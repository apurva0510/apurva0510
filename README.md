<h1 align="center">Hi, I'm Apurva Aggarwal</h1>

<p align="center">
  Computer Science + Business @ Michigan State • May 2027 • Data Products & Full-Stack Software
</p>

<p align="center">
  <a href="https://linkedin.com/in/apurva0510">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-apurva0510-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://apaggarwal.com">
    <img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-apaggarwal.com-2B6CB0?style=flat-square" />
  </a>
  <a href="mailto:appyaggarwal40@gmail.com">
    <img alt="Email" src="https://img.shields.io/badge/Email-appyaggarwal40@gmail.com-BB001B?style=flat-square&logo=gmail&logoColor=white" />
  </a>
</p>

---

## About Me

I'm a Computer Science major with a Business minor at Michigan State, graduating in May 2027. I build data products, full-stack platforms, and applied AI tools for real users.

My work spans a market research app used daily by my dad, a local Gemma research assistant, and deployed platforms for SpartaHack and MSU's International Students Association. I focus on data quality, server-enforced permissions, useful interfaces, and tests that check actual behavior.

Start with [Argus](https://github.com/apurva0510/argus) for data engineering, [Argus Friend Brief](https://github.com/apurva0510/argus-friend-brief) for applied AI, or [SpartaHack](https://spartahack.com) for full-stack work.

---

## Featured Projects

### [Argus](https://github.com/apurva0510/argus)

<p>
  <img alt="Argus CI status" src="https://img.shields.io/github/actions/workflow/status/apurva0510/argus/ci.yml?branch=main&label=CI&style=flat-square" />
  <img alt="Argus last commit" src="https://img.shields.io/github/last-commit/apurva0510/argus?style=flat-square" />
  <img alt="Argus top language" src="https://img.shields.io/github/languages/top/apurva0510/argus?style=flat-square" />
</p>

Market intelligence platform for researching AI, semiconductor, quantum, and data-center-linked companies.

- Tracks 53 companies across AI infrastructure themes
- Built with Python, Streamlit, PostgreSQL, SQLAlchemy, and GitHub Actions
- Uses a 33-table data model with scheduled pipelines for market data, SEC filings, earnings, news, and macroeconomic indicators
- Includes peer-relative valuation, bull/bear thesis tracking, thematic indices, watchlist alerts, and explainable opportunity scoring
- Backtests signals across 5D, 20D, and 60D forward returns and analyzes earnings and SEC-filing catalyst reactions
- Built for a daily family research workflow; behavioral tests and PostgreSQL-backed CI check the data and application paths

### [Argus Friend Brief](https://github.com/apurva0510/argus-friend-brief)

A research companion that turns Argus company data into plain-language, evidence-linked briefs using Gemma through Ollama.

- Runs inference locally over a sanitized research snapshot
- Validates citation IDs, attempts one repair, and rejects responses that still fail validation
- Real-model testing exposed citation failures missed by mocked tests, leading to a revised evidence format
- [Hosted preview](https://argus-friend-brief.streamlit.app/) shows saved, citation-validated examples; live generation runs locally

### [SpartaHack Platform](https://spartahack.com)

A Next.js, TypeScript, and Convex platform supporting multiple student-run events, built as SpartaHack Co-Director.

- Connects participant applications, event dashboards, teams, project submissions, check-in, judging, and organizer operations
- Enforces event isolation, department-scoped staff permissions, and workflow windows in the backend
- Uses durable communication jobs with retries and duplicate-safe recovery
- Translates operational requirements into staged implementation tasks and regression checks for authorization and event boundaries

### [MSU ISA Platform](https://msuisa.org)

A deployed Next.js, TypeScript, and Supabase platform built as ISA's Director of Technical Affairs.

- Brings public events, registration, affiliate attendance, funding requests, and staff administration into one system
- Implements server-enforced permissions, organization isolation, conflict-of-interest rules, and audit records
- Tests duplicate-safe workflows and automates releases and PostgreSQL migrations through CI/CD

### [Pykno](https://github.com/apurva0510/pykno)

<p>
  <img alt="Pykno CI status" src="https://img.shields.io/github/actions/workflow/status/apurva0510/pykno/ci.yml?branch=main&label=CI&style=flat-square" />
  <img alt="Pykno latest release" src="https://img.shields.io/github/v/release/apurva0510/pykno?style=flat-square" />
  <img alt="Pykno license" src="https://img.shields.io/github/license/apurva0510/pykno?style=flat-square" />
</p>

Local-first PDF compressor for reducing image-heavy files without redrawing their pages.

- Preserves text, vectors, links, forms, annotations, outlines, metadata, and page geometry
- Uses pikepdf/QPDF and Pillow to resize raster images based on their effective rendered DPI
- Handles shared images and images nested in Form XObjects, with a guarded macOS Quartz fallback
- Includes a configurable Finder Quick Action for right-click compression
- Tested on macOS and Linux across Python 3.11–3.13

### [FarmX](https://github.com/apurva0510/FarmX)

Applied ML tool for crop suitability and nutrient recommendations.

- Built Random Forest models using soil and weather inputs
- Deployed with Streamlit
- Won Best Sustainability Track at MHacks 2024
- [Hackathon submission](https://devpost.com/software/farmx-zpw0yq)

### [Micro Foods Market](https://github.com/apurva0510/MicroFoodMarket)

Dockerized backend marketplace built around service separation and authentication.

- Built 5 Flask microservices
- Implemented REST APIs, JWT authentication, SQLite persistence, and Docker Compose orchestration

---

## Currently Working On

- Maintaining SpartaHack's multi-event platform and preparing participant and organizer workflows for upcoming events
- Expanding ISA's event and affiliate operations at [msuisa.org](https://msuisa.org)
- Improving Argus research workflows, pipeline reliability, and behavioral verification
- Evaluating local-model outputs against their source evidence

---

## Tools I Use Most

### Languages

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white" />
</p>

### Data & ML

<p>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img alt="Ollama" src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" />
</p>

### Backend & Databases

<p>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img alt="REST APIs" src="https://img.shields.io/badge/REST_APIs-02569B?style=for-the-badge" />
  <img alt="Supabase" src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=black" />
  <img alt="Convex" src="https://img.shields.io/badge/Convex-EE342F?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" />
</p>

### Tools & Platforms

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/CI%2FCD-0A0A0A?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
</p>

### Analytics

<p>
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" />
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" />
</p>

---

## GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=apurva0510&show_icons=true&theme=github_dark&hide_border=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=apurva0510&layout=compact&theme=github_dark&hide_border=true" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=apurva0510&theme=github-dark-blue&hide_border=true" />
</p>

---

## Contact

I'm open to software engineering, data engineering, and AI engineering new-grad conversations.

- Portfolio: [apaggarwal.com](https://apaggarwal.com)
- LinkedIn: [linkedin.com/in/apurva0510](https://linkedin.com/in/apurva0510)
- Email: [appyaggarwal40@gmail.com](mailto:appyaggarwal40@gmail.com)
