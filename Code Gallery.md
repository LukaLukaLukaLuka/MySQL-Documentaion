## **1.** 
```SQL
CREATE Table employess (
    employee_id INT,
    first_name VARCHAR(15),
    last_name VARCHAR(30),
    hourly_pay DECIMAL(4, 2),
    hire_date DATE
);
```
- Seperate columns with commas
- Dont forget the infotype
---
## **2.**
```SQL
INSERT Into employees
VALUES (001, "Eugene", "Krabs",90.00,"2025-03-20"),
       (002, "Squidward", "Tentacles", 15.00, "2025-01-03"),
       (003, "Spongebob", "Squarepants", 15.00, "2025-02-16"),
       (004, "Sandy", "Cheeks", 17.25, "2024-12-28");
 ```
- Date Syntax: *YYYY*-*MM*-*DD*
- Seperate info with commas
- If you are not putting all the data inside, then use `INSERT INTO employees (employee_id, first_name, last_name, hourly_pay)`. This will ignore the hire date and will only insert the selected values
