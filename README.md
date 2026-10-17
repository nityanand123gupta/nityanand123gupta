<p align="center">
  <img src="./profile/banner.svg?v=2" alt="Nityanand Gupta — Machine Learning · Agentic AI · Full-Stack · B.Tech Computer Science, IIIT Hyderabad" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/IIIT_Hyderabad-0D1117?style=for-the-badge&logo=googlescholar&logoColor=58A6FF&labelColor=0D1117" alt="IIIT Hyderabad" />
  <img src="https://img.shields.io/badge/Machine_Learning-0D1117?style=for-the-badge&logo=pytorch&logoColor=58A6FF&labelColor=0D1117" alt="Machine Learning" />
  <img src="https://img.shields.io/badge/Agentic_AI-0D1117?style=for-the-badge&logo=openaigym&logoColor=58A6FF&labelColor=0D1117" alt="Agentic AI" />
  <img src="https://img.shields.io/badge/Full_Stack-0D1117?style=for-the-badge&logo=nextdotjs&logoColor=58A6FF&labelColor=0D1117" alt="Full Stack" />
  <img src="https://img.shields.io/badge/Systems-0D1117?style=for-the-badge&logo=linux&logoColor=58A6FF&labelColor=0D1117" alt="Systems" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Upstream_merged_PRs-4-58A6FF?style=flat-square&labelColor=0D1117" alt="Upstream merged PRs" />
  <img src="https://img.shields.io/badge/Upstream_stars_reached-28k%2B-58A6FF?style=flat-square&labelColor=0D1117" alt="Upstream stars reached" />
  <img src="https://img.shields.io/badge/Hyderabad-IN-58A6FF?style=flat-square&labelColor=0D1117" alt="Hyderabad, India" />
</p>

---

## <img src="./profile/icons/profile.svg" height="23" /> Profile

Computer Science at **IIIT Hyderabad**, working across **machine learning**, **agentic AI**,
**full-stack** and **systems**. I like building the whole thing — model pipeline, database
schema, operator interface and deploy — rather than one slice of it.

Most of my work falls into three areas. **Agentic AI and applied ML**: multi-step LLM
pipelines that plan their own analysis and write the code to run it, retrieval systems over
real document corpora, and agent crews that reason against hard rule engines. **Full-stack
products**: TypeScript and Postgres on Next.js 16, built end to end and shipped.
**Detection and monitoring systems**: deep-learning detectors with multi-object tracking,
motion-pattern verification and image preprocessing for degraded conditions, packaged to run
fully offline.

Alongside that I ship fixes upstream into widely-used open-source infrastructure.

---

## <img src="./profile/icons/merge.svg" height="23" /> Merged upstream contributions

Fixes and features merged into open-source projects used in production worldwide —
**28,000+ combined stars**.

