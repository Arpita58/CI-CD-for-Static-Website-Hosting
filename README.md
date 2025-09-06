# 🚀 Push Code → Go Live (CI/CD on AWS S3)

This project is all about making deployments simple.  
I set up a **CI/CD pipeline** that hosts a static website on **Amazon S3**.  
Now, whenever I push code to GitHub, the website updates automatically 🎉  

---

## ✨ What It Does
- Hosts a static website using **S3 Static Website Hosting** 🌐  
- Automates deployment with **GitHub Actions** ⚡  
- Every `git push` → new website goes live 🚀  

---

## 🏗️ How I Built It (Steps)
1. **Created an S3 bucket** and enabled **Static Website Hosting**.  
2. **Configured bucket policy** to allow public read access.  
3. **Connected GitHub repo** with a workflow file (`deploy.yml`).  
4. **Set up IAM user + access keys** for GitHub Actions.  
5. **Wrote GitHub Actions workflow** to sync code → S3 on each push.  
6. **Pushed my website code**, and boom 💥 it went live automatically!  

---

## 🔧 Tech Stack
- **AWS S3** – Static website hosting  
- **GitHub Actions** – CI/CD pipeline  
- **IAM** – Secure access to AWS  
