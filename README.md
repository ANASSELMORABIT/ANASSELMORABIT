<h1 align="center">Anass El Morabit</h1>
<p align="center">
  <b>.NET Developer</b> · C# · ASP.NET · SQL Server<br>
  Enterprise applications for the insurance sector · Barcelona, Spain
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/anass-el-morabit-98310929a"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  &nbsp;
  <a href="mailto:anasselmorabit797@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

---

## About me

.NET developer with over 2.5 years of experience building enterprise applications for the insurance sector.

- 🏢 **Junior .NET Developer at [Inkoova](https://www.inkoova.com)** (technology consultancy), assigned to a **Catalana Occidente (GCO Group)** project. I build new applications and evolve existing ones: complex workflows for order management and work invoicing, across domains such as insurance, repair workshops, lawyers and doctors.
- 🤝 I work directly with functional analysts and take part in requirements meetings, turning business needs into technical solutions.
- 🎓 Previously an **intern .NET / Backend developer at Catalana Occidente**, working on the claims management system with .NET Framework, SQL Server and ASP.NET Web Forms.
- 🌱 On my own time I build full-stack projects with **.NET 8/10, ASP.NET Core, React and TypeScript**, using Clean Architecture, JWT, real-time communication and automated testing.
- 📫 Open to new opportunities as a .NET / backend or full-stack developer.

## Tech stack

**Backend**

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Entity Framework](https://img.shields.io/badge/Entity%20Framework-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![SignalR](https://img.shields.io/badge/SignalR-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![REST](https://img.shields.io/badge/Web%20API%20%2F%20REST-000000?style=flat-square&logo=json&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Databases**

![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Testing, tools and workflow**

![xUnit](https://img.shields.io/badge/xUnit-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?style=flat-square&logo=visualstudio&logoColor=white)

**Also:** Python · jQuery · ASP.NET Web Forms · Hangfire · TFS · SSMS

## Featured projects

### [BookingApp](https://github.com/ANASSELMORABIT/BookingApp) — multi-tenant booking SaaS

Booking and appointment management platform where each business gets its own subdomain and fully isolated data.

- **Backend:** ASP.NET Core 10 REST API with Clean Architecture (Domain / Application / Infrastructure / API), EF Core and PostgreSQL 16.
- **Security:** JWT authentication with granular roles (SuperAdmin, Owner, Staff, Client) and tenant-based authorization.
- **Real time:** instant notifications through SignalR (WebSockets) and automatic email reminders with Hangfire background jobs.
- **Payments:** Stripe integration (test mode).
- **Features:** public booking page that needs no account, interactive calendar (day / week / month), dashboard with KPIs and charts, and Excel / PDF export with detailed statistics.
- **Frontend:** React 18, TypeScript, Vite, Tailwind CSS v4, shadcn/ui, TanStack Query, FullCalendar and Recharts.
- **DevOps and quality:** fully containerized with Docker Compose, xUnit unit tests, API documented with Scalar/OpenAPI.

`ASP.NET Core 10` `C#` `EF Core` `PostgreSQL` `SignalR` `Hangfire` `Stripe` `React` `TypeScript` `Docker`

### [InsureClaims](https://github.com/ANASSELMORABIT/insurance-claims-system) — full-stack claims management

Application that replicates an enterprise insurance management system.

- **Backend:** ASP.NET Core 8 Web API with Clean Architecture (Core / Infrastructure / API), EF Core 8 and SQL Server.
- **Security:** JWT authentication with refresh tokens and role-based authorization (Admin, Agent, Client).
- **Features:** full claim lifecycle (CRUD, status history, filters, pagination) and automatic agent assignment.
- **Frontend:** React 18, TypeScript and Vite, with dashboards, Excel/PDF export, email notifications and dark/light mode.
- **Quality:** xUnit, FluentAssertions and Moq on the backend; Vitest and Testing Library on the frontend; API documented with Swagger/OpenAPI.

`ASP.NET Core 8` `C#` `EF Core` `SQL Server` `React` `TypeScript` `JWT` `Docker`

### [Music Web Platform](https://github.com/ANASSELMORABIT/ProyectoFinalMP09MP03) — DAW final project

- MVC application in .NET with Entity Framework and SQLite.
- Integration of external APIs for search, recommendations and trending content.
- Playlist management and music player with AJAX requests; responsive interface.

## Experience

| Period | Role | Company |
|---|---|---|
| Jun 2025 – Present | Junior .NET Developer | Inkoova (consultancy), assigned to Catalana Occidente |
| Apr 2024 – Jun 2025 | Intern, .NET / Backend Developer | Catalana Occidente (GCO Group) |

## Education

- **Higher Vocational Diploma in Web Application Development (DAW)** — ETP Xavier, Barcelona (2023 – 2025)
- **Computer Engineering (partially completed)** — ENSA Tetouan, Morocco (2020 – 2022)

## Languages

Spanish (native) · Arabic (native) · English (advanced) · French (advanced) · Catalan (intermediate)

---

<p align="center">
  Looking for a .NET developer who understands the business side too? <a href="https://www.linkedin.com/in/anass-el-morabit-98310929a">Let's talk.</a>
</p>
