<!-- =================================================================== -->
<!--  ZAFAR JAMAL — GitHub profile README                                -->
<!--  Professional first, noir second. Survives with all imagery off.    -->
<!-- =================================================================== -->

<p align="center">
  <img src="assets/hero.svg" alt=" " width="1000" />
</p>

<h1 align="center">ZAFAR JAMAL</h1>

<p align="center">
  <sub><b>software engineering · backend · geospatial systems</b></sub>
</p>

<p align="center">
  <em>“The night was long. The bug was longer.”</em>
</p>

<p align="center">
  <a href="https://github.com/bashfullad78"><b>&nbsp;GitHub&nbsp;</b></a>&nbsp;·&nbsp;
  <a href="https://linkedin.com/in/zafar-jamal-3a0a1b386/"><b>&nbsp;LinkedIn&nbsp;</b></a>&nbsp;·&nbsp;
  <a href="mailto:viperzafar@gmail.com"><b>&nbsp;Email&nbsp;</b></a>
</p>

<br />

<p align="center">
  <img src="assets/divider.svg" alt="" width="860" />
</p>

### 01 / PROFILE

I build practical software across backend engineering, web applications and geospatial computing. My current work spans Python/FastAPI services, creating smooth websites, PostgreSQL-backed systems, React applications, data pipelines and optimization problems on real-world geographic data. I am particularly interested in the parts of software that become important after the demo works: authentication, transactions, validation, testing, reproducibility and deployment.

### 02 / WHAT I BUILD

**BACKEND SYSTEMS** — APIs · authentication · databases · transactional logic

**WEB APPLICATIONS** — React · responsive interfaces · API integration

**DATA & COMPUTATIONAL SYSTEMS** — pipelines · optimization · spatial analysis · reproducibility

**GEO / OPEN DATA** — OpenStreetMap · WorldPop · OSMnx · GeoPandas

**ENGINEERING** — testing · CI · Linux · deployment

### 03 / TOOLBOX

**Languages** — Python · C++ · JavaScript · SQL

**Backend** — FastAPI · REST APIs · Pydantic · SQLAlchemy

**Databases** — PostgreSQL · SQLite · Alembic

**Frontend** — React · Vite · TypeScript · HTML · CSS · Javascript

**Geospatial / Computational** — OpenStreetMap · OSMnx · GeoPandas · WorldPop · MCLP · E2SFCA · spatial analysis

**Engineering / Infrastructure** — Git · GitHub Actions · Linux · pytest

### 04 / SELECTED WORK

---

**01 — ATLASIS**
*Healthcare facility siting pipeline*

Open geospatial framework that recommends where new hospitals should go so the most people reach one within a fixed drive time — built entirely on free data: OSM road networks via OSMnx and WorldPop population rasters. Ranks single sites by road-network drive time, selects complementary site sets jointly (MCLP, lazy-greedy solver benchmarked against an exact MILP), grades access with an E2SFCA index and attaches sensitivity intervals to headline figures.

`Python` · `OSM/OSMnx` · `WorldPop` · `GeoPandas` · `MCLP` · `E2SFCA`

`8 cities` · `4 countries` · `97 automated tests` · `CI on every push` · `zero paid APIs`

→ [Repository](https://github.com/bashfullad78/Atlasis) · [Analyses](https://github.com/bashfullad78/Atlasis/tree/main/docs/analyses)

---

**02 — CAMPUS-VAULT**
*Full-stack academic file-sharing platform*

A college-specific academic PDF platform with a virtual coin economy. JWT auth with refresh rotation and global token revocation, config-driven storage abstraction (local / any S3-compatible bucket), server-side file validation and dedup via content hashing, and a transactional wallet that locks wallet rows with ledger-backed balances — concurrency-tested so parallel spends can never overdraw.

`FastAPI` · `PostgreSQL` · `SQLAlchemy` · `Alembic` · `React` · `Vite` · `TypeScript` · `JWT`

`42 backend tests` · `25-step E2E smoke test` · `transactional coin engine` · `streamed file validation`

→ [Repository](https://github.com/bashfullad78/Campus-Vault)

---

**03 — URL SHORTENER**
*Analytics-focused shortening service*

Backend REST API for shortening URLs with authenticated ownership and click tracking. Every redirect atomically records the click and increments the counter in the same transaction; daily breakdowns and per-link summaries run on deliberate raw-SQL analytics queries over PostgreSQL's native INET type.

`FastAPI` · `PostgreSQL` · `raw SQL` · `JWT` · `Pydantic`

`atomic click tracking` · `JWT ownership` · `daily + summary analytics`

→ [Repository](https://github.com/bashfullad78/URL-Shortener)

---

<p align="center">
  <img src="assets/divider.svg" alt="" width="860" />
</p>

### 05 / ENGINEERING NOTES

```text
01 · A working demo is the bareback of a product.

02 · Failure cases deserve more attention than happy paths.

03 · Infrastructure should remain understandable.

04 · Tests should protect important behaviour instead of inflating coverage.

05 · Open data and free infrastructure are useful constraints when they
     force better engineering decisions.

06 · Reproducibility matters when software produces analytical results.
```

### 06 / CURRENTLY

**BUILDING** — Backend-heavy applications and practical developer tooling.

**EXPLORING** — Deployment, DevOps, networking and systems fundamentals.

**RESEARCHING** — Geospatial accessibility, facility siting and reproducible open-data workflows.

**LOOKING FOR** — Software engineering internships, practical collaborations and technically interesting projects.

### 07 / CONTACT

I can contribute to:

```text
REST/API development            ·  backend services
PostgreSQL-backed applications  ·  authentication & authorization
internal tools                  ·  data-processing pipelines
geospatial applications         ·  technical prototypes
testing and CI                  ·  deployment-oriented engineering
```

<p align="center">
  <a href="mailto:viperzafar@gmail.com"><b>EMAIL</b></a> &nbsp;—&nbsp;
  <a href="https://linkedin.com/in/zafar-jamal-3a0a1b386/"><b>LINKEDIN</b></a> &nbsp;—&nbsp;
  <a href="https://github.com/bashfullad78"><b>GITHUB</b></a>
</p>

<br />

<p align="center">
  <img src="assets/divider.svg" alt="" width="860" />
</p>

<p align="center">
  <sub><b>ZAFAR JAMAL</b> · software · systems · geospatial</sub><br />
  <sub>Open data in. Evidence out.</sub>
</p>
