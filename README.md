# intro-to-sql-lab-starter-code

A SQL lab starter repo (Carmen Sandiego mystery) for practicing querying a relational dataset.

## ✨ Technologies

- **SQL**
- A relational database (commonly PostgreSQL)
- Provided dataset files:
  - `world.sql`
  - `clues.sql`

## 🚀 Features

- Step-by-step mystery prompts (clues) to guide query writing
- Practice:
  - `SELECT`, `WHERE`, `ORDER BY`, `LIMIT`
  - `JOIN`
  - filtering + matching (`ILIKE`)

## 🛠️ The Process

1. Load the provided dataset (`world.sql`) into your database.
2. Open `clues.sql` and write queries under each clue.
3. Execute queries to reveal the next destination / answer.

## ▶️ Running the Project

### Example (PostgreSQL)

1. Create a database:

```bash
createdb world
```

2. Load the dataset:

```bash
psql -d world -f world.sql
```

3. Run your clue queries:

```bash
psql -d world -f clues.sql
```
