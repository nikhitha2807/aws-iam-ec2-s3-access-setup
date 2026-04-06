# aws-iam-ec2-s3-access-setup
IAM user setup with EC2 access via policy and S3 access via group in AWS Free Tier.
# 🚀 AWS IAM User Setup (EC2 + S3 Access)

## 📌 Project Overview

This project demonstrates how to create an IAM user in AWS with:

* EC2 access using a direct policy
* S3 access using a group

---

## 🧰 Services Used

* AWS IAM
* Amazon EC2
* Amazon S3

---

## 👤 Step 1: Create IAM User

1. Go to AWS Console → IAM
2. Click **Users → Create User**
3. Enter username
4. Select **Provide user access to AWS Management Console**
5. Set password

---

## 🔐 Step 2: Attach EC2 Policy (Direct)

1. In permissions → Click **Attach policies directly**
2. Search and select: `AmazonEC2FullAccess`
3. Continue and create user

---

## 👥 Step 3: Create Group for S3 Access

1. Go to IAM → **User Groups → Create Group**
2. Group name: `S3AccessGroup`
3. Attach policy: `AmazonS3FullAccess`
4. Create group

---

## ➕ Step 4: Add User to Group

1. Open the created user
2. Go to **Groups → Add user to group**
3. Select `S3AccessGroup`
4. Save

---

## ✅ Final Result

* IAM user has:

  * EC2 access via direct policy
  * S3 access via group

---

## 🎥 Demo Video

https://youtu.be/GzAgSZAyI2w?si=ufycuFwYf5SwVhXZ

---

## 📌 Conclusion

This setup follows AWS best practices by:

* Using groups for managing permissions (S3)
* Assigning specific access directly where needed (EC2)

---

## Nikhitha Athem

Your Name

