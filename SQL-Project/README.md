


# SQL Project – Students & Grades

**Objective**  
Join two tables (`students` and `grades`) to display each student's name with their score.

## Query
```sql
SELECT students.name, grades.score
FROM students
JOIN grades ON students.id = grades.student_id;
```

## Result  
| name   | score |
|--------|-------|
| Ahmed  | 98    |
| Mohamed| 80    |
| Mazen  | 95    |
| Saleh  | 96    |

## Download
[📂 Download SQL File](./students_grades_query.sql)

**Tools Used**  
- PostgreSQL  
- pgAdmin 4



