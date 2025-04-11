# 🚀 AWS S3 Static Website Hosting Guide (with Versioning)

This repository contains a complete step-by-step guide (with screenshots) to hosting a **static website** using **Amazon S3**. It also includes **S3 Versioning**, which allows tracking changes and restoring previous versions of website files — a critical concept in production environments.

## 📄 PDF Guide

Click below to view or download the complete walkthrough:

👉 [AWS S3 Website Hosting - Step by Step (PDF)](./AWS-S3-Static-Website-Hosting.pdf)

## 🌐 Live Demo

This website was previously hosted on AWS S3 as part of a learning project.  
To avoid unnecessary charges, the resources have been deleted.  
📄 Please refer to the PDF above for full deployment steps and screenshots.

## 🧠 What I Learned

- Creating and configuring an S3 bucket
- Enabling static website hosting on S3
- Uploading HTML/CSS files
- Making bucket objects public
- Setting bucket policy for public read access
- **Enabling versioning** to track changes in files
- Restoring previous file versions in case of accidental overwrite or deletion
- Accessing the website through S3’s public endpoint

## 📂 Project Structure

AWS-S3-Static-Website-Hosting/ ├── AWS-S3-Static-Website-Hosting.pdf # Full PDF walkthrough with screenshots ├── index.html # Homepage (demo site) ├── about.html # About page ├── contact.html # Contact page ├── css/ │ └── style.css # Website styling ├── images/ │ └── logo.png # Logo used in the demo └── README.md # Project description and usage guide

markdown
Copy code

## 🔧 Tools & Technologies Used

- **Amazon Web Services (AWS)**
  - S3 (Simple Storage Service)
  - IAM (Identity & Access Management)
  - **Versioning (Object-level backup and history)**
- **HTML/CSS (for demo site)**
- **GitHub (for documentation)**

## 💡 Why S3 Versioning?

Versioning in S3 allows:
- Recovering overwritten files
- Tracking changes to website assets
- Protection from accidental deletes
- A production-grade hosting setup

## 🖼️ Screenshots Included

The PDF contains detailed screenshots of:
- Bucket creation and settings
- Website configuration
- Access permissions
- Versioning setup
- Final hosted result

## 📬 About Me

I’m actively learning and building in Cloud and DevOps. This project is a part of my AWS learning journey.  
📌 Let’s connect:

- GitHub: [github.com/GauravWeb-Dev](https://github.com/GauravWeb-Dev)  
- LinkedIn: [linkedin.com/in/gaurav-sardar](https://www.linkedin.com/in/gaurav-sardar)

---

⭐ Like this repo? Give it a star and help it reach more learners!
