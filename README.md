# Kartikeya Pradhan

**Computer Science & Engineering Undergraduate | Software Engineer**  
Building dependable full-stack applications, computer vision & edge AI systems, and developer tooling.

---

### 👨‍💻 About Me

I am a Computer Science & Engineering undergraduate focused on practical software engineering and applied computer science. My work spans computer vision and edge intelligence, role-based web applications, algorithmic data analytics, and developer tooling.

- **What I build:** Practical systems that solve tangible problems—from privacy-preserving urban hazard auditing to digital agricultural supply chains and CPU cache simulators.
- **Engineering focus:** Clean architecture, verifiable execution, defensive programming, and choosing the right tool for the job without unnecessary framework overhead.
- **Current exploration:** Edge AI inference optimization, verifiable LLM-assisted program repair, and scalable distributed systems fundamentals.

---

### 🛠️ Technical Toolkit

| Category | Technologies & Tools |
| :--- | :--- |
| **Languages** | Python, TypeScript, JavaScript, Java, C, SQL, HTML5, CSS3 |
| **Frontend Development** | Next.js (App Router), React, Tailwind CSS, Vite |
| **Backend & Systems** | Node.js, Express, REST APIs, Streamlit, CLI Architecture |
| **AI & Computer Vision** | OpenCV, Ultralytics YOLOv8, LLM AST/Code Pipelines, Playwright, axe-core |
| **Databases & ORM** | PostgreSQL, Supabase, Drizzle ORM, SQLite |
| **Tools & Environments** | Git, GitHub Actions (CI/CD), Make, Linux, macOS, Vercel |
| *Currently Learning* | Distributed Systems, Docker containerization, Microservices architecture |

---

### 🚀 Featured Engineering Projects

#### 1. [AccessAudit](https://github.com/Kartik-idk/AccessAudit)
*AI-Assisted Accessibility Remediation & Verification Engine*
- **Problem:** LLM-generated code fixes often introduce syntax breakages, alter unrelated logic, or lack verification against actual web standards.
- **Solution:** Connects browser-level DOM violations (detected via Playwright and axe-core) directly to source code, prompts an LLM for structured AST edit operations (`ADD`, `UPDATE`, `REMOVE`), enforces deterministic semantic validation, and verifies the final build in a headless browser loop.
- **Tech Stack:** `TypeScript` • `Playwright` • `axe-core` • `Vite` • `Node.js` • `Automated Testing`

#### 2. [Drishti-Edge (दृष्टि-Edge)](https://github.com/Kartik-idk/drishti-edge)
*Privacy-Preserving Edge AI for Urban Safety Auditing & Video Hazard Mapping*
- **Problem:** Municipal safety auditing is manual and infrequent, while cloud-connected video surveillance poses severe civilian privacy risks.
- **Solution:** Processes video feeds locally at the edge, keeps raw frames transient without cloud transmission, redacts sensitive features (faces, license plates), and computes structured Zone Vulnerability Index (ZVI) telemetry across a 3×3 spatial grid for an auditor dashboard.
- **Award / Context:** Developed for the *Seva First Innovation Challenge*.
- **Tech Stack:** `Python` • `OpenCV` • `Ultralytics YOLOv8` • `Streamlit` • `SQLite` • `CI Test Suite`

#### 3. [Kisan Mandi MVP](https://github.com/Kartik-idk/Kisan-Mandi-mvp)
*Role-Based Digital Agricultural Marketplace & Supply Chain Workflow*
- **Problem:** Traditional agricultural mandis rely on opaque, paper-heavy lot handling, making price discovery and settlement difficult for farmers.
- **Solution:** A unified digital workflow providing dedicated, synchronized views for farmers, commission agents, merchants, palledars (labourers), and managers. Manages the complete lot lifecycle: arrival, weighing, quality assessment, multi-party bidding auctions, settlement, and dispatch.
- **Live Deployment:** [kisan-mandi-mvp.vercel.app](https://kisan-mandi-mvp.vercel.app)
- **Tech Stack:** `Next.js` • `TypeScript` • `React` • `Supabase` • `Tailwind CSS` • `Recharts`

#### 4. [RetailPulse](https://github.com/Kartik-idk/RetailPulse)
*Supermarket Sales Analytics Platform & Algorithmic Command Center*
- **Problem:** Heavy analytical frameworks (Pandas/NumPy) add steep memory footprints for standard batch retail aggregation pipelines.
- **Solution:** Ingests and validates historical supermarket sales records using pure standard-library Python algorithms. Features an interactive terminal command center and synchronizes with an 11-panel dark-themed Matplotlib executive visualization dashboard (5 KPI cards + 6 analytical charts).
- **Tech Stack:** `Python 3` • `Matplotlib` • `Standard Library (csv, datetime, pathlib)` • `Unittest`

#### 5. [CacheFlow](https://github.com/Kartik-idk/CacheFlow)
*Interactive CPU Cache Memory & Hierarchy Simulator*
- **Problem:** Memory hierarchy and cache eviction policies are abstract concepts that are difficult to visualize in computer architecture courses.
- **Solution:** A zero-dependency, browser-based simulator that models CPU, L1, L2, L3, and DRAM hierarchies. Allows users to step through memory addresses, observe four-slot cache lines, trace FIFO eviction, and inspect real-time hit/miss ratios and Average Memory Access Time (AMAT).
- **Live Deployment:** [cacheflow-ten.vercel.app](https://cacheflow-ten.vercel.app)
- **Tech Stack:** `JavaScript (ES6+)` • `HTML5` • `CSS3` • `Zero External Dependencies`

#### 6. [Smart Bill Calculator](https://github.com/Kartik-idk/Smart-Bill-Calculator)
*Production-Grade Retail Billing, Warranty Tracking & Invoicing System*
- **Problem:** Floating-point arithmetic drift in retail software causes rounding discrepancies in tax and financing calculations.
- **Solution:** Implements exact banking decimal arithmetic (`ROUND_HALF_UP`) across subtotals, GST taxation, and EMI installments. Features 128-column formatted tax invoicing, calendar-exact warranty expiration tracking handling leap years, and interactive warranty lookup.
- **Tech Stack:** `Python 3` • `Decimal` • `Standard Library` • `Make` • `26 Unit Tests`

---

### 🧩 Engineering Practices

- **Zero-Unnecessary-Dependencies:** Prioritizing language standard libraries and lightweight architectures before introducing third-party packages.
- **Verifiable AI Pipelines:** Grounding generative AI outputs with AST parsers, deterministic schema validators, and end-to-end browser verification.
- **Test-Driven Reliability:** Writing automated test suites (Python `unittest`, Playwright, GitHub Actions CI) to prevent regressions.
- **Defensive Design:** Explicit input sanitization, constant-time comparisons for sensitive operations, and graceful error handling without raw stack traces.

---

### 📬 Connect With Me

- **Email:** [kartikeyapradhan1@outlook.com](mailto:kartikeyapradhan1@outlook.com)
- **GitHub:** [@Kartik-idk](https://github.com/Kartik-idk)
