<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=24&pause=1000&color=58A6FF&center=true&vCenter=true&width=680&lines=Nityanand+Gupta;Computer+vision+%26+full-stack+engineer;Production+drone+detection+systems+%F0%9F%9A%81;Open-source+contributor+%E2%80%94+28k%2B%E2%98%85+upstream;I+ship+systems%2C+not+demos" alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Computer_Vision-111F68?style=for-the-badge&logo=opencv&logoColor=white" alt="Computer Vision" />
  <img src="https://img.shields.io/badge/Full_Stack-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Full Stack" />
  <img src="https://img.shields.io/badge/Open_Source-181717?style=for-the-badge&logo=github&logoColor=white" alt="Open Source" />
</p>

<p align="center">
  <img src="https://img.shields.io/github/followers/nityanand123gupta?style=flat-square&logo=github&label=Followers&labelColor=0D1117&color=58A6FF" alt="Followers" />
  <img src="https://img.shields.io/badge/Merged_PRs_upstream-4-58A6FF?style=flat-square&labelColor=0D1117" alt="Merged upstream PRs" />
  <img src="https://img.shields.io/badge/Upstream_stars_reached-28k%2B-58A6FF?style=flat-square&labelColor=0D1117" alt="Upstream stars" />
  <img src="https://img.shields.io/badge/Based_in-Hyderabad,_IN-58A6FF?style=flat-square&labelColor=0D1117" alt="Location" />
</p>

---

## 👨‍💻 Profile

I build **production computer-vision systems** and **full-stack products** end to end —
from model pipeline and database schema through to packaged installers and deploy.

