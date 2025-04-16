# 💳 Card Limit Validation System (Oracle SQL)

This project simulates a credit card transaction limit system using Oracle SQL. It demonstrates how to:

- Create a `dataholder` table with card details
- Detect and handle duplicate records
- Apply a primary key constraint
- Build a PL/SQL function to validate card transaction limits
- Return user-friendly messages like:
  - `Limit exceeded. Your limit is: XXXX`
  - `Withdrawal allowed. Remaining limit: XXXX`

## 📁 Files Included
- `card_limit_validation.sql` – Full working script with insert, validation, and clean-up steps

## ✅ Run Steps
1. Open Oracle SQL Developer
2. Run the entire `card_limit_validation.sql` script
3. Use anonymous block or `SELECT` to test the validation function

## 🧠 Concepts Used
- SQL DDL & DML
- Constraints
- ROWID usage
- PL/SQL Functions
- Exception Handling
- `DBMS_OUTPUT.PUT_LINE`

## 💬 Sample Output
```sql
Result: Limit exceeded. Your limit is: 75000
