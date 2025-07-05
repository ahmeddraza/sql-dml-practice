# sql-dml-practice

This project contains my practice work using SQL DML (Data Manipulation Language) commands such as `INSERT`, `UPDATE`, `DELETE`, and `SELECT` on a real-world dataset.

## 📂 Dataset

The dataset used for this project is [`insurance_data - insurance_data.csv`](./data/insurance_data - insurance_data.csv), located in the `data/` folder.

It contains fields like:
- `PatientID`
- `Age`
- `Region`
- `Blood_Pressure`
- `BMI`
- `Charges` (optional)

📌 **Source**: *https://www.google.com/url?q=https%3A%2F%2Fdocs.google.com%2Fspreadsheets%2Fd%2Fe%2F2PACX-1vRa1wWwXmzxEvqITxj4OQTeLywlGTTsOTbhSRqKj2lPuGefjlci-DQhgLBPpgWXe8AAUu2WUBqY59X1%2Fpub%3Fgid%3D1030172542%26single%3Dtrue%26output%3Dcsv*

## 🛠️ Skills Practiced

- `INSERT INTO` for adding new rows  
- `UPDATE` for modifying existing values  
- `DELETE` to remove records  
- `SELECT` queries using:
  - `WHERE`, `BETWEEN`, `NOT IN`, `DISTINCT`, `COUNT`, etc.
  - Mathematical expressions and filtering

## 🧠 Sample Query

```sql
SELECT COUNT(*) 
FROM insurance_data 
WHERE age < 17 
  AND blood_pressure BETWEEN (80 + age * 2) AND (100 + age * 2);
