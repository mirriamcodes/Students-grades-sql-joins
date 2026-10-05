# Students & Grades - Joining Related Tables

Learning SQL normalization & JOINs from Khan Academy.

This repo demonstrates how to split data into related tables and join them back.

## Tables
- **students**: id, first_name, last_name, email, phone, birthdate
- **student_grades**: id, student_id, test, grade

## Concepts Covered
- Primary Key / Foreign Key
- Cross Join vs Inner Join
- Implicit vs Explicit JOIN syntax
- LEFT OUTER JOIN
- Filtering with WHERE grade > 90

## How to Run
Open in https://sqliteonline.com/ or any SQLite editor and run `schema.sql` then `queries.sql`
