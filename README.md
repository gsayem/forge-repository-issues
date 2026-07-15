# Forge.Repository - Feedback & Issue Tracker

Welcome to the central issue, feature request, and architectural discussion tracker for the **Forge.Repository** ecosystem. 

`Forge.Repository` is a robust, database-agnostic repository pattern and unit of work implementation built natively for **.NET 10** and **Entity Framework Core**. It provides an enterprise-scale data access layer abstraction supporting SQL Server, PostgreSQL, MySQL, and Oracle.

---

## 🚀 Project Status & Roadmap

* **Packages:** Fully published, stable, and ready for production workloads on NuGet.
* **Source Code:** Currently closed-source. However, **the codebase is actively being prepared to be fully open-sourced in the near future**.
* **This Repository:** This specific repository serves as a public-facing hub for community collaboration, bug reports, and telemetry feedback while the core implementation remains private.

---

## 🌐 Quick Links

Before submitting an issue, you can explore the ecosystem through these resources:

* **Official Website:** [sayem.xyz/packages/forge-repository](https://www.sayem.xyz/packages/forge-repository)
* **Comprehensive Documentation:** [doc.sayem.xyz/forge-docs](https://doc.sayem.xyz/forge-docs)
* **NuGet Core Package:** `dotnet add package Forge.Repository`

---

## 🛠️ Ecosystem Packages

Forge utilizes optimized, database-specific provider packages. If you encounter a bug, please note if it is limited to a specific provider:

| Database | NuGet Package |
| :--- | :--- |
| **SQL Server** | `Forge.Repository.SqlServer` | 
| **PostgreSQL** | `Forge.Repository.PostgreSql` |
| **MySQL / MariaDB** | `Forge.Repository.MySql` |
| **Oracle** | `Forge.Repository.Oracle` |

---

## 🤝 How to Contribute Feedback

We highly value engineering feedback, edge-case bug reporting, and feature proposals to help shape the public open-source release.

### 1. Bug Reports
If you encounter unexpected behavior, transient connection failures, or framework conflicts:
* Check the existing issues to ensure it hasn't been reported.
* Use our **Bug Report Template** when opening a new issue.
* Provide minimal code snippets of your `DbContext` setup or repository query execution where possible.

### 2. Feature Requests & Ideas
Want support for a specific EF Core 10 feature, or an enhancement to the connection pooling tuners?
* Use our **Feature Request Template** to outline your proposal.
* Explain the use case and how it benefits enterprise architectures (e.g., DDD, Onion Architecture).

### 3. Architectural Discussions
For general questions about setting up criteria-based queries (`ICriteriaAsync<TEntity>`), handling complex transactional states, or performance tuning, feel free to open a standard GitHub issue marked as a **Discussion**.

---

## 🔒 Security Vulnerabilities

If you discover a critical security vulnerability, please do **not** open a public issue. Instead, reach out directly via the contact options listed on [sayem.xyz/contact](https://www.sayem.xyz/contact) so we can patch the NuGet packages immediately.

---

Thank you for helping build a more robust, performance-tuned data layer infrastructure for the .NET community!