My day-to-day is camera-only airspace security at **[Rungta Ventures](https://github.com/rungtaventures1)**:
drone and bird detection from ordinary IP/PTZ cameras with **no radar, RF or acoustic sensors**.
That constraint is the hard part, and it's where most of my engineering goes — pretrained UAV
YOLO models, a ByteTrack-style tracker, flight-pattern confirmation that vetoes the classic
bird false-alarms, and CLAHE weather preprocessing to pull faint targets out of fog, haze and
snow-glare.

Alongside that I contribute fixes upstream to widely-used open-source infrastructure, and build
TypeScript/Postgres products on Next.js 16.

```yaml
focus:      [computer vision, applied ML, full-stack product engineering]
production: camera-only drone detection · multi-site airspace monitoring
stack:      [Python, TypeScript, C++, PyTorch, YOLO, FastAPI, Next.js, Postgres]
education:  IIIT Hyderabad — B.Tech Computer Science
offline:    [chess ♟️, guitar 🎸, horse riding 🐎]
```

---

## 🔀 Merged upstream contributions

Shipped fixes and features into open-source projects used in production worldwide —
**28,000+ combined stars**.

| Project | ★ | Contribution | Diff |
|---|---:|---|---|
| **[faker-js/faker](https://github.com/faker-js/faker)** <br/><sub>Fake-data generation for JS/TS</sub> | 15.5k | [#4016 — `docs(helpers)`: document `weightedArrayElement` throws](https://github.com/faker-js/faker/pull/4016) | `+3 / −0` |
| **[evilmartians/lefthook](https://github.com/evilmartians/lefthook)** <br/><sub>Git hooks manager</sub> | 8.9k | [#1512 — `fix(run)`: error when `--job`/`--command` matches nothing](https://github.com/evilmartians/lefthook/pull/1512) | `+61 / −5` |
| **[django-oauth/django-oauth-toolkit](https://github.com/django-oauth/django-oauth-toolkit)** <br/><sub>OAuth2 provider for Django</sub> | 3.3k | [#1847 — `fix(rfc9207)`: add `iss` to authorization error redirects](https://github.com/django-oauth/django-oauth-toolkit/pull/1847) | `+199 / −40` |
| **[elementary/granite](https://github.com/elementary/granite)** <br/><sub>GTK widget library for elementary OS</sub> | 331 | [#1009 — `HeaderLabel`: add `justify` property](https://github.com/elementary/granite/pull/1009) | `+22 / −4` |

> The `django-oauth-toolkit` fix closes an **RFC 9207** spec gap — the `iss` issuer identifier
> was emitted on success but omitted on authorization *error* redirects, leaving clients unable
> to attribute failures in multi-provider deployments.

---

## 🚀 Selected work

### 🛰️ Airspace security & computer vision

| System | Detail |
|---|---|
| **RV AirGuard** · **RV SkyShield** <br/>`proprietary — Rungta Ventures` | Production multi-site airspace monitoring with Zone Intelligence. Camera-only detection stack, packaged Windows installers, operator dashboard. **~630k LOC Python + 338k LOC JS** across the two systems. |
| **[sky-watch-drone-zones](https://github.com/nityanand123gupta/sky-watch-drone-zones)** | Border/perimeter drone-threat monitor. Restricted-airspace ROI zones, Critical/Warning/Normal threat grading, border line-crossing and loitering alerts, acknowledgeable alert feed, event log with CSV export. **FastAPI + React.** |
| **[sky-watch-drone-monitor](https://github.com/nityanand123gupta/sky-watch-drone-monitor)** | Multi-camera deployment of the same pipeline — live annotated RTSP streams, per-camera drone/bird counts, activity charts. |

### 🤖 Applied AI & agent systems

| System | Detail |
|---|---|
| **[ai-sports-trade-analyzer](https://github.com/nityanand123gupta/ai-sports-trade-analyzer)** | Multi-agent NBA trade analyzer — a Scout / Quant / Cap / GM agent crew reasoning over a player-valuation model and a **CBA salary-cap rules engine** to produce a graded recommendation. CrewAI + Gemini/Claude, with a full architecture write-up in `DESIGN.pdf`. |

### 🧱 Product engineering

| System | Detail |
|---|---|
| **StudyMint** `private` | Study-support platform for university students — Next.js 16, Drizzle ORM, Clerk auth, Postgres. Built end to end from schema to deploy. |
| **Buddyly** `private` | TypeScript product platform. Shipped venue search, consent-flow and DigiLocker redirect fixes (**+3,012 / −139** in one QA cycle) and uncapped bulk data export. |
| **Relationship OS** `private` | TypeScript + PLpgSQL CRM. Delivered a UI/performance/reliability overhaul with Daily Lineup, AI-budget fix, test fixtures and CI — **+5,358 / −432**. |

---

## 🧰 Engineering stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)

**ML & computer vision**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Ultralytics](https://img.shields.io/badge/Ultralytics_YOLO-111F68?style=for-the-badge&logo=yolo&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-FF5A50?style=for-the-badge&logo=robotframework&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

**Backend & data**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=for-the-badge&logo=clerk&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

**Infrastructure & tooling**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 📊 Engineering activity

<p align="center">
  <img src="./profile/stats.svg" alt="GitHub stats" width="49%" />
  <img src="./profile/top-langs.svg" alt="Most used languages" width="40%" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=nityanand123gupta&theme=tokyonight&hide_border=true" alt="Contribution streak" width="60%" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=nityanand123gupta&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution%20activity" alt="Contribution activity graph" width="98%" />
</p>

---

## 📌 Featured repositories

<p align="center">
  <a href="https://github.com/nityanand123gupta/sky-watch-drone-zones"><img src="./profile/pin-sky-watch-drone-zones.svg" alt="sky-watch-drone-zones" width="49%" /></a>
  <a href="https://github.com/nityanand123gupta/ai-sports-trade-analyzer"><img src="./profile/pin-ai-sports-trade-analyzer.svg" alt="ai-sports-trade-analyzer" width="49%" /></a>
</p>
<p align="center">
  <a href="https://github.com/nityanand123gupta/sky-watch-drone-monitor"><img src="./profile/pin-sky-watch-drone-monitor.svg" alt="sky-watch-drone-monitor" width="49%" /></a>
</p>

---

## 🐍 Contribution graph

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nityanand123gupta/nityanand123gupta/output/github-contribution-grid-snake-dark.svg" />
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/nityanand123gupta/nityanand123gupta/output/github-contribution-grid-snake.svg" />
</picture>

---

## 🤝 Contact

<p align="center">
  <a href="mailto:hr@rungtaventures.ai"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://github.com/nityanand123gupta"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

<p align="center"><sub>Off the keyboard: chess ♟️ · guitar 🎸 · horse riding 🐎</sub></p>
