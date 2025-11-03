# Family-Expenses-Calculator
The project “Calculating Family Expenses using ServiceNow” aims to develop a smart and automated expense management system to help families efficiently monitor and control their monthly financial activities. The system is built using ServiceNow, a cloud-based platform that provides workflow automation and data management capabilities.

# 🏡 Calculating Family Expenses using ServiceNow

In today’s fast-paced world, managing household expenses has become a crucial aspect of maintaining financial stability. Families often struggle to keep track of their daily, monthly, and yearly expenditures, leading to financial stress and poor budgeting. To overcome these challenges, digital solutions that automate expense tracking and provide clear financial insights are becoming increasingly important.
---

## 🎯 Project Objectives

->To automate the calculation of family expenses
->To provide an easy-to-use interface for expense entry
->To compare total expenses with monthly income or budget
-> To categorize and analyze expenses effectively
->To generate reports and visual dashboards

---

## 🛠️ Features Implemented

| Feature                           | Description |
|----------------------------------|-------------|
| ✅ Family Expenses Table         | Stores family name, budget, category, etc. |
| ✅ Daily Expenses Table          | Stores individual spending records |
| ✅ Reference Fields              | Links Daily Expenses to Family |
| ✅ Related List View             | Daily records shown under each family |
| ✅ Business Rule (Optional)      | Warns if total spending exceeds the set budget |

---

## 🧱 Tables Created

### 1. `Family Expenses`
- Family Name (String)
- Category (Choice: Food, Rent, etc.)
- Monthly Budget (Currency)
- Total Spent (Currency)
- Notes (String)


### 2. `Daily Expenses`
- Family (Reference to Family Expenses)
- Date (Date)
- Item (String)
- Amount (Currency)
- Notes (String)

---

## 🔄 Data Flow

1. Add a family in `Family Expenses`
2. Add daily expenses in `Daily Expenses` (linked to family)
3. View all expenses linked to a family via related list
4. If Business Rule is active: you'll be warned when budget is exceeded

---

## 🖼️ Screenshots

All screenshots of the project setup are available inside the `/Screenshots/` folder:


## 📚 Tools Used

- **Platform:** ServiceNow (Personal Developer Instance)
- **Type:** Low-Code / No-Code development
- **Database:** Glide Tables in ServiceNow
- **Logic:** Business Rules (JavaScript)

---

## 🙋‍♀️ Developed By  Renuka



