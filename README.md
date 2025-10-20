# ☁️ AWS S3 Storage Bucket — Task 1

## 📘 Project Overview
This project demonstrates how to create a **Cloud Storage Bucket** and upload files using **Amazon S3 (Simple Storage Service)** through the **AWS Management Console**.

It is part of a cloud computing fundamentals exercise to understand how **object storage** works in the cloud environment.

---

## 🎯 Objective
- Learn the concept of **object storage**.
- Create an **S3 bucket** in AWS.
- Upload and manage objects (files).
- Test file accessibility via a **public URL**.

---

## 🧰 Tools & Services Used
- **Amazon Web Services (AWS)**
- **S3 (Simple Storage Service)**
- **AWS Management Console (Web UI)**
- **Any sample file** (text/image)
- *(Optional)* AWS Free Tier account

---

## 🪣 Steps to Reproduce

### Step 1 — Create AWS Account
1. Visit [https://aws.amazon.com](https://aws.amazon.com)
2. Sign up for a **Free Tier account**.
3. Sign in to the **AWS Management Console**.

---

### Step 2 — Open S3 Service
1. In the AWS Console search bar, type **S3**.
2. Select **S3** under *Services → Storage*.

---

### Step 3 — Create a Bucket
1. Click **Create bucket**.
2. Provide a **unique bucket name** (e.g., `storage-bucket-demo-2025`).
3. Select your desired **region** (e.g., `US East (N. Virginia)`).
4. Leave other settings default.
5. *(Optional)* Uncheck **Block all public access** if you want public access to your files.
6. Click **Create bucket**.

✅ Your new S3 bucket is now ready.

---

### Step 4 — Upload Files
1. Click on your bucket name.
2. Select **Upload → Add files**.
3. Choose any file (e.g., `test.txt`, `image.png`).
4. Click **Upload**.
5. Wait for the **“Upload succeeded”** message.

---

### Step 5 — View File Details
1. Click your uploaded file to open **Object details**.
2. You will see:
   - Object name
   - Size and type
   - **Object URL**
  
     
---

### Step 6 — Make File Public (Optional)
If public access is disabled:
1. Select the file.
2. Click **Actions → Make public using ACL** (or “Make public” button).
3. Copy the **Object URL**.
4. Open it in your browser to confirm accessibility.

---
## 🧑‍💻 Author

**Shrihari Mohite**  
📦 Repository: [Storage_Bucket_S3](https://github.com/ShrihariMohite/Storage_Bucket_S3)


