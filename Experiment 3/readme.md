# 📘 Experiment 03: Department Salary Champions Explorer  

**UID:** 23BCS13053  
**Section/Group:** KRG-2B  
**Date of Performance:** 19/08/25  
**Subject Code:** 23CSP-333  
**Department of Computer Science & Engineering**  

---

## 🎯 Aim  
To design and implement SQL queries that identify the highest-paid employees within each department and merge historical employee records from two systems to extract the lowest recorded salaries.  

---

## 📖 Problem Statement  

### Part A – Department Salary Champions (Medium Level)  
In a bustling corporate organization, every department strives to retain its top talent. Given employee records with salaries and department details, the task is to:  
- Identify the **top earners** in every department.  
- If multiple employees share the same maximum salary, include all of them.  
- Display the **department name, employee name, and salary** sorted by department.  

---

### Part B – Merging Employee Histories: Who Earned Least? (Hard Level)  
Two legacy HR systems (**System A** and **System B**) maintain separate salary records. These may overlap. The task is to:  
1. Merge records from both systems.  
2. For each **EmpID**, return the **lowest recorded salary** across both systems along with the employee’s name.  

---

## 🎯 Objectives  
- To understand and implement **sub-queries** in SQL.  
- To identify the **top earners per department** using correlated sub-queries.  
- To handle scenarios where multiple employees share the same maximum salary.  
- To merge datasets from multiple sources using **UNION ALL**.  
- To apply **GROUP BY** with aggregate functions (**MAX**, **MIN**) for reporting.  
- To extract the lowest salary per employee across merged datasets.  
- To enhance problem-solving skills for **analytical database queries**.  

---

## 📊 Output  

### **Output 1 – Department Salary Champions**  
| DEPT_NAME | NAME  | SALARY |  
|-----------|-------|--------|  
| IT        | JIM   | 90000  |  
| IT        | MAX   | 90000  |  
| SALES     | HENRY | 80000  |  

---

### **Output 2 – Merging Employee Histories (Lowest Salary)**  
| EMPID | ENAME | SALARY |  
|-------|-------|--------|  
| 1     | AA    | 1000   |  
| 2     | BB    | 300    |  
| 3     | CC    | 100    |  

---

## 📝 Learning Outcomes  
- Implemented **correlated sub-queries** to extract top salary earners by department.  
- Handled cases with **multiple employees sharing the same max salary**.  
- Successfully merged data from two systems using **UNION ALL**.  
- Applied **GROUP BY** with aggregate functions (**MAX**, **MIN**) for insights.  
- Learned how to retrieve **minimum salary records** across datasets.  
- Strengthened SQL querying skills for **real-world analytical use cases**.  
