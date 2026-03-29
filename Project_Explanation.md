# Project Explanation

## 📌 Overview
This project is a fraud detection workflow created using n8n.

## ⚙️ Working Process
1. A transaction message is given as input
2. The system checks:
   - Transaction amount
   - Transaction location
3. IF condition is applied

## 🚨 Logic Used
- If amount > 10000
- AND location is unknown

## 🎯 Result
- FRAUD ⚠️ → if both conditions are true
- SAFE ✅ → otherwise

## 🧠 Conclusion
This is a simple rule-based fraud detection system which can be extended using AI models for better accuracy.
