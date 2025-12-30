# Student Records SQL Database

This project is a mini database system to manage student records using SQL.

## Files
- schema.sql → Table definitions
- sample_data.sql → Demo data
- queries.sql → Example queries

## Learning Outcomes
- Practiced SQL table creation, constraints, and joins
- Applied CRUD operations and reporting queries
## Example Outputs

### Students Table
| student_id | name  | age | course |
|------------|-------|-----|--------|
| 1          | Tanvi | 19  | BTech  |
| 2          | Ravi  | 20  | BTech  |

### Courses Table
| course_id | course_name     | credits |
|-----------|-----------------|---------|
| 101       | C Programming   | 4       |
| 102       | SQL Basics      | 3       |

### Query Result: Students with Courses
| name  | course_name   |
|-------|---------------|
| Tanvi | C Programming |
| Ravi  | SQL Basics    |