# ICANN 2026 Next Round gTLD Intelligence Explorer

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://sohib.github.io/icann-2026-gtld-explorer/)

An interactive visual intelligence dashboard mapping **2,056 applications** across **1,372 active top-level domain strings** submitted for the ICANN 2026 Next Round program.

🔗 **Live Website:** [https://sohib.github.io/icann-2026-gtld-explorer/](https://sohib.github.io/icann-2026-gtld-explorer/)

---

## 🚀 Key Features

* **▦ Zoomable Treemap (Squarified)**: Full rectangular space packing with readable labels, category hierarchies, and smooth drill-down.
* **◯ Zoomable Bubble Pack**: Refined D3 circle packing layout with glowing contested highlights; labels appear only after zoom makes them legible.
* **🖱 Mouse Scroll Zoom & Pan**: A contextual, dismissible first-use tip demonstrates how scrolling, pinching, or `+` reveals more TLD labels. `? Help` recalls it; drag to pan.
* **⚔ Contested Battleground (293 TLDs)**: Dedicated rivalry leaderboard ranking strings contested by multiple applicants (e.g. `.agent` with 13 rivals, `.bit` with 11, `.api` with 10, `.hub` with 10, `.brand` with 10).
* **🌐 IDN Translations & English Equivalents**: Comprehensive mapping for all 27 Internationalized Domain Name strings (`.xn--...`), showing their native Unicode characters (Chinese, Japanese, French), literal meaning, and closest single-word English TLD equivalent (e.g., `.官网` ≈ `.official`, `.智能体` ≈ `.agent`, `.人工智能` ≈ `.ai`, `.机器人` ≈ `.robot`, `.钱包` ≈ `.wallet`).
* **🏢 Top Applicants Portfolio (480 Entities)**: Ranked breakdown of major applicants (Link Freedom Group Ltd with 213, XYZ.COM LLC with 182, Intercap with 92, Radix with 70, Google/Charleston Road with 39, OpenAI, etc.) with 1-click portfolio drill-down.
* **☰ Data Directory & CSV Export**: Complete searchable, sortable database with one-click CSV download.
* **⚠ Typosquatting & File-extension Risk Review**: Two static, defensively focused queues: **gTLD similarity** lists precomputed font-aware visual matches at 80+ and groups them by closest delegated target; **file-extension cues** separately lists exact applications that match the comprehensive MIME database, including `.pdf`, `.php`, and `.tex`. Results are generated in this workstation from IANA root-zone version 2026100800, then embedded in `risk-results.js`; the browser does not fetch references or calculate similarity. Scores prioritize review; they do not attribute intent.
* **🔍 Real-Time Smart Search & Autocomplete**: Search by TLD string, English equivalent, native script, applicant name, or theme.

---

## 📊 Summary Statistics

* **Active Strings:** 1,372
* **Total Applications:** 2,056
* **Contested Wars (Multi-Applicant):** 293
* **Unique Applicants:** 480
* **Primary / Replacement Applications:** 2,001 / 55

---

## 🛠 Tech Stack

* HTML5 / CSS3 (Modern Glassmorphic Dark UI)
* D3.js v7 (Treemap, Pack Layout, Continuous Zoom & Pan)
* One deployed application file: `index.html` (Zero build step required)

---

## 📄 License

MIT License. Dataset derived from ICANN Next Round public records.
