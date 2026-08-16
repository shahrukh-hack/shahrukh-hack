<div align="center">

# Hi there, I'm Yogeshkumar Patel ðŸ‘‹
### AI Developer & Design Engineer â€¢ Adelaide, Australia ðŸ‡¦ðŸ‡º

<p align="center">
  <em>"Obsessed with crafting bespoke, high-taste digital experiences, autonomous AI agents, and resilient enterprise systems."</em>
</p>

[![Location](https://img.shields.io/badge/Location-Adelaide%2C%20Australia%20ðŸ‡¦ðŸ‡º-181717?style=for-the-badge&logo=google-maps)](https://github.com/shahrukh-hack)
[![Focus](https://img.shields.io/badge/Focus-AI%20Development%20%26%20Design%20Engineering-FF0055?style=for-the-badge&logo=framer)](https://github.com/shahrukh-hack)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Yogeshkumar%20Patel-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/yogeshkumar-ai/)
[![Profile Views](https://komarev.com/ghpvc/?username=shahrukh-hack&style=for-the-badge&color=2563EB&label=Profile%20Views)](https://github.com/shahrukh-hack)

<br />

</div>

---

## âš¡ About Me & Core Focus

I am an AI developer and design engineer based in **Adelaide, South Australia**, specializing in **Autonomous AI Multi-Agent Workflows**, **High-Taste Design Engineering (UI/UX)**, and **Enterprise Systems Architecture**.

- ðŸª„ **High-Taste Web Design:** Eradicating robotic "AI slop" by engineering physics-based animations (Framer Motion / Emil Kowalski spring curves), bespoke typography pairings, and tactile interfaces.
- ðŸ¤– **Autonomous AI Agents & RAG:** Building intelligent LLM pipelines, autonomous multi-agent workflows, and custom MCP tools using Antigravity, OpenAI, Claude, and Gemini.
- ðŸ¢ **Enterprise Automation & Data Pipelines:** Architecting business automation engines, price scrapers, and ERP data synchronization systems.

---

## ðŸŒŸ Public Flagship Applications & Live Demos

| Project | GitHub Repository | ðŸŒ Standalone Live Demo | Description |
| :--- | :--- | :--- | :--- |
| **ðŸª„ Vibe Superkit** | [`shahrukh-hack/vibe-superkit`](https://github.com/shahrukh-hack/vibe-superkit) | **[Live Demo](https://shahrukh-hack.github.io/vibe-superkit/)** | Anti-AI Slop & High-Taste Design Engine for Vibe Coders & Antigravity agents. |
| **ðŸ“ˆ Lakshmi AI** | [`shahrukh-hack/lakhsmiAI`](https://github.com/shahrukh-hack/lakhsmiAI) | **[Live Demo](https://shahrukh-hack.github.io/lakhsmiAI/)** | Stock market forecasting & financial intelligence dashboard with ApexCharts. |
| **ðŸŒ¬ï¸ LCA Wind Turbine** | [`shahrukh-hack/LCA-bolt`](https://github.com/shahrukh-hack/LCA-bolt) | **[Live Demo](https://shahrukh-hack.github.io/LCA-bolt/)** | Wind turbine Life Cycle Assessment with D3 Sankey carbon flow diagrams. |
| **ðŸŒ Siddheshwar Sai Infotech** | [`shahrukh-hack/ssi`](https://github.com/shahrukh-hack/ssi) | **[Live Demo](https://shahrukh-hack.github.io/ssi/)** | Enterprise IT consulting, cloud infrastructure, and AI solutions web portal. |
| **ðŸ“„ Document Similarity** | [`shahrukh-hack/similarity-new`](https://github.com/shahrukh-hack/similarity-new) | **[Live Demo](https://shahrukh-hack.github.io/similarity-new/)** | Semantic document comparison, text overlap analysis, and plagiarism verification. |
| **ðŸ›¡ï¸ AI Content Detector** | [`shahrukh-hack/AI-detection`](https://github.com/shahrukh-hack/AI-detection) | **[Live Demo](https://shahrukh-hack.github.io/AI-detection/)** | Real-time linguistic perplexity and synthetic vs human text detection platform. |
| **ðŸ¤– Awesome LLM Apps** | [`shahrukh-hack/awesome-llm-apps`](https://github.com/shahrukh-hack/awesome-llm-apps) | [`GitHub`](https://github.com/shahrukh-hack/awesome-llm-apps) | Production LLM applications, autonomous agent workflows, and RAG architectures. |

---

## ðŸ›ï¸ Enterprise Systems & Commercial Architecture

Below are in-depth technical specifications and architectural workflows for private enterprise systems engineered by Yogeshkumar Patel:

---

### ðŸ“Š 1. Excel-Driven Competitor Price Tracker (`competitor_price_tracker`)
> **Domain:** Automated E-Commerce Scraping & Spreadsheet Reporting

* **The Problem:** Merchandisers needed a lightweight way to monitor competitor price shifts from daily email feeds and Excel price lists without modifying their existing spreadsheet workflow.
* **The Solution:** Engineered an automated Python tracking engine with email alert parsers (`email_fetcher.py`), scheduled background workers (`scheduler.py`), and price difference recalculators (`price_updater.py`) exporting clean comparative Excel/CSV reports.
* **Tech Stack:** `Python 3` â€¢ `Pandas` â€¢ `OpenPyXL` â€¢ `BeautifulSoup4` â€¢ `Async Scheduler`

```mermaid
graph LR
    A[Excel SKU Master / Email Feeds] -->|email_fetcher.py| B[Price Scraper Engine]
    B --> C[price_updater.py Delta Engine]
    C --> D[scheduler.py Daemon]
    D --> E[Clean Comparative Excel / CSV Reports]
```

---

### ðŸ—„ï¸ 2. Database-Backed Retail Intelligence & Arbitrage Engine (`competitor_price_tracker_db`)
> **Domain:** Multi-Retailer Scraping, Relational Database & Real-Time Analytics

* **The Problem:** Enterprise retail businesses tracking thousands of electronics SKUs across multiple major Australian retailers (Scorptec, Umart, JB Hi-Fi, Centre Com, JW, The Good Guys) required a persistent relational database, category-level margin tracking, and price arbitrage analytics.
* **The Solution:** Architected a high-throughput scraping engine backed by a relational SQLite database (`price_tracker.db`), modular scraper workers, an automated analytics manager (`analytics_manager.py`), and an interactive web dashboard with price history and monopoly detection.
* **Tech Stack:** `Python` â€¢ `SQLite / SQLAlchemy` â€¢ `FastAPI / REST` â€¢ `Playwright / Chromium` â€¢ `Chart.js`

```mermaid
graph LR
    A[Australian Retailers: Umart, Scorptec, JB Hi-Fi, Centre Com] -->|Headless Scrapers| B[Data Normalization Pipeline]
    B --> C[(Relational DB: price_tracker.db)]
    C --> D[analytics_manager.py]
    D --> E[Arbitrage & Monopoly Detection]
    D --> F[Live Analytics Web Dashboard]
```

---

### âš¡ 3. Excel-to-MYOB ERP Cloud Price Sync Engine (`myob_price_sync`)
> **Domain:** Financial & Enterprise ERP Automation Pipeline

* **The Problem:** Finance and inventory teams spent hours manually re-typing approved Excel supplier price sheets into MYOB ERP, resulting in margin errors and fulfillment delays.
* **The Solution:** Engineered a dedicated Excel-to-ERP bridge (`price_reader.py`) that validates spreadsheet data, handles currency/tax normalization, and automatically commits bulk item price updates to MYOB AccountRight / Essentials via the official MYOB REST API (`myob_client.py`) with token refresh and rate limiting.
* **Tech Stack:** `Python` â€¢ `MYOB Cloud REST API` â€¢ `OAuth2 Integration` â€¢ `OpenPyXL` â€¢ `FastAPI Webhook Bridge`

```mermaid
graph LR
    A[Approved Excel Supplier Price Sheets] -->|price_reader.py Validation| B[Price Normalization Engine]
    B --> C[myob_client.py with OAuth2 & Token Refresh]
    C -->|Secure REST API Webhooks| D[MYOB Enterprise Cloud ERP]
    D --> E[Live Synchronized Inventory & Invoicing]
```

---

### ðŸš— 4. South Australia Smart Fleet & Driver Hub (`sa-drive-smart-hub`)
> **Domain:** Regional Mobility, Logistics & Transport Compliance (Adelaide, SA)

* **The Problem:** Fleet dispatchers required real-time corridor monitoring, driver duty compliance, and incident telemetry across South Australian transport routes.
* **The Solution:** Engineered a responsive fleet management platform featuring dynamic route corridor filtering, status metrics, and geofencing telemetry.
* **Tech Stack:** `React 18` â€¢ `TypeScript` â€¢ `Tailwind CSS` â€¢ `Mapbox/Leaflet` â€¢ `Lucide`

```mermaid
graph LR
    A[SA Route Corridors] -->|GPS Telemetry| B[Live Ingestion Hub]
    B --> C[Compliance & Safety Matrix]
    C --> D[Dispatcher Central Console]
```

---

### ðŸŒ¬ï¸ 5. Aerodynamic Airflow & Turbine Yield Analytics (`wind-flow-insights`)
> **Domain:** Renewable Energy & Environmental Modeling

* **The Problem:** Stakeholders needed an intuitive interface to model wind turbine power yields based on real-time meteorological vector fields.
* **The Solution:** Developed a mathematical vector animation dashboard that simulates laminar wind velocity, turbine efficiency curves, and estimated power generation (MW).
* **Tech Stack:** `React` â€¢ `TypeScript` â€¢ `D3.js` â€¢ `Vector Mathematics` â€¢ `Tailwind CSS`

```mermaid
graph LR
    A[Meteorological Sensors] -->|Wind Velocity & Vectors| B[Aerodynamic Engine]
    B --> C[Turbine Efficiency Model]
    C --> D[Power Yield Forecast MW]
```

---

### ðŸ¢ 6. CNC Corporate IT Services & E-Commerce Platform (`cncnew-website`)
> **Domain:** Enterprise Managed IT, Disaster Recovery, Cloud Security & IT Hardware Shop (Adelaide, SA)

* **The Problem:** An established South Australian managed IT service provider needed a modern, high-performance web portal integrating enterprise service catalogs (Disaster Recovery, Network Management, Server Solutions), live hardware inventory feeds, automated quote generators, and an intelligent AI customer support chat engine.
* **The Solution:** Architected a comprehensive full-stack corporate portal featuring dynamic product catalogs (`products.json`), automated inventory feed synchronizers (`sync_feed.php`), instant quote generation workflows (`send_quote.php`), customer survey engines, and an integrated AI support assistant (`ai_chat.php`).
* **Tech Stack:** `PHP Backend` â€¢ `JavaScript (ES6+)` â€¢ `Tailwind CSS` â€¢ `REST Endpoints` â€¢ `AI Chatbot Integration` â€¢ `Automated Survey Engines`

```mermaid
graph LR
    A[Adelaide Enterprise Clients] -->|Corporate Web Portal| B[CNC Services Engine]
    B --> C[ai_chat.php / AI Customer Support]
    B --> D[sync_feed.php / Hardware Catalog Sync]
    B --> E[send_quote.php / Enterprise Quote Engine]
    B --> F[Managed IT, Disaster Recovery & Cloud Security]
```

---

## ðŸ› ï¸ Technical Stack & Arsenal

| Domain | Core Technologies |
| :--- | :--- |
| **Frontend & Design** | `React 19` `Next.js` `TypeScript` `Tailwind CSS` `Framer Motion` `Radix UI` `Lenis` `D3.js` `VisX` |
| **AI & LLM Workflows** | `Autonomous Agents` `RAG Pipelines` `Antigravity` `OpenAI` `Claude` `Gemini` `MCP Protocol` |
| **Backend & Automation** | `Python` `FastAPI` `PHP` `Node.js` `REST APIs` `PostgreSQL` `SQLite` `MYOB API` |
| **Tooling & Cloud** | `Git` `GitHub Actions` `Docker` `Vite` `VS Code` `Cursor` `Linux` `Terminal` |

---

## ðŸ“Š Developer Snapshot

```yaml
Name: Yogeshkumar Patel
Location: Adelaide, South Australia (ACST / UTC+9:30)
Role: AI Developer & Design Engineer
Primary Stack: TypeScript, React, Next.js, Python, Tailwind, Framer Motion
Specialties: Autonomous Agents, RAG Pipelines, Bespoke High-Taste Web Systems, Enterprise Sync
Current Focus: Building Next-Gen Vibe Coding Tools & AI-Native Applications
Open For: High-Impact AI Projects, Consultations & Full-Stack Collaboration
```

---

<div align="center">
  <p><b>Interested in collaborating or building high-taste AI products?</b></p>
  <a href="https://www.linkedin.com/in/yogeshkumar-ai/">
    <img src="https://img.shields.io/badge/Connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin" />
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/shahrukh-hack">
    <img src="https://img.shields.io/badge/GitHub-@shahrukh--hack-181717?style=for-the-badge&logo=github" />
  </a>
  <br /><br />
  <sub>Designed with intention by Yogeshkumar Patel â€¢ Adelaide, South Australia ðŸ‡¦ðŸ‡º</sub>
</div>
