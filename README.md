# CSIWB — Cardiological Society of India (West Bengal) – Membership Management

> **Domain:** Membership & Professional Society Management  
> **Author:** Sagarika Chakraborty — *Full Stack .NET Engineer | React.js | Web API | SQL Server*

A web-based **membership management** system for **CSIWB** to handle **Associate Life Member** registration, **active vs expired** status tracking, **newsletter distribution**, and **reporting**. Built with **ASP.NET MVC 5 / .NET Core 3**, **Entity Framework**, **LINQ**, **SQL Server**, **jQuery**, and **RDLC** reporting. Versioning and deployments were managed via **TFS**.

---

## ✨ Key Features
- **Membership Registration**: capture full associate life member details; validation & audit.
- **Status Management**: active/expired lifecycle with rules (renewal, grace, verification).
- **Newsletters**: distribution lists, subscription flags, delivery logs.
- **Reporting**: RDLC exports to **Word/PDF/Excel** (membership rosters, expiries, engagement).
- **Admin Console**: manage members, chapters, roles, newsletters, and exports.

---

## 🧱 Technology Stack
- **Framework**: ASP.NET MVC 5 / .NET Core 3 (server-rendered)
- **Data**: SQL Server + Entity Framework, LINQ
- **Frontend**: Razor Views, jQuery, AJAX, Bootstrap
- **Reporting**: RDLC (Word/PDF/Excel)
- **DevOps**: TFS (version control, CI/CD, production support)

---

## 📁 Repository Structure
```
.
├─ README.md
└─ docs
   ├─ HLD.md
   ├─ LLD.md
   └─ architecture.png
```

---

## 🚀 Quick Start (Dev)
Update `appsettings.json` / `Web.config`:
```json
{
  "ConnectionStrings": {
    "SqlServer": "Server=.;Database=CSIWB;Trusted_Connection=True;TrustServerCertificate=True"
  }
}
```
Run the MVC app from Visual Studio or `dotnet run` (if targeting .NET Core).

---

## 🧭 Documentation
- **HLD**: [`/docs/HLD.md`](docs/HLD.md)
- **LLD**: [`/docs/LLD.md`](docs/LLD.md)
- **Diagram**: [`/docs/architecture.png`](docs/architecture.png)

---

## 👩‍💻 Credits
**Sagarika Chakraborty** — Registration & lifecycle flows, newsletter module, EF/SQL schema, RDLC reports, and TFS CI/CD & production support.
