# Secure Document Management System (SDMS)

This folder contains a coursework-ready implementation skeleton for the SDMS actions:

- Register
- Login
- Logout
- Upload a document
- Download a document
- Search/view documents
- Reserve a document
- Release a reservation

All actions are routed through `SecurityProxy` before reaching the service layer.

## Folder Structure

```text
sdms_github_folder/
├── README.md
├── src/
│   └── sdms_app.py
└── database/
    └── sdms_database.sql
```

## How to Run the Python Demo

```bash
cd src
python sdms_app.py
```

## How to Run the SQL Script

Open `database/sdms_database.sql` in SQLite DB Browser, SQLiteStudio, or run:

```bash
sqlite3 sdms.db < sdms_database.sql
