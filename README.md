# 🚀 DevOps Internship Task 3 – Deploying a Frontend Website on AWS EC2 using Terraform

## 🎯 Objective
The main aim of this project is to **deploy a static frontend website (HTML, CSS, JavaScript)** on **AWS EC2** using **Terraform Infrastructure as Code (IaC)**.  
This shows the ability to automate cloud infrastructure setup and application deployment using DevOps practices.

---

## 🛠️ Tools & Technologies Used
- **Terraform v1.13.3** → Infrastructure as Code
- **AWS CLI** → Cloud authentication & configuration
- **AWS EC2 (t2.micro)** → Virtual server
- **IAM User + Access Keys** → Secure AWS access
- **Apache Web Server (httpd)** → To serve frontend files
- **GitHub** → Version control and project submission

---

## 🚀 Steps Followed
1. Installed **AWS CLI** and configured with IAM Access Keys (`aws configure`).
2. Installed **Terraform v1.13.3** on Windows.
3. Created `main.tf` Terraform script to:
   - Create a **Security Group** (allow SSH :22 and HTTP :80).
   - Launch an **EC2 instance** in AWS.
   - Install and start **Apache Web Server**.
4. Connected to EC2 using **SSH** and deployed frontend files (`index.html`, `style.css`, `script.js`) into `/var/www/html/`.
5. Verified website is accessible via **EC2 Public IPv4 address**.
6. Captured screenshots of each step for proof.

---

## 📸 Screenshots

### Terraform Init
![Terraform Init](screenshots/terraform-init.png)

### Terraform Plan
![Terraform Plan](screenshots/terraform-plan.png)

### Terraform Apply
![Terraform Apply](screenshots/terraform-approve.png)

### EC2 Instance Running
![EC2 Running](screenshots/ec2-running.png)

### Website Live
![Website Live](screenshots/output-live.png)

*(Optional)* Terraform Destroy  
![Terraform Destroy](screenshots/terraform-destroy.png)

---

## ✅ Outcome
- A working **frontend website** deployed on AWS EC2.
- Infrastructure fully automated with **Terraform**.
- Demonstrated knowledge of **Cloud, DevOps, and IaC** practices.
- GitHub repo contains:
  - `main.tf`
  - `index.html`, `style.css`, `script.js`
  - `screenshots/`
  - `README.md`

---

## 📌 How to Reproduce
1. Clone this repo:
   ```bash
   git clone https://github.com/Kamalkumar25/Elevate_labs_task_3.git
   cd Elevate_labs_task_3
