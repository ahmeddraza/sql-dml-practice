# sql-dml-practice
This project contains my practice work using SQL DML (Data Manipulation Language) commands such as `INSERT`, `UPDATE`, `DELETE`, and `SELECT` on a real-world dataset.

## Dataset
I practiced on an **Insurance dataset**, which contains fields like age, region, blood pressure, BMI, and patient ID.

## Skills Practiced
- `INSERT INTO` for adding new rows
- `UPDATE` for modifying existing values
- `DELETE` to remove records
- `SELECT` queries using:
  - `WHERE`, `BETWEEN`, `NOT IN`, `DISTINCT`, `COUNT`, etc.
  - Mathematical expressions and filtering

## Sample Query
```sql
SELECT COUNT(*) 
FROM insurance_data 
WHERE age < 17 
AND blood_pressure BETWEEN (80 + age * 2) AND (100 + age * 2);
