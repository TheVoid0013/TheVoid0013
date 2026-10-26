# Samyam Subedi

**.NET Developer** · Kathmandu, Nepal

I build secure, maintainable backend systems for financial and compliance software, mainly with C#, ASP.NET Core, and SQL Server. I have 2+ years of professional experience on enterprise fintech products, including multi-tenant platforms, third-party integrations, and high-volume data workloads.

> Most of my professional work is proprietary and lives in private repositories. This profile highlights personal projects and the tools and practices I work with.

---

## What I Work On

- **Backend architecture:** Clean Architecture, Repository and Unit-of-Work patterns, and CQRS-style request handling with MediatR
- **Multi-tenant systems:** tenant data isolation, hierarchical access control, and role-based authorization
- **APIs:** versioned, idempotent REST APIs documented with Swagger/OpenAPI
- **Security:** JWT, ASP.NET Identity, RBAC, and encryption of sensitive data
- **Databases:** SQL Server performance tuning, indexing strategy, stored procedures, bulk operations, and full-text search
- **Data pipelines:** ingestion, parsing, and batched upserts of large datasets

---

## Featured Project

### [DataImport](https://github.com/TheVoid0013/DataImport): OFAC SDN Sanctions Platform

A .NET solution that ingests U.S. Treasury OFAC sanctions data and serves it through a REST API.

- Console ETL job with a MediatR pipeline (download, parse, save) that records every run in an audit log
- Streams large XML files and uses day-partitioned caching to avoid redundant downloads
- Batched upserts with EF Core (`AsNoTracking`, periodic `ChangeTracker.Clear()`) to keep memory and change-tracking cost flat
- ASP.NET Core Web API with paged endpoints and Swagger documentation
- BenchmarkDotNet project comparing parsing and save strategies

**Stack:** C#, .NET, EF Core, SQL Server, MediatR, Serilog, BenchmarkDotNet

---

## Tech Stack

| Area | Technologies |
| --- | --- |
| **Backend** | C#, .NET 8+, ASP.NET Core, ASP.NET MVC, Entity Framework Core, MediatR |
| **Frontend** | React, TypeScript, JavaScript, jQuery/AJAX, HTML/CSS, Bootstrap, Tailwind CSS |
| **Databases** | SQL Server, MySQL |
| **Security** | JWT, OAuth, SSO, ASP.NET Identity, RBAC, AES/RSA |
| **Tools and Practices** | Git, GitLab, Docker, Azure, CI/CD, xUnit, Moq, Postman, Swagger/OpenAPI, Jira, Agile/Scrum |

---

## Currently Learning

- Advanced Docker workflows
- Redis caching and distributed systems
- Cloud architecture on Azure
- Building scalable financial systems

---

## Get in Touch

- Portfolio: [samyamsubedi.netlify.app](https://samyamsubedi.netlify.app)
- LinkedIn: [linkedin.com/in/samyamsubedi](https://www.linkedin.com/in/samyamsubedi/)
- Email: [samyam081@gmail.com](mailto:samyam081@gmail.com)
