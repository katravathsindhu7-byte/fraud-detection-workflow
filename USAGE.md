# How to Use the Fraud Detection Workflow

## ▶️ Steps to Run

1. Open n8n application
2. Import the workflow.json file
3. Click on "Execute Workflow"
4. Provide transaction input in the message field
5. Run the workflow

## 📌 Input Format

Enter transaction details like:
- Amount
- Location
- Time (optional)

### Example Input:
"20000 transferred from unknown location at midnight"

## ⚙️ Processing

The system checks:
- If the transaction amount is greater than 10000
- If the location is unknown

## 📊 Output

Based on conditions, the output will be:

- FRAUD ⚠️ → If transaction is suspicious
- SAFE ✅ → If transaction is normal

## 🧪 Example

Input:
"20000 from unknown location"

Output:
FRAUD ⚠️

---

Input:
"5000 from known location"

Output:
SAFE ✅
