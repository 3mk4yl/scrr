# Strategic Cyber Risk Report: Research Archive
> **Radical transparency in AI-assisted threat intelligence.**

This repository serves as the official open-source archive for the raw research dossiers referenced in the *Strategic Cyber Risk Report* publication series (available on Amazon). 

In an era of generative AI and epistemic fragmentation, trusting a cybersecurity book without seeing its source data is a critical vulnerability. This repository is my patch. I am open-sourcing the entire bibliography, allowing security practitioners, researchers, and peers to independently verify the data, trace the citations, and audit the chain of custody for every technical claim made in my publications.

---
## 📚 Publications & Book Index

Looking for the actual reports or the specific dossiers for a book you are reading?

**👉 [View the Publications Index (PUBLICATIONS.md)](PUBLICATIONS.md)**

---
## 🏗️ The Research Architecture (Chain of Custody)

To provide full transparency into how the information in our books is gathered, synthesized, and published, we employ a strict three-tier methodology:

### Layer 1: Original Data Acquisition

> The foundation of my reports is built upon raw, real-time data—including technical telemetry, academic pre-prints, and primary security disclosures—gathered via a wide-spectrum OSINT retriever stack.

### Layer 2: Autonomous Research Synthesis (This Repository)

> Using `gpt-researcher` (Custom Mode), the raw data is recursively filtered and multi-source verified to identify emerging patterns and technical edge cases. These outputs become the highly dense **Tier-2 Dossiers** hosted in this repository. *These files are published exactly as generated to ensure zero manipulation of the source data.*

### Layer 3: Human-Centric Curation (The Published Books)

> The final Amazon reports are the result of structural refinement and strategic synthesis using advanced LLMs under strict "Zero Invention" parameters. The human lead transforms high-density AI outputs into a cohesive, actionable narrative, mapping every claim back to the dossiers found here.

---

## 📂 Repository Structure
Dossiers are organized chronologically by publication year and book title:
```text
dossiers/
├── 2026/
│   └── 01-adversarial-machines/
│       ├── 1_autonomous_offensive_cyber_operations.md
│       ├── 2_llm_vulnerability_discovery.md
│       └── ...

```

---

## ⚖️ Disclosures & Disclaimers

### Research Methodology

These dossiers were generated using AI-assisted research tools that aggregate and summarize publicly available sources. They constitute secondary research and literature synthesis; they do not represent original empirical research or peer-reviewed findings.

### Professional Disclaimer

The use of Large Language Models (LLMs) and autonomous agents in technical research offers unprecedented speed, but it is not infallible. Despite rigorous prompting, iterative filtering, and manual curation, the nature of generative AI means that technical nuances, misattributions, or "hallucinations" may occasionally persist in the raw data.

While every effort has been made to verify the integrity of the published books, readers are strongly encouraged to consult the primary sources linked within these markdown dossiers before applying findings to mission-critical environments. **This archive is intended to augment—not replace—professional due diligence and hands-on validation.**

### License Note

The contents of this repository consist primarily of research reports and data dossiers. This work is licensed under a **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**.

You are free to share, fork, and reference these materials with proper attribution. You may not use this material for commercial purposes (e.g., you cannot repackage and sell these dossiers). Furthermore, nothing in this repository constitutes legal, financial, or professional cybersecurity advice.
