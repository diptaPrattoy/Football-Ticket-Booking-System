# Football Ticket Booking System

This repository contains the PostgreSQL implementation of a Football Ticket Booking System. It includes database table creation, sample data insertion, and required SQL queries for the assignment.

## Project Contents

- `QUERY.sql` — PostgreSQL script containing table creation, constraints, sample data, and all required queries.
- `README.md` — Project documentation.
- `erd/` — ERD files or image export.
- `screenshots/` — Query output screenshots.

## Database Tables

The system uses three main tables:

- `users` — Stores football fans and ticket managers.
- `matches` — Stores football match details and ticket availability.
- `bookings` — Stores ticket booking records and links users with matches.

## ERD Link

```text
https://drive.google.com/file/d/11PeimoExvHaYoQBQacKPMYrAHPwFdqHr/view?usp=sharing
```

## How to Run

1. Open PostgreSQL or pgAdmin.
2. Create a new database.
3. Open `QUERY.sql`.
4. Run the full script.
5. Check the query outputs.

## SQL Concepts Used

- Primary Key and Foreign Key
- `CHECK` constraints
- `INSERT`
- `SELECT`
- `WHERE`
- `ILIKE`
- `COALESCE`
- `INNER JOIN`
- `LEFT JOIN`
- Subquery
- `ORDER BY`
- `LIMIT` and `OFFSET`
