# 🚀 Symplichain Hackathon Submission

## 👨‍💻 Candidate
Dhanush Korlepara

---

## 📌 Overview
This repository contains my solution for the Symplichain Software Engineering Intern Hackathon.

The goal of this assignment was to design scalable systems, build deployment pipelines, and demonstrate structured debugging approaches using a modern tech stack.

---

## 🧠 What I Focused On
- Designing a **rate-limited shared gateway** handling high traffic efficiently  
- Ensuring **fair request distribution across customers**  
- Building a **mobile-first architecture** optimized for real-world usage  
- Creating a **CI/CD pipeline using GitHub Actions**  
- Following a **step-by-step debugging strategy** instead of guesswork  

---

## 🏗️ Tech Stack
- Backend: Django, Django REST Framework  
- Frontend: React  
- Queue System: Celery + Redis  
- Database: PostgreSQL (RDS)  
- Cloud: AWS (EC2, S3, CloudFront)  
- CI/CD: GitHub Actions  

---

## ⚙️ CI/CD Workflows
Located in:
.github/workflows/


- `staging-deploy.yml` → Deploys to staging environment  
- `production-deploy.yml` → Deploys to production environment  

---

## 📄 Documentation
Full detailed explanation is available in the PDF submission.

---

## 🎯 Key Highlights
- Used **Celery rate limiting** to enforce API constraints  
- Implemented **round-robin fairness strategy**  
- Applied **exponential backoff retry mechanism**  
- Designed **low-friction mobile interaction model**  
- Followed **systematic debugging flow**  

---

## 🙌 Note
This solution focuses on **clear reasoning, simplicity, and practical design decisions** rather than over-engineering.

---
