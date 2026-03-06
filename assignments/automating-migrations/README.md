# 📘 Assignment: Automating Migrations

## 🎯 Objective

Learn how to automate database migration steps with Python so schema updates are consistent, repeatable, and less error-prone.

## 📝 Tasks

### 🛠️ Parse and Track Migration Files

#### Description
Create a Python script that reads migration files from a folder and determines which migrations still need to run.

#### Requirements
Completed program should:

- Read migration filenames from a `migrations/` directory (for example: `001_create_users.sql`, `002_add_email.sql`).
- Sort migration files in execution order.
- Read a local state file (for example: `applied_migrations.txt`) to determine which migrations were already applied.
- Print a clear list of pending migrations.

### 🛠️ Apply Pending Migrations Safely

#### Description
Extend your script so it applies pending migrations and records progress.

#### Requirements
Completed program should:

- Simulate applying each pending migration in order.
- Log success or failure for each migration.
- Update the applied-migrations state file after each successful migration.
- Stop processing if a migration fails and report what remains.
- Display a final summary showing how many migrations succeeded and how many are still pending.