| Project | Stars | What I shipped |
|---|---:|---|
| **[django-oauth/django-oauth-toolkit](https://github.com/django-oauth/django-oauth-toolkit)** <br/><sub>OAuth2 provider for Django</sub> | 3.3k | Brought authorization **error** redirects into **RFC 9207** compliance by emitting the `iss` issuer identifier on the failure path, not just on success — so clients in multi-provider deployments can attribute which server rejected them. <sub>[#1847](https://github.com/django-oauth/django-oauth-toolkit/pull/1847)</sub> |
| **[evilmartians/lefthook](https://github.com/evilmartians/lefthook)** <br/><sub>Git hooks manager</sub> | 8.9k | Made `lefthook run` **fail loudly** when `--job` or `--command` matches nothing, replacing a silent no-op that let mistyped filters pass as a green run. <sub>[#1512](https://github.com/evilmartians/lefthook/pull/1512)</sub> |
| **[faker-js/faker](https://github.com/faker-js/faker)** <br/><sub>Fake-data generation for JS/TS</sub> | 15.5k | Closed an **API contract gap** in `weightedArrayElement` — documented the error it throws, so consumers handle the failure path instead of discovering it at runtime. <sub>[#4016](https://github.com/faker-js/faker/pull/4016)</sub> |

---

## <img src="./profile/icons/layers.svg" height="23" /> Selected work

### <img src="./profile/icons/neural.svg" height="20" /> Applied AI & agent systems

| System | Detail |
|---|---|
| **Multi-agent analytics pipeline** <br/>`proprietary` | Eight-stage LLM pipeline over enterprise spreadsheets: ingests workbooks, infers schema and cross-dataset relationships, proposes candidate analyses, plans an execution strategy, then **generates and runs the Python analysis code** — a full question-to-result loop with no analyst in the middle. |
| **Financial RAG system** <br/>`proprietary` | Retrieval-augmented analysis over financial reports. PDF extraction and chunking with metadata preserved, **FAISS** semantic search over sentence-transformer embeddings, and a router that reaches for external industry benchmarks only when the local corpus can't answer. Every claim cites its source down to the PDF page. |
| **AI Sports Trade Analyzer** <br/>`public` | Multi-agent NBA trade analyzer — a Scout / Quant / Cap / GM agent crew reasoning over a player-valuation model and a **CBA salary-cap rules engine** to produce a graded recommendation. CrewAI + Gemini/Claude, with a full architecture write-up in `DESIGN.pdf`. |

### <img src="./profile/icons/cube.svg" height="20" /> Product engineering

| System | Detail |
|---|---|
| **StudyMint** `private` | Study-support platform for university students — Next.js 16, Drizzle ORM, Clerk auth, Postgres. Built end to end from schema to deploy. |
| **Buddyly** <br/>`live · buddyly.ai` | TypeScript product platform with **DigiLocker** identity verification. Shipped venue search, consent-flow and DigiLocker redirect fixes across a full QA cycle, and removed the row cap on bulk data export. |
| **Relationship OS** `private` | TypeScript + PLpgSQL CRM. Delivered a UI, performance and reliability overhaul with Daily Lineup, an AI-budget fix, test fixtures and CI. |

### <img src="./profile/icons/radar.svg" height="20" /> Detection & monitoring systems

| System | Detail |
|---|---|
| **Zone Intelligence** <br/>`proprietary` | Fuses a camera fleet into **one air picture**. A single camera can only report a bearing — Zone Intelligence resolves the object seen by multiple cameras into a single track with position, heading and speed, then grades that track against the site's surveyed perimeter. |
| **AirGuard** · **SkyShield** <br/>`proprietary` | Camera-only drone-vs-bird detection for border and perimeter sites — **no radar, RF or acoustic sensors**. Pretrained UAV detection models with multi-object tracking, flight-pattern confirmation that vetoes the classic bird false-alarms, and CLAHE preprocessing for fog, haze and snow-glare. Operator dashboard, shipped as packaged Windows installers that run **fully offline**. |
| **SiteGuard** <br/>`proprietary` | Ground-side site monitoring over ONVIF/RTSP camera fleets — detection and tracking of people, vehicles and animals, directional line-crossing counts, zone dwell and loitering alerts, and a camera wall that scales to the full fleet. **FastAPI + React.** |

---

## <img src="./profile/icons/stack.svg" height="23" /> Engineering stack

**Core areas**

![Machine Learning](https://img.shields.io/badge/Machine_Learning-0D1117?style=for-the-badge&logo=pytorch&logoColor=58A6FF&labelColor=0D1117)
![Agentic AI](https://img.shields.io/badge/Agentic_AI-0D1117?style=for-the-badge&logo=langchain&logoColor=58A6FF&labelColor=0D1117)
![Statistical Methods in AI](https://img.shields.io/badge/Statistical_Methods_in_AI-0D1117?style=for-the-badge&logo=scipy&logoColor=58A6FF&labelColor=0D1117)
![Operating Systems](https://img.shields.io/badge/Operating_Systems-0D1117?style=for-the-badge&logo=linux&logoColor=58A6FF&labelColor=0D1117)
![Networks](https://img.shields.io/badge/Networks-0D1117?style=for-the-badge&logo=cisco&logoColor=58A6FF&labelColor=0D1117)

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-0D1117?style=for-the-badge&logo=typescript&logoColor=58A6FF&labelColor=0D1117)
![Python](https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=58A6FF&labelColor=0D1117)
![JavaScript](https://img.shields.io/badge/JavaScript-0D1117?style=for-the-badge&logo=javascript&logoColor=58A6FF&labelColor=0D1117)
![C++](https://img.shields.io/badge/C++-0D1117?style=for-the-badge&logo=cplusplus&logoColor=58A6FF&labelColor=0D1117)
![SQL](https://img.shields.io/badge/SQL-0D1117?style=for-the-badge&logo=postgresql&logoColor=58A6FF&labelColor=0D1117)
![Go](https://img.shields.io/badge/Go-0D1117?style=for-the-badge&logo=go&logoColor=58A6FF&labelColor=0D1117)

**Machine learning & AI**

![PyTorch](https://img.shields.io/badge/PyTorch-0D1117?style=for-the-badge&logo=pytorch&logoColor=58A6FF&labelColor=0D1117)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0D1117?style=for-the-badge&logo=scikitlearn&logoColor=58A6FF&labelColor=0D1117)
![pandas](https://img.shields.io/badge/pandas-0D1117?style=for-the-badge&logo=pandas&logoColor=58A6FF&labelColor=0D1117)
![NumPy](https://img.shields.io/badge/NumPy-0D1117?style=for-the-badge&logo=numpy&logoColor=58A6FF&labelColor=0D1117)
![FAISS](https://img.shields.io/badge/FAISS-0D1117?style=for-the-badge&logo=meta&logoColor=58A6FF&labelColor=0D1117)
![CrewAI](https://img.shields.io/badge/CrewAI-0D1117?style=for-the-badge&logo=robotframework&logoColor=58A6FF&labelColor=0D1117)
![OpenCV](https://img.shields.io/badge/OpenCV-0D1117?style=for-the-badge&logo=opencv&logoColor=58A6FF&labelColor=0D1117)
![Jupyter](https://img.shields.io/badge/Jupyter-0D1117?style=for-the-badge&logo=jupyter&logoColor=58A6FF&labelColor=0D1117)

**Backend & data**

![FastAPI](https://img.shields.io/badge/FastAPI-0D1117?style=for-the-badge&logo=fastapi&logoColor=58A6FF&labelColor=0D1117)
![Node.js](https://img.shields.io/badge/Node.js-0D1117?style=for-the-badge&logo=nodedotjs&logoColor=58A6FF&labelColor=0D1117)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0D1117?style=for-the-badge&logo=postgresql&logoColor=58A6FF&labelColor=0D1117)
![Drizzle](https://img.shields.io/badge/Drizzle-0D1117?style=for-the-badge&logo=drizzle&logoColor=58A6FF&labelColor=0D1117)
![Clerk](https://img.shields.io/badge/Clerk-0D1117?style=for-the-badge&logo=clerk&logoColor=58A6FF&labelColor=0D1117)

**Frontend**

![React](https://img.shields.io/badge/React-0D1117?style=for-the-badge&logo=react&logoColor=58A6FF&labelColor=0D1117)
![Next.js](https://img.shields.io/badge/Next.js-0D1117?style=for-the-badge&logo=nextdotjs&logoColor=58A6FF&labelColor=0D1117)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-0D1117?style=for-the-badge&logo=tailwindcss&logoColor=58A6FF&labelColor=0D1117)
![Vite](https://img.shields.io/badge/Vite-0D1117?style=for-the-badge&logo=vite&logoColor=58A6FF&labelColor=0D1117)

**Infrastructure & tooling**

![Git](https://img.shields.io/badge/Git-0D1117?style=for-the-badge&logo=git&logoColor=58A6FF&labelColor=0D1117)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0D1117?style=for-the-badge&logo=githubactions&logoColor=58A6FF&labelColor=0D1117)
![Docker](https://img.shields.io/badge/Docker-0D1117?style=for-the-badge&logo=docker&logoColor=58A6FF&labelColor=0D1117)
![Vercel](https://img.shields.io/badge/Vercel-0D1117?style=for-the-badge&logo=vercel&logoColor=58A6FF&labelColor=0D1117)
![Linux](https://img.shields.io/badge/Linux-0D1117?style=for-the-badge&logo=linux&logoColor=58A6FF&labelColor=0D1117)

---

## <img src="./profile/icons/chart.svg" height="23" /> Engineering activity

<p align="center">
  <img src="./profile/stats.svg" alt="GitHub stats" width="49%" />
  <img src="./profile/top-langs.svg" alt="Most used languages" width="40%" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=nityanand123gupta&theme=tokyonight&hide_border=true" alt="Contribution streak" width="60%" />
</p>

---

## <img src="./profile/icons/pin.svg" height="23" /> Featured repositories

<p align="center">
  <a href="https://github.com/nityanand123gupta/sky-watch-drone-zones"><img src="./profile/pin-sky-watch-drone-zones.svg" alt="sky-watch-drone-zones — detection system" width="49%" /></a>
  <a href="https://github.com/nityanand123gupta/ai-sports-trade-analyzer"><img src="./profile/pin-ai-sports-trade-analyzer.svg" alt="ai-sports-trade-analyzer — multi-agent AI" width="49%" /></a>
</p>
<p align="center">
  <a href="https://github.com/nityanand123gupta/felicity-event-management"><img src="./profile/pin-felicity-event-management.svg" alt="felicity-event-management — full-stack platform" width="49%" /></a>
</p>

---

## <img src="./profile/icons/grid.svg" height="23" /> Contribution graph

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nityanand123gupta/nityanand123gupta/output/github-contribution-grid-snake-dark.svg" />
  <img alt="Contribution graph animation" src="https://raw.githubusercontent.com/nityanand123gupta/nityanand123gupta/output/github-contribution-grid-snake.svg" />
</picture>

