# Fraud Detection Workflow (n8n)

## 📌 Project Overview
This project detects fraudulent transactions using a rule-based workflow in n8n.

## ⚙️ How it Works
The system checks:
- Transaction amount
- Transaction location

## 🚨 Conditions
- If amount > 10000 AND location is unknown → FRAUD ⚠️
- Otherwise → SAFE ✅

## 🛠️ Tools Used
- n8n (workflow automation)
- GitHub (version control)

## 🎯 Output
- FRAUD ⚠️
- SAFE ✅

## 📂 File
- workflow.json (contains the full workflow)

## 🚀 Future Improvement
- Add AI-based fraud detection
- Send SMS/Email alerts
