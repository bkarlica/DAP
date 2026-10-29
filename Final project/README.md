# Final Project: University Database

Final project for the Database Application Programming course at Poznan University of Technology. The goal was to design and populate a relational database for a university and analyse it with SQL queries.

## Database design

The database consists of eight tables:

* `subject_types` – types of classes (Lecture, Exercise, Laboratory)
* `subjects` – university subjects
* `subject_subject_types` – links subjects to their types (many-to-many, since one subject can have several types)
* `students` and `teachers`
* `teacher_salary` – salary and employment type of each teacher
* `teacher_subjects` – links teachers to subjects (many-to-many)
* `grades` – students' grades per subject and subject type

The report contains the ER diagrams, the full `CREATE TABLE` script and the `INSERT` statements.

## Data

3 subject types, 6 subjects, 15 students, 4 teachers and 60 grades.

## Queries

1. Display all data from each table
2. Average grade for each subject
3. Average grade for each student
4. Average grade for one type of subject (e.g. English, Exercise) for each student

## Files

* `Database_Application_Programming_Final_Project_Budimir.pdf` – full report with code, diagrams and query outputs

**Technologies:** Oracle Database, SQL, Oracle SQL Developer
