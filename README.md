# 💰 AI Personal Finance Assistant (UiPath)

## 📌 Overview

This project is an AI-powered Personal Finance Assistant built using UiPath.
It reads expense data from Excel, categorizes transactions using AI, and generates financial insights.

---

## 🚀 Features

* 📂 Read expense data from Excel
* 🤖 Categorize expenses using AI
* 🧠 Generate spending insights
* 📄 Export insights to a text file

---

## 🛠️ Technologies Used

* UiPath Studio
* Generate Content Activity (AI)
* Excel Automation
* JSON (Serialize JSON)

---

## 📂 Workflow

1. Read data from Excel
2. Loop through each transaction
3. Send data to AI for categorization
4. Update category in DataTable
5. Convert DataTable to JSON
6. Generate final financial insight using AI
7. Save output to `Report.txt`

---

## 📊 Input Format

| Date       | Description | Amount | Category |
| ---------- | ----------- | ------ | -------- |
| 01-04-2026 | Swiggy      | 250    |          |
| 01-04-2026 | Amazon      | 1200   |          |

---

## 📄 Output (Report.txt)

Example:

Summary of spending:

* Total spent: Rs 9250
* Highest category: Food

Suggestions:

* Reduce food expenses
* Limit online shopping

---

## 🎯 Use Case

This bot helps users:

* Automatically categorize expenses
* Understand spending patterns
* Get simple financial suggestions

---

## 📌 Future Improvements

* Excel dashboard with charts
* Email notifications
* Web interface

---

## 👨‍💻 Author

Raghun
Software Intern – RPA & Agentic AI Automation

---
