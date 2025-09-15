


# SQL Project – Students & Grades

**Objective**  
Join two tables (`students` and `grades`) to display each student's name with their score.

**Query**
```sql
SELECT students.name, grades.score
FROM students
JOIN grades ON students.id = grades.student_id;


