# Mermaid Diagrams — ESG Project
## How to use: Go to https://mermaid.live → paste each chart code → Export as PNG → insert into slides

---

## CHART 1 — Job Market Analysis: ESG Skills Demand
### Use on: Slide 6 (Akshat)

```mermaid
xychart-beta horizontal
    title "ESG Competency Demand in 24 Job Postings (%)"
    x-axis ["ESG Reporting (GRI/CSRD)", "ESG Data & Metrics", "Materiality Assessment", "Stakeholder Comms", "Climate Risk (TCFD)", "Supply Chain ESG", "Sustainability Strategy", "Corporate Governance"]
    y-axis "% of Job Postings" 0 --> 100
    bar [83, 71, 63, 58, 54, 46, 42, 38]
```

---

## CHART 2 — Alumni Survey Results
### Use on: Slide 7 (Akshat)

```mermaid
pie title "Alumni: Was ESG adequately covered in your degree? (n=47)"
    "Not adequately covered" : 42
    "Not covered at all" : 29
    "Somewhat covered" : 20
    "Well covered" : 9
```

---

## CHART 3 — ESG Skills Map (Gap Analysis)
### Use on: Slide 10 (Anmol) — THIS IS THE MOST IMPORTANT CHART

```mermaid
xychart-beta
    title "ESG Skills Gap: Employer Expectation vs HS Fresenius Coverage (0-5 scale)"
    x-axis ["ESG Reporting", "ESG Data", "Materiality", "Climate Risk", "Supply Chain", "Stakeholder Comms", "Governance", "Strategy"]
    y-axis "Score out of 5" 0 --> 5
    bar [4.8, 4.5, 4.2, 3.9, 3.7, 4.0, 3.8, 4.1]
    line [2.1, 2.3, 1.8, 1.5, 1.2, 3.2, 3.0, 3.5]
```

> Note: Blue bars = Employer Expectation. Orange line = HS Fresenius Coverage. The wider the gap between bar and line, the bigger the problem.

---

## CHART 4 — Sector Comparison
### Use on: Slide 13 (Anmol)

```mermaid
xychart-beta
    title "ESG Skill Urgency by Sector (1-5 scale)"
    x-axis ["Finance", "Consulting", "Sustainability", "Marketing", "Management"]
    y-axis "Urgency Score" 0 --> 5
    bar [4.9, 4.7, 4.8, 3.9, 3.7]
```

---

## DIAGRAM 5 — Three-Tier Competency Framework
### Use on: Slide 5 (Akshat) — Use as a visual pyramid/ladder

```mermaid
graph TD
    T3["🏆 TIER 3 — STRATEGIC
    Sustainability Strategy
    ESG Risk Integration
    Board-Level Governance
    Stakeholder Engagement"]

    T2["⚙️ TIER 2 — APPLIED TECHNICAL
    GRI Reporting
    CSRD/ESRS Compliance
    TCFD Frameworks
    Materiality Assessment
    ESG Data & Metrics
    Supply Chain Due Diligence"]

    T1["📚 TIER 1 — FOUNDATIONAL
    ESG Literacy
    Framework Awareness (GRI, TCFD, SDGs)
    Corporate Governance Basics
    Sustainability Concepts"]

    T1 --> T2 --> T3

    style T1 fill:#d4edda,stroke:#28a745,color:#000
    style T2 fill:#fff3cd,stroke:#ffc107,color:#000
    style T3 fill:#f8d7da,stroke:#dc3545,color:#000
```

> Label the gap arrow: "Most graduates stop here ↑" pointing at Tier 1/Tier 2 boundary
> Label the target arrow: "Employers expect this ↑" pointing at Tier 2

---

## DIAGRAM 6 — Research Methodology Flow
### Use on: Slide 4 (Akshat)

```mermaid
flowchart LR
    A["📋 Alumni Survey
    n=47
    LinkedIn + Alumni Network"] --> E["ESG Skills Gap
    Analysis"]
    B["🎙️ Corporate Interviews
    n=4
    Industry Partners"] --> E
    C["💼 Job Market Analysis
    n=24 postings
    LinkedIn · Xing · StepStone"] --> E
    D["📚 Curriculum Review
    HS Fresenius Modules
    vs. Employer Demands"] --> E
    E --> F["5 Curriculum
    Recommendations
    for HS Fresenius"]

    style A fill:#e3f2fd,stroke:#1565c0,color:#000
    style B fill:#e3f2fd,stroke:#1565c0,color:#000
    style C fill:#e3f2fd,stroke:#1565c0,color:#000
    style D fill:#e3f2fd,stroke:#1565c0,color:#000
    style E fill:#fff9c4,stroke:#f9a825,color:#000
    style F fill:#e8f5e9,stroke:#2e7d32,color:#000
```

---

## TIPS FOR USING THESE IN SLIDES

1. Go to **mermaid.live**
2. Paste the code block (everything between the triple backticks)
3. Click the PNG download button (top right)
4. Insert into Google Slides or PowerPoint

**Chart 3 (Skills Gap) is the most important** — make it full-slide and large.
Chart 1 (Job postings) and Chart 2 (Alumni pie) support Akshat's section.
Diagrams 5 and 6 are for the methodology and framework slides.
