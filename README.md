# 🌐 Secure Static Website Hosting on AWS

This project demonstrates how to host a secure, scalable, and cost-effective static website using Amazon Web Services. The site uses Amazon S3 for hosting, CloudFront for CDN and HTTPS, and CloudWatch for logging.

---

## 🔧 Technologies Used

- **Amazon S3** – Primary site hosting (Bucket: `nvrjansen-portfolio`)
- **CloudFront** – Global CDN with HTTPS
- **AWS Certificate Manager** – Free SSL certificate
- **IAM** – Principle of least privilege for access control
- **S3 Access Logs** – Sent to `nvjansen` logging bucket
- **AWS CLI** – Infrastructure setup and deployment
- **GitHub** – Project source and documentation

---

## 🔐 Security Features

- **Public access blocked** at bucket level; access granted via CloudFront
- **HTTPS enforced** with `Redirect HTTP to HTTPS` policy
- **Logging enabled** for auditing and monitoring
- **IAM policies** used to restrict access to upload-only roles

---

## 📁 File Structure
secure-static-website-aws/
├── index.html
├── policy.json
├── README.md
