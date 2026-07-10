# Civic Action Toolkit Template
> An open-source, high-rigor framework for replicable citizen advocacy, macro-sociology analytics, and public interest pitches.

This repository provides an independent, structured workspace that utilizes open-source intelligence (OSINT), systems theory, and applied political economy to analyze local community issues. 

It is designed to be hosted entirely for free via **GitHub Pages**, translating complex public datasets into accessible, plain-spoken public action proposals and community mobilization toolkits.

---

## How This Toolkit Works (The Sandbox Engine)
To prevent data hallucinations and attention dilution common in large language models, this toolkit relies on a **modular, multi-session sandbox architecture**. 

Instead of processing an entire issue at once, the analysis is broken down into granular subsections. Each individual markdown file contains a **hidden, specialized AI prompt** embedded as an HTML comment (`<!-- prompt -->`) at the very top. 

### Step-by-Step Deployment Guide:
1. **Fork This Repository:** Click the **Fork** button in the top right of this page to create your own independent copy of this toolkit under your GitHub profile.
2. **Collect Local OSINT Data:** Gather public records relevant to your targeted community issue (e.g., property assessor ledgers, city council meeting logs, municipal GIS maps, or public health equity reports).
3. **Execute the Prompts:** 
   * Navigate to a subsection file (e.g., `steeple-analysis/economic-solidarity.md`).
   * Click the edit icon to view the raw text and copy the hidden `MASTER AI PROMPT` block.
   * Open a **fresh, isolated AI session** with web browsing enabled.
   * Paste the prompt along with your raw local dataset to generate highly rigorous, objective findings.
4. **Update the Workspace:** Replace the template text with the AI's generation, commit your changes, and save the file.

---

## Repository Directory Tree
```text
├── index.md                        # The Main Web Hub (Home Page Dashboard)
├── README.md                       # Repository Documentation (This File)
├── _config.yml                     # Jekyll settings (Visual theme engine)
├── assets/                         # Visual Media & Brand Assets
│   ├── favicon.png                 # Browser tab icon
│   └── thumbnail.jpg               # Open-graph social link preview image
├── steeple-analysis/               # Part 1: STEEPLE Environmental Scan
│   ├── sociocultural-health.md     # SDoH & community stability metrics
│   ├── economic-solidarity.md      # Capital tracing & alternative economics
│   ├── legal-political.md          # Jurisdictional power mapping & statutes
│   └── techno-environmental.md     # Infrastructure deficits & data barriers
├── systems-dynamics/               # Part 2: Underlying Machinery & Loops
│   ├── feedback-loops.md           # Reinforcing societal loops & dependencies
│   └── institutional-friction.md   # Bureaucratic gatekeeping & accountability gaps
└── civic-leverage/                 # Part 3: Public Action & Mobilization
    ├── pressure-points.md          # Target administrative boards & executives
    └── action-scripts.md           # Plain-spoken deep canvassing scripts
```

---

## Launching Your Live Webpage
This template is completely pre-configured for mobile-responsive web hosting:
1. Go to your forked repository's **Settings** tab.
2. Click **Pages** in the left-hand menu.
3. Under *Build and deployment*, set the Source to **Deploy from a branch**.
4. Set the Branch dropdown to **`main`** and the folder to **`/ (root)`**.
5. Click **Save**.

Your live toolkit dashboard will be published at: `https://[your-username].github.io/civic-action-toolkit/`

---

## Open-Source License & Collaboration
This toolkit is a free, independent educational resource. It is shared under the **CC0 1.0 Universal License**, meaning anyone is free to replicate, modify, and distribute the framework for grassroots community organizing and public interest advocacy. 

*Maintained by community advocates.*