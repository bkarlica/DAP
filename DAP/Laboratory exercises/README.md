# Laboratory Exercises

Four laboratory sessions for the Database Application Programming course at Poznan University of Technology. Each report (PDF) contains the code and the outputs.

## Lab 1: Basic operations on a database
Creating the `Students`, `Courses` and `Grades` tables with primary and foreign keys, inserting data, filtering and joining data (`ORDER BY`, `JOIN`), and modifying data with subqueries (deleting the grades of the course with the lowest average, lowering the grades of the course with the highest average).

## Lab 2: PL/SQL part 1
PL/SQL fundamentals: quoted and unquoted identifiers (case sensitivity, reserved words), variables declared with `%TYPE`, and control statements: even/odd check, weekday of a hire date, listing employees with manager names (self-join), employees per department, and comparing a salary with the department average.

## Lab 3: PL/SQL part 2
Calculating employment periods (also using the `job_history` table), counting affected rows with `SQL%ROWCOUNT` and `ROLLBACK` handling in the exception block, and counting direct and indirect subordinates of each manager with a hierarchical query (`CONNECT BY`).

## Lab 4: Triggers
A "smart autoincrement" trigger for a table without an auto-increment column: if the ID is provided, the row is inserted unchanged (or rejected if the ID already exists), and if the ID is `NULL`, the trigger assigns the first free ID, filling gaps in the sequence.

## Files

* `DAP_LAB_1_Budimir.pdf` ... `DAP_LAB_4_Budimir.pdf`

**Technologies:** Oracle Database, SQL, PL/SQL, Oracle SQL Developer
