# Excel Practice

This repository contains my Excel practice files as part of my Data Analyst preparation.

---

## 📂 Files

### 1. `practice.xlsx`

**Topics covered:**

- Employee dataset structure
- Text cleaning functions  
  - `LEFT`, `RIGHT`, `MID`, `LEN`, `TRIM`, `PROPER`, `UPPER`, `LOWER`
- Logic functions  
  - `IF`, `AND`, `OR`, `NOT`
- Basic formulas  
  - `SUM`, `AVERAGE`, `COUNT`, `COUNTA`, `COUNTBLANK`, `MAX`, `MIN`
- Basic formatting and colour scaling
- Data validation with drop-down lists

---

### 2. `Sorting_Filtering.xlsx`

**Dataset:** Employee table with EmpID, Name, Dept, Age, JoinDate, Salary, City, Status.

**Sorting tasks included:**

1. **Salary High → Low**  
   - Sorted the Salary column in descending order to identify highest-paid employees first.

2. **Name A → Z**  
   - Sorted the Name column alphabetically.

3. **Department A → Z, then Salary High → Low**  
   - Applied a multi-level sort:  
     - Primary sort by Department (A → Z)  
     - Secondary sort by Salary (Largest → Smallest) within each department.

4. **JoinDate Oldest → Newest**  
   - Sorted employees by their joining date to see who joined earliest vs latest.

5. **Status (Active first), then Age (Low → High)**  
   - Multi-level sort:  
     - Primary sort by Status (Active before Resigned)  
     - Secondary sort by Age (youngest to oldest) within each status group.

**Filtering tasks included:**

- Show only **IT** employees  
- Filter employees with **Salary > 50,000**  
- Filter employees who **joined after 2020**  
- Filter employees with **Age between 25 and 40**  
- Show only **Resigned** employees  
- Filter cities that **start with "S"**  
- Filter names that **contain the letter "a"**  
- Use **conditional formatting** to highlight salaries above a threshold, then filter by color

This file demonstrates practical Excel skills used in real data analysis:
- Sorting (single and multi-level)
- Filtering (basic and advanced)
- Conditional formatting
- Working with a structured employee dataset
