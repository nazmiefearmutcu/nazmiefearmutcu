<div align="center">

# Hi, I'm Aylin 👋
**AI Developer & Quantitative Engineer**

*"Working on financial engineering of AI and researching alternative AI/ML methodologies."*

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=nazmiefearmutcu&show_icons=true&theme=tokyonight&hide_border=true&title_color=14b8a6&icon_color=14b8a6&text_color=94a3b8&bg_color=0f172a)](https://github.com/anuraghazra/github-readme-stats)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=nazmiefearmutcu&layout=compact&theme=tokyonight&hide_border=true&title_color=14b8a6&text_color=94a3b8&bg_color=0f172a&langs_count=6)](https://github.com/anuraghazra/github-readme-stats)

---

[**Research Directions**](#-research-directions) · [**Highlighted Projects**](#-highlighted-projects) · [**Technical Stack**](#-technical-stack) · [**Full Repository Index**](#-full-repository-index) · [**Contact**](#-get-in-touch)

</div>

---

## 🔬 Research Directions

My research sits at the intersection of **deep learning theory**, **computational neuroscience**, and **quantitative finance**. I focus on local, biologically plausible learning dynamics and their application to high-frequency, non-stationary financial data.

*   **Deep Learning & Sequence Modeling:** Designing efficient alternatives to standard self-attention mechanisms. Currently exploring parameter-free, quadratic delta-state sequence mixers (`Prizma-Seq`) to achieve linear/quadratic space-time efficiency without loss of long-range context.
*   **Computational Neuroscience & Active Inference:** Investigating backpropagation-free, local-plasticity architectures (`Cerebrum`, `Prizma`). Designing active inference agents that settle states under Langevin stochastic differential equations (SDEs) and update weights via multi-factor Hebbian rules.
*   **Financial Engineering & NLP:** Deploying specialized sentiment-analysis and cross-attention architectures (`FinBERT`, `RoBERTa`, `news_impact_v1`) to map unstructured public web streams (news, RSS, transcripts) to real-time market impact and asset class movements.

---

## 🚀 Highlighted Projects

Here are the core projects and research threads currently active on my profile:

### 🧠 Neuromorphic & Sequence Modeling Research

#### [Cerebrum](https://github.com/nazmiefearmutcu/Cerebrum)
> **Backpropagation-Free Neuromorphic Learning Architecture**
*   **Core Concept:** A biologically plausible, predictive-coding learning model built entirely in **pure NumPy** (completely autograd-free).
*   **Mechanism:** Coordinates state inference, dynamic routing, and learning across three physical timescales: Langevin SDE neural settling, basal-ganglia-gated workspace routing, and surprise-gated multi-factor Hebbian plasticity.
*   **Technologies:** `Python`, `NumPy`, `Computational Neuroscience`, `Active Inference`.

#### [Prizma](https://github.com/nazmiefearmutcu/Prizma)
> **Sequence Modeling & Local Plasticity Research Threads**
*   **Core Concept:** Dual research tracks focused on efficient attention and local learning.
*   **Features:** Contains **Prizma-Seq** (a parameter-free, quadratic delta-state sequence mixer proposed as an efficient-attention replacement candidate) and **Prizma** (a backprop-free, local continual learning framework). Both run under pre-registered falsifiable bars and adversarial referee audits.
*   **Technologies:** `Python`, `PyTorch`, `Deep Learning`, `Sequence Models`.

### 📊 Local-First Data & Financial Engineering

#### [showMe](https://github.com/nazmiefearmutcu/showMe)
> **High-Density Desktop Financial Terminal for macOS**
*   **Core Concept:** A local-first command-palette driven desktop terminal that brings Bloomberg-style command workflows to your Mac.
*   **Features:** Evaluates 138 financial analyst functions (from DCF models to options gamma grids and yield curve analytics) across 3,370 symbols and 12 timeframes.
*   **Technologies:** `Tauri (Rust)`, `React`, `Python (FastAPI Sidecar)`, `Binance API`, `Technical Analysis`.

#### [catchem](https://github.com/nazmiefearmutcu/catchem)
> **Local NLP Financial News Ingestion & Classifier**
*   **Core Concept:** A local-first desktop application that reads incoming RSS and news feeds to predict immediate market impacts.
*   **Features:** Classifies news items by targeted asset class, expected direction of movement, and impact timeframe. Runs completely offline on your device.
*   **Technologies:** `Python`, `FastAPI`, `React`, `Tauri`, `Financial NLP`.

#### [awareness](https://github.com/nazmiefearmutcu/awareness)
> **Laptop-Scale Public Web Data Ingest Pipeline**
*   **Core Concept:** A highly efficient, single-process pipeline that harvests open-web datasets onto local storage.
*   **Features:** Streams and processes Common Crawl, Hugging Face FineWeb, RSS, and GDELT without cloud clusters or Spark. Fully queryable offline in milliseconds using DuckDB SQL.
*   **Technologies:** `Python`, `DuckDB`, `Apache Iceberg`, `OSINT`, `Web Scraping`.

### 🤖 Agentic Infrastructure

#### [antigravity-ralph](https://github.com/nazmiefearmutcu/antigravity-ralph)
> **Continuous Self-Improving Loop for Google Antigravity**
*   **Core Concept:** An autonomous execution harness for Google Antigravity agents.
*   **Features:** Drives the `agy` headless CLI using a git-backed metric ratchet, guaranteeing that every agent handoff is strictly better than the last. Keeps agent execution loops running and improving indefinitely.
*   **Technologies:** `Agentic AI`, `Google Antigravity SDK`, `Gemini API`, `Bash`, `Developer Tools`.

---

## 🛠️ Technical Stack

### 💻 Languages & Environments
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)](https://www.gnu.org/software/bash/)
[![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)](https://en.wikipedia.org/wiki/SQL)

### 🧠 Deep Learning, NLP & Computational Research
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)](https://numpy.org/)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/)
[![Transformers](https://img.shields.io/badge/Transformers-FinBERT%20%7C%20RoBERTa-8A2BE2?style=flat-square)](https://huggingface.co/models)

### 🗄️ Data Engineering & Local Databases
[![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)](https://duckdb.org/)
[![Apache Iceberg](https://img.shields.io/badge/Apache%20Iceberg-0078D4?style=flat-square&logo=apache&logoColor=white)](https://iceberg.apache.org/)
[![Polars](https://img.shields.io/badge/Polars-CD7F32?style=flat-square)](https://pola.rs/)

### 🖼️ App Shells & UI Frameworks
[![Tauri](https://img.shields.io/badge/Tauri-FFC131?style=flat-square&logo=tauri&logoColor=black)](https://tauri.app/)
[![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)](https://www.electronjs.org/)
[![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)](https://react.dev/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Compose Multiplatform](https://img.shields.io/badge/Compose%20Multiplatform-Android%20%7C%20Kotlin-3DDC84?style=flat-square&logo=android&logoColor=white)](https://www.jetbrains.com/lp/compose-multiplatform/)

---

## 📂 Full Repository Index

<details>
<summary><b>🛠️ Other Original Projects (Click to expand)</b></summary>
<br/>

*   **[Crypcodile](https://github.com/nazmiefearmutcu/Crypcodile):** Open-source crypto market-data engine. Ingests, normalizes, stores, and retrieves WebSocket and historical REST data from 6 major venues into a local partitioned Parquet lake.
*   **[dive-into-crypto](https://github.com/nazmiefearmutcu/dive-into-crypto):** Native Android futures scanner for Binance USDT-M. Evaluates 15 indicators across 12 timeframes using Compose Multiplatform.
*   **[news_impact_v1](https://github.com/nazmiefearmutcu/news_impact_v1):** Model artifact package for TBV NewsImpact v1 (financial cross-attention news transformer).
*   **[such-a-good-clock](https://github.com/nazmiefearmutcu/such-a-good-clock):** Highly aesthetic fullscreen clock PWA and native app featuring 11 cinematic themes, Pomodoro timers, and ambient audio loops.
</details>

<details>
<summary><b>📚 Curated Awesome Lists (Click to expand)</b></summary>
<br/>

I actively maintain several curated lists to track tools and frameworks in fields I follow closely:
*   [awesome-quant](https://github.com/nazmiefearmutcu/awesome-quant) - Quantitative finance libraries, resources, and datasets.
*   [awesome-algorithmic-trading](https://github.com/nazmiefearmutcu/awesome-algorithmic-trading) - Algorithmic trading frameworks and platforms.
*   [awesome-crypto-trading-bots](https://github.com/nazmiefearmutcu/awesome-crypto-trading-bots) - Automated cryptocurrency trading strategies and bots.
*   [awesome-fintech](https://github.com/nazmiefearmutcu/awesome-fintech) - Open-source fintech libraries.
*   [awesome-data-engineering](https://github.com/nazmiefearmutcu/awesome-data-engineering) - Data engineering software and pipelines.
*   [awesome-tauri](https://github.com/nazmiefearmutcu/awesome-tauri) - Selected Tauri applications and plugins.
*   [awesome-electron-alternatives](https://github.com/nazmiefearmutcu/awesome-electron-alternatives) - Lightweight alternatives to Electron.
*   [awesome-electron](https://github.com/nazmiefearmutcu/awesome-electron) - Curated tools and resources for Electron.
*   [awesome-fastapi](https://github.com/nazmiefearmutcu/awesome-fastapi) - Resources and extensions for FastAPI.
*   [awesome-pwa](https://github.com/nazmiefearmutcu/awesome-pwa) - Progressive Web Apps.
*   [awesome-python-applications](https://github.com/nazmiefearmutcu/awesome-python-applications) - Production-grade open source Python applications.
*   [awesome-selfhosted](https://github.com/nazmiefearmutcu/awesome-selfhosted) - Self-hostable network services.
*   [awesome-osint](https://github.com/nazmiefearmutcu/awesome-osint) - Open-source intelligence tools.
</details>

---

## 📬 Get in Touch

*   **Email:** [nazmiefearmutcu@posta.mu.edu.tr](mailto:nazmiefearmutcu@posta.mu.edu.tr)
*   **GitHub:** [@nazmiefearmutcu](https://github.com/nazmiefearmutcu)
