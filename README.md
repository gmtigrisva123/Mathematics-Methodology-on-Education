# Visually Impaired Math Education

**A pedagogical research framework for teaching rational numbers to students with visual impairments.**

Developed under the **Math4Money Initiative** - Inclusive Mathematics Education, Vietnam.  
Authors: Lê Trần Khánh Minh · Hồ Việt Anh · Version 1.0 · 2025

---

## Overview

This repository contains the full source for a structured, evidence-informed instructional framework comprising six teaching methodologies and a seven-phase Core Instructional Cycle. The framework is grounded in constructivism, cognitive load theory, dual coding theory, and the gradual release of responsibility model.

See [`docs/ABSTRACT.md`](docs/ABSTRACT.md) for a full summary and [`docs/REFERENCES.md`](docs/REFERENCES.md) for the theoretical bibliography.

---

## Repository Structure

```
visually-impaired-math-education/
│
├── src/                        # All source files
│   ├── index.html              # Entry point — open this in a browser
│   │
│   ├── styles/
│   │   ├── base.css            # Reset, CSS custom properties, typography
│   │   ├── layout.css          # Page wrapper, grids, spacing, footer
│   │   ├── components.css      # Method cards, chips, abstract, lists
│   │   └── sections.css        # Cover, Core Instructional Cycle
│   │
│   ├── sections/               # HTML partials (one per document section)
│   │   ├── cover.html
│   │   ├── abstract.html
│   │   ├── methods.html
│   │   ├── cycle.html
│   │   ├── theory.html
│   │   └── footer.html
│   │
│   └── js/
│       └── main.js             # Reserved — no runtime behaviour in v1.0
│
└── docs/
    ├── ABSTRACT.md             # Plain-text abstract
    ├── REFERENCES.md           # Full theoretical bibliography
    └── METHODOLOGY_OVERVIEW.md # Quick-reference summary of all six methods
```

---

## Getting Started

No build step required. Open `src/index.html` directly in any modern browser.

```bash
git clone https://github.com/gmtigrisva123/Mathematics-Methodology-on-Education.git
cd Mathematics-Methodology-on-Education
open src/index.html
```

---

## The Six Methodologies

| Code  | Name                                    | Core Mechanism                        |
|-------|-----------------------------------------|---------------------------------------|
| MSCM  | Multi-Sensory Conceptualisation Method  | Tactile + auditory + verbal encoding  |
| SWEM  | Structured Worked Example Method        | Explicit step-by-step modelling       |
| GIT   | Guided-to-Independent Transition        | Gradual release of responsibility     |
| VCE   | Verbalisation and Cognitive Encoding    | Oral reconstruction of solutions      |
| EBLM  | Error-Based Learning Method             | Diagnosis of intentional errors       |
| CM    | Contextualisation Method                | Real-world situational embedding      |

---

## Licence

© 2025 Lê Trần Khánh Minh · Hồ Việt Anh · Math4Money Initiative. All rights reserved.
