# Database configuration

Set `MSSQL_SA_PASSWORD` in your process environment or local .env file before running `docker compose up`. Compose supplies the same value to SQL Server and the application. Existing database volumes retain their existing login password.

When starting the .NET application outside Compose, set `ConnectionStrings__DefaultConnection` in its process environment.
