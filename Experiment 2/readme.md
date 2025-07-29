### ✅ [Experiment 2](./experiment2.sql)
**Aim:**  
Design normalized schemas using SQL to represent employee-manager and financial data. Implement joins, self-joins, and NULL handling.

#### 🔹 Part A – Medium Level:
- Create `Employee_tbl` with a self-referencing foreign key (`Manager_ID`).
- Use `LEFT OUTER JOIN` for retrieving employees and their manager details.
- Display employee name, manager name, and their respective departments.

#### 🔹 Part B – Hard Level:
- Create `Year_tbl` and `Queries` to track financial NPV over time.
- Insert multiple NPV records and corresponding query requests.
- Use `LEFT JOIN` to retrieve records and handle missing values with `ISNULL()`.

---
