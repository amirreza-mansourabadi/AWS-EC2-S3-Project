# AWS EC2 to S3 Secure Access Project

This project demonstrates how to configure an AWS EC2 instance with an attached IAM role to securely access a private S3 bucket. The goal is to use least-privilege access controls so the EC2 instance can read/write to the bucket without exposing credentials, while maintaining proper auditing and security practices.

---

## Key Features

- **EC2 Instance with IAM Role**: Uses an attached IAM role for secure, credential-free access to S3.  
- **Least-Privilege S3 Access**: IAM policies restrict the EC2 instance to only the permissions needed.  
- **Proof of Work**: Includes screenshots of EC2 login, IAM role, and successful S3 access.

---

## Project Screenshots

### 1️⃣ EC2 Login
![EC2 Login](screenshots/EC2-Login.png)  
*Shows SSH login to the EC2 instance.*

### 2️⃣ IAM Role Attached to EC2
![EC2 IAM Role](screenshots/EC2-IAM-Role.png)  
*Shows the IAM role attached to the EC2 instance.*

### 3️⃣ S3 Access from EC2
![EC2 S3 Access](screenshots/EC2-S3-Access.png)  
*Shows successful access to the S3 bucket from the EC2 instance.*

---

## Project Files

- [S3SecureProjectPolicy.json](S3SecureProjectPolicy.json) – IAM policy allowing EC2 access to the S3 bucket.

---

## Skills Demonstrated

- AWS EC2 configuration and SSH access  
- IAM role attachment and least-privilege access control  
- Secure S3 bucket access from EC2  
- Cloud security best practices

---

## How to Use

1. Clone this repository.  
2. Review the IAM policy JSON file to understand permission boundaries.  
3. Launch your own EC2 instance and attach the IAM role as shown in the screenshots.  
4. Verify access to your S3 bucket by following the examples in the screenshots.

---

## License

This project is licensed under the [MIT License](LICENSE).  
See the LICENSE file for full details.
