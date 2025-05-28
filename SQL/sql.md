# SQL Practice Repository

## 🧩 Problem: Journey Start & End Location

Given a list of customer flights, find the first origin and final destination for each customer.

---

### 📥 Input Table

| cust_id | flight_id | origin     | destination |
|---------|-----------|------------|-------------|
| 1       | SG1234    | Delhi      | Hyderabad   |
| 1       | SG3476    | Kochi      | Mangalore   |
| 1       | 69876     | Hyderabad  | Kochi       |
| 2       | 68749     | Mumbai     | Varanasi    |
| 2       | SG5723    | Varanasi   | Delhi       |

---

### 📤 Expected Output

| cust_id | Origin | Final_destination |
|---------|--------|-------------------|
| 1       | Delhi  | Mangalore         |
| 2       | Mumbai | Delhi             |

---

### 🧠 SQL Concepts

- `CTE` (Common Table Expression)
- `NOT IN` for filtering unmatched origins/destinations
- Simple `JOIN` to relate start and end points

📂 SQL File: [`queries/path_tracing_journey.sql`](queries/path_tracing_journey.sql)
