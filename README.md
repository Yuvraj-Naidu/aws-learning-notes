# AWS Learning Notes ☁️

This repository documents my daily AWS learning journey as I transition from QA → DevOps Engineer.

---

## Day 1 – AWS Account Setup & Core Concepts

### 1️⃣ AWS Account Creation
- Created AWS root account
- Understood why root account should **never be used daily**

### 2️⃣ IAM Setup (Security First 🔐)
- Created IAM Admin User
- Attached **AdministratorAccess** policy
- Logged in using IAM user instead of root

### 3️⃣ Enabled MFA
- Enabled Multi-Factor Authentication for root + IAM user
- Learned why MFA is critical for cloud security

### 4️⃣ Regions & Availability Zones
Learned the basics of AWS global infrastructure:
- Region = Geographic area (ex: ap-south-1 Mumbai)
- Availability Zone = Isolated datacenter within a region
- High availability achieved by using multiple AZs

---

## Key Takeaways
- Never use root account for daily tasks
- Always enable MFA
- IAM is the foundation of AWS security
- Regions & AZs are the base of cloud architecture
