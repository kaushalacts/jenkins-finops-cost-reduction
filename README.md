# Jenkins FinOps CI/CD Cost Reduction

This project sets up a Jenkins server integrated with AWS S3 to reduce operational costs. Jenkins job histories are archived periodically and moved into **S3 Glacier Deep Archive** storage class using AWS CLI.

---

## 🚀 Features

- Automatically archives old Jenkins jobs/logs to S3
- Reduces EBS volume and storage costs
- Integrates with Jenkins CI/CD setup
- Applies FinOps principles to optimize infrastructure spend
- Uses AWS CLI and simple shell scripting

---

## 🧱 Architecture

 ![image](https://github.com/user-attachments/assets/efa8c166-a7d5-4ac0-b749-7c7de10285b9)

**Flow:**
1. Jenkins server hosts CI/CD jobs
2. `s3_job_archive.sh` scans and compresses job history
3. Compressed archives are pushed to an S3 bucket
4. Archives are stored using the `GLACIER_DEEP_ARCHIVE` storage class
