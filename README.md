<h1 align="center">Derek Singleton</h1>

<p align="center">
  <b>Full-stack engineer · C# / .NET · Python · React · SQL Server</b><br/>
  I build the internal software a business runs its week on, and the clean data underneath it that AI needs before it can do anything useful.
</p>

<p align="center">
  <a href="https://devhorizon.io"><img src="https://img.shields.io/badge/portfolio-devhorizon.io-0ea5e9?style=flat-square" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/derek-singleton-a29726129/"><img src="https://img.shields.io/badge/LinkedIn-Derek%20Singleton-0a66c2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:ds301056@gmail.com"><img src="https://img.shields.io/badge/email-ds301056%40gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## What I'm doing now

I'm the main developer of the internal software platform at a **50-person engineering firm** (Jan 2025 – present). I handle the architecture, the builds, and the deployments. The platform started as a fragile set of tools with broken authentication and a legacy Access database that had no referential integrity. It's now **5+ production apps used every day by 30+ people**.

- **Document-delivery desktop app.** I rebuilt a WinForms v1 as a WPF / .NET 9 app on Clean Architecture and EF Core. It talks to the firm's ERP in two ways: the API for keys and ODBC for detail. That pulls about 600 projects in about 2 seconds. It has 970 tests, an installer that bundles the runtime, a channel-based auto-updater, and a forced v1 → v2 migration.
- **Workforce-capacity forecasting.** A Python / FastAPI and Next.js service that combines ERP billing data with CRM pipeline data. It runs three forecast models against real staff capacity and feeds a 12-month KPI dashboard. It takes about 90% less effort than the Excel process it replaced.
- **Revit add-in suite (Revit 2023–2026).** A model-to-database integrity engine that finds and repairs broken data links, transactional parent/child sync with rollback and retry, and two-way document tracking between the model and SQL Server.
- **Firm-wide file browser.** Searches 7,113 projects in under a second, and each user sees only what their role allows. It replaced digging through network drives by hand.
- **Standards written for AI.** About 15 development-standards documents written so a model can read and follow them. Also a Model Context Protocol server stack and Claude Code subagents that enforce the standards as code gets written. 35+ zero-downtime releases.

The firm's own ROI accounting credits the tools I built with **~804 hours (~$130K)** across 2025 and the first half of 2026. That accounting is based on estimated time saved per use; nobody timed it with a stopwatch.

**Before that:** Balluff, Software Engineer (Aug 2023 – Dec 2024). I built Node.js and Python pipelines that polled 120+ industrial sensors across 12 systems over REST, TCP/IP, UDP, and EtherNet/IP, and fed real-time React diagnostics dashboards for PLC and sensor health.

---

## Projects you can open

| Project | What it is | Stack |
|---|---|---|
| **[NRAP](https://github.com/ds301056/NRAP)** | Neural Response Analytics Platform. Upload audio, video, or text, and it predicts brain activation with Meta's TRIBEv2 model, then shows the result on a 3D particle brain that lights up in real time. Inference runs on an on-demand Modal A10G GPU that costs about $0.02 per clip and nothing when idle. Three inference backends can be swapped without the frontend noticing. | Python · FastAPI · PostgreSQL · Redis · React · Modal |
| **[jarvis](https://github.com/ds301056/jarvis)** | A local voice assistant that runs the whole agent loop. Wake word → Whisper speech-to-text → a local (Ollama) or cloud LLM → tool calls that act on the machine → streaming text-to-speech. The first audio plays in under a second, you can interrupt it mid-sentence, and the whole thing fits in 16 GB of RAM. | Python · Whisper · Ollama · multi-LLM |
| **[House](https://github.com/ds301056/House)** | A Cincinnati house-search tool that checks each listing's asking price against 295k county sales and nearby comps. Uses only the Python standard library, with no paid data and no API key. | Python · SQLite |
| **[FitSafe](https://github.com/ds301056/FitSafe)** | A self-hosted home-gym tracker for a shared iPad, running on a Raspberry Pi. It has profiles, guided workouts, and a 68-exercise library. | Node.js · TypeScript · Raspberry Pi |
| **[devOverflow](https://github.com/ds301056/devOverflow)** | A Stack Overflow-style Q&A platform with auth, tags, and AI-drafted answers. [Live demo →](https://dev-overflow-topaz-kappa.vercel.app) | Next.js · MongoDB · OAuth |
| **[OpenForge](https://github.com/ds301056/OpenForge)** | *Work in progress.* A planning tool that turns vague goals into plans you can edit, tracks progress, and suggests improvements. | Next.js · Supabase · Vitest |

Most of my professional work lives in private repositories. The write-ups, diagrams, and demos are at **[devhorizon.io](https://devhorizon.io)**.

---

## Tools I use day to day

| | |
|---|---|
| **Languages** | C#, Python, TypeScript, JavaScript, SQL |
| **Backend** | .NET / ASP.NET Core, WPF, Entity Framework Core, FastAPI, Node.js, REST, OAuth2 / Entra ID SSO |
| **Frontend** | React, Next.js, Tailwind CSS |
| **Data** | SQL Server, PostgreSQL, MongoDB, Redis, Pandas, Power BI |
| **Testing & DevOps** | xUnit, pytest, Playwright, Git, GitHub Actions, Docker |
| **AI** | Claude Code, MCP servers, agentic tool-calling, Whisper, Ollama |
| **Domain** | Revit API, ERP/CRM integration (ODBC + REST), industrial protocols (EtherNet/IP, TCP/UDP) |

---

## Credentials

- **B.S., Data Analysis & Software Development**, University of Cincinnati (expected Spring 2027)
- **Associate degree, Software Development & Database Management**, Cincinnati State (2024)
- AWS Certified Cloud Practitioner (Dec 2024) · AWS Certified AI Practitioner · Next.js, JavaScript Mastery (Aug 2024)
- *In progress:* Azure AI Engineer (AI-102) · IBM AI Engineering

<p align="center"><sub>Open to full-stack and applied-AI engineering roles. The fastest way to reach me is <a href="mailto:ds301056@gmail.com">email</a>.</sub></p>
