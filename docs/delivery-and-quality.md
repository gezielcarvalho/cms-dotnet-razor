# Delivery and quality

## Local workflows

- Use `dotnet restore`, `dotnet ef database update`, and `dotnet run` for local development.
- Use Docker Compose and the provided scripts for the documented container workflow.
- Run focused .NET tests and build checks when application code changes.

Documentation-only changes require whitespace validation and reviewer inspection. Do not embed production connection strings, CAPTCHA keys, or other secrets in repository documentation.
