# AWS Static Website Hosting using S3 and CloudFront

## 📌 Project Overview
This project demonstrates how to deploy a highly available and globally distributed static portfolio website using Amazon S3 and Amazon CloudFront under AWS Free Tier.

The goal was to implement secure static hosting, configure public access policies properly, and integrate a CDN for performance optimization.

---

## 🏗 Architecture

User → Amazon CloudFront → Amazon S3 (Static Website Hosting)

---

## 🛠 AWS Services Used

- Amazon S3
- Amazon CloudFront
- AWS Billing & Budget Alerts

---

## ⚙️ Implementation Steps

1. Created S3 bucket in ap-south-1 region.
2. Disabled block public access (for static hosting).
3. Enabled static website hosting.
4. Configured bucket policy for public read access.
5. Uploaded website files.
6. Created CloudFront distribution with S3 website endpoint as origin.
7. Configured default root object (index.html).
8. Enabled HTTPS redirection.
9. Verified global website access via CloudFront.

---

## 🔐 Security Considerations

- No IAM credentials exposed.
- Bucket policy restricted to GetObject only.
- No EC2, RDS, NAT Gateway, or paid services used.
- Budget alerts configured to prevent unexpected billing.

---

## 💰 Cost Optimization

- Used AWS Free Tier only.
- No Route 53 (to avoid hosted zone charges).
- All resources deleted after project completion.

---

## 📷 Screenshots

Screenshots are available in the /screenshots directory.

---

## 🚀 Outcome

Successfully deployed a globally distributed static website using AWS S3 and CloudFront while maintaining zero cost through careful monitoring and resource cleanup.

