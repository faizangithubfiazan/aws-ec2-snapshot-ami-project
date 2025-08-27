# aws-ec2-snapshot-ami-project
“AWS EC2 project demonstrating Snapshots &amp; AMI for backup and recovery"
# AWS EC2 Snapshot & AMI Project 🚀

## 📌 Project Overview
This project demonstrates how to create an **EC2 instance backup** using **EBS Snapshots** and **AMI (Amazon Machine Image)**, and how to restore it successfully.

## 🛠️ Steps Performed
1. Launched an **EC2 instance** and installed Apache (httpd).
2. Deployed a custom webpage (`index.html`) showing:  
   *“Hello, This is My Apache Web Server 🚀”*
3. Created a **Snapshot** of the EBS volume (data backup).
4. Terminated the original instance (to simulate data loss).
5. Created an **AMI** from the Snapshot.
6. Launched a **new EC2 instance** from the AMI and verified the Apache page.

## ✅ Key Learnings
- How to create and manage Snapshots in AWS.
- How to create an AMI from a Snapshot.
- How Snapshots and AMIs help in **disaster recovery**.
- Importance of **backups** in cloud infrastructure.

## 📷 Screenshots
| Step | Screenshot |
|------|------------|
| EC2 instance running with Apache | ![EC2 Instance](screenshots/ec2-instance-running.png) |
| Snapshot created | ![Snapshot](screenshots/snapshot-created.png) |
| AMI created | ![AMI](screenshots/ami-created.png) |
| Restored instance Apache page | ![Restored Instance](screenshots/restored-instance.png) |

## 🔗 LinkedIn Post
Check out my LinkedIn post about this project 👉 [Add Your LinkedIn Post Link Here]

---
