# Composite Index Investigation

## Objective

The goal of this investigation was to understand how composite index column ordering affects PostgreSQL query performance.

---

## Query Tested

```sql
SELECT *
FROM employees
WHERE department = 'Sales '
AND salary > 50000;