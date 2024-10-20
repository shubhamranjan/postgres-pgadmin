# Postgres (timescaledb) + PgAdmin

This repo will help with the following:

- Run postgres with timescaledb extension installed
- Run pgAdmin 4 with postgres already configured

This will come in handy for local development or for exploring timescaledb

## Getting Started

- Clone the repo
- Run the following command:

```bash
  docker compose up -d
```

- Visit `http://localhost:5050/` to browse the pgAdmin UI for querying postgres
  - Use the followign credentials:
    - Username:  `admin@example.com`
    - Password: `admin`
  
- For connecting to postgres from CLI or code, use the following connection string:

```txt
  postgresql://postgres:postgres@localhost:5432/<db_name>
```

where `db_name` should be replaced with the database you wish to connect to. A database with name `postgres` is already created on initialisation.
