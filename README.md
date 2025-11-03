# Family-Expenses-Calculator
“Calculating Family Expenses using ServiceNow” is a low-code/no-code application that helps users manage and track family spending. Built entirely on the ServiceNow platform, this system allows families to record daily expenses, categorize them.


# 🏡 Calculating Family Expenses using ServiceNow

This project is a Family Expense Tracking system built entirely within **ServiceNow**. It helps families manage and track daily expenses, compare them against monthly budgets, and visualize categorized spending. Built using tables, references, and business logic — this is a low-code/no-code ServiceNow solution.

---

## 🎯 Project Objectives

- Track daily expenses for each family
- Categorize expenses: Food, Rent, Utilities, Education, Misc
- Set monthly budgets for each family
- Automatically warn if spending exceeds budget
- Display real-time expense data linked to families

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

## 🙋‍♀️ Developed By  Harika  



