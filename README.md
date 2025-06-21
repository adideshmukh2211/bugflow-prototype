#  BugFlow Prototype – No-Code + GitOps Bug Reporting System

## 📌 Overview
BugFlow is a lightweight prototype that demonstrates how to combine **No-Code platforms** and **GitOps workflows** for rapid and reliable bug reporting.

## 🧩 Tech Stack
- 🧾 **Frontend**: Rebolt (No-Code Form Builder)
- 📥 **Data Capture**: Manual CSV Export from Rebolt
- 🗂️ **Backend**: GitHub Repo (`bug-reports.csv`)
- ⚙️ **Automation**: GitHub Actions CI/CD for simulated deployment

## 🔁 Workflow
1. Tester submits a bug via the Rebolt Form
2. Submission data is exported manually to CSV
3. CSV is committed to GitHub as `bug-reports.csv`
4. GitHub Actions triggers `deploy.yml`, simulating deployment

## 📂 File Structure
📁 .github
└── workflows
└── deploy.yml
📄 bug-reports.csv


## 🚀 Simulated Output
Each update triggers a deployment workflow:

📦 New bug report received!
🛠️ Deploying changes using GitOps simulation...
✅ Deployment simulated successfully


## 🎯 Goal
This project showcases how organizations can build practical internal tools combining **speed (No-Code)** and **stability (GitOps)** — using entirely **free tools**.

