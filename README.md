# Chondrosarcoma Drug Discovery (2026): In Silico Structure-Based Virtual Screening Pipeline

[![GitHub Pages Deployment](https://github.com/ht2905/chondrosarcoma-drug-discovery-2026/actions/workflows/deploy-pages.yml/badge.svg)](https://github.com/ht2905/chondrosarcoma-drug-discovery-2026/actions/workflows/deploy-pages.yml)
[![Hosted Presentation](https://img.shields.io/badge/Hosted%20Presentation-GitHub%20Pages-blue)](https://ht2905.github.io/chondrosarcoma-drug-discovery-2026/)
[![Format](https://img.shields.io/badge/Deck%20Format-Standalone%20Reveal.js-emerald)](https://ht2905.github.io/chondrosarcoma-drug-discovery-2026/)

---

## Table of Contents

- [1. Project Overview & Scope](#1-project-overview--scope)
- [2. Interactive Presentation Deck](#2-interactive-presentation-deck)
  - [2.1 Live Web Access](#21-live-web-access)
  - [2.2 Local Offline Viewing](#22-local-offline-viewing)
  - [2.3 Navigation Keyboard Shortcuts](#23-navigation-keyboard-shortcuts)
- [3. Research Pillars](#3-research-pillars)
- [4. Repository Structure](#4-repository-structure)
- [5. Automated CI/CD & Deployment](#5-automated-cicd--deployment)
- [6. Citation & Inquiries](#6-citation--inquiries)

---

## 1. Project Overview & Scope

Chondrosarcoma is a cartilaginous bone malignancy characterized by severe intrinsic resistance to conventional chemotherapeutics and ionizing radiation. This repository hosts the distribution artifacts and research presentation for an *in silico* structure-based drug discovery program investigating computational virtual screening strategies to overcome these therapeutic barriers.

> [!NOTE]
> **Proprietary Research Notice:**
> To protect project intellectual property and prevent automated text scraping of unpublished therapeutic targets, active-site coordinates, and proprietary screening algorithms, detailed biochemical protocols and numerical screening cutoffs are intentionally omitted from plain-text repository markdown. Complete scientific rationales, structural models, docking quality gates, and multi-phase validation roadmaps are compiled into the interactive presentation deck for research evaluators and human collaborators.

---

## 2. Interactive Presentation Deck

### 2.1 Live Web Access

The full research proposal slide deck is hosted and viewable via GitHub Pages:

- **Hosted URL:** [https://ht2905.github.io/chondrosarcoma-drug-discovery-2026/](https://ht2905.github.io/chondrosarcoma-drug-discovery-2026/)

### 2.2 Local Offline Viewing

The presentation artifact [index.html](index.html) is fully self-contained (`embed-resources: true`). All JavaScript engines, typography, styles, vector charts, and high-resolution visual data assets are base64-encoded into a single document:

1. Clone or download this repository.
2. Open `index.html` in any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Apple Safari).
3. No local web server, runtime installation, or active internet connection is required.

### 2.3 Navigation Keyboard Shortcuts

| Key | Action |
| :--- | :--- |
| **Right Arrow** / **Space** / **PageDown** | Advance to next slide |
| **Left Arrow** / **PageUp** | Return to previous slide |
| **F** | Toggle full-screen mode |
| **S** | Open speaker notes console |
| **M** | Toggle slide navigation menu |
| **O** / **Esc** | Toggle slide overview grid |
| **Home** / **End** | Jump to first / last slide |

---

## 3. Research Pillars

The computational drug discovery pipeline encompasses five distinct investigative phases presented within the deck:

- **Target Structural Modeling:** Quaternary structural characterization and catalytic pocket definition for candidate chondrosarcoma vulnerability targets.
- **Therapeutic Compound Curation:** Multi-conformer chemical library standardization encompassing small-molecule drug libraries across drug-like and extended chemical space.
- **Structure-Based Virtual Screening:** Multi-engine molecular docking protocols coupled with crystallographic re-docking quality gates and machine learning scoring.
- **Interaction Fingerprinting & ADMET Triage:** Detailed atomic contact profiling, toxicophore identification, and pharmacokinetic filtering.
- **Dynamic Stability Validation:** Explicit-solvent all-atom molecular dynamics trajectories and binding free energy estimation.

---

## 4. Repository Structure

```text
chondrosarcoma-drug-discovery-2026/
├── .github/
│   └── workflows/
│       └── deploy-pages.yml     # Automated GitHub Pages CI/CD deployment
├── research-papers/             # Primary literature corpus & reference publications
├── .gitignore                   # Git exclusion rules
├── index.html                   # Standalone compiled interactive presentation deck
└── README.md                    # Project distribution documentation
```

---

## 5. Automated CI/CD & Deployment

Slide distributions are maintained through GitHub Actions (`.github/workflows/deploy-pages.yml`):

- **Zero-Build Deployment:** Slides are pre-compiled and packaged into an isolated deployment artifact with `.nojekyll` routing.
- **Dual Pipeline:** Synchronizes to both the `gh-pages` branch and GitHub Actions Pages infrastructure.
- **Turnaround:** Under 15-second deterministic deployment upon updates.

---

## 6. Citation & Inquiries

Author: Hoang Q. Tran | In Silico Pharmacology & Biotechnology  
For technical inquiries or collaboration requests, please consult the presentation deck or contact the project team.
