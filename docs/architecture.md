# Architecture

The application is an ASP.NET Core 8 Razor Pages CMS/blog showcase.

- Razor Pages provide public and admin user interfaces.
- Entity Framework Core targets SQL Server through `AppDbContext` and migrations.
- Repository abstractions encapsulate blog-post persistence.
- Blog posts support content, tags, visibility, SEO-friendly URLs, and featured images.
- Docker Compose supports a local app plus database workflow.

The repository demonstrates a custom CMS foundation. Migration to a packaged CMS such as Orchard Core remains a strategic option, not an approved implementation change.
