# Task 1 – AWS S3 Cloud Storage Setup

## ✅ Objective:
Set up and configure cloud storage using **AWS S3**. Upload example files and manage access permissions.

---

## 📦 Bucket Details
- **Bucket Name:** vanshika.cloud.bucket 
- **Region:** ap-south-1 (Mumbai)
- **Versioning:** Disabled
- **Public Access:** Enabled for individual files via bucket policy (see below)

---

## 📁 Files Uploaded
1. image.jpg
2. notes.txt
3. resume.pdf
4. presentation.pptx
5. report.docx
6. data.csv

Uploaded using AWS Console.

---

## 🔐 Access Configuration

### Method 1: Public Access via Bucket Policy
- Public access granted to `image.jpg` for demo.
- Bucket policy configured (see `bucket-policy.json` file).

### Method 2: Pre-Signed URL (Private File Access)
Generated pre-signed URL to share file securely for limited time.

---

## 🖼️ Screenshots
- Bucket creation
- File upload
- Access permissions
- File preview link

(All screenshots are in `/screenshots/` folder.)

---

## 🔗 Links
- [View bucket](https://s3.console.aws.amazon.com/s3/buckets/vanshika.cloud.bucket)
- [Public file link (if enabled)](https://vanshika.cloud.bucket.s3.amazonaws.com/image.jpg)

---

## 👩‍💻 Tools Used
- AWS Console
- GitHub
