# phenotypic-memory-in-QS
ODE-based modeling of phenotypic memory in bacterial quorum sensing, capturing activation dynamics under environmental stress.
This repository contains a minimal implementation of the core models and simulations from the study:  
👉 [PLOS Computational Biology (2024)](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1011696)

---

## Overview

Bacterial populations often coordinate collective behaviors using quorum sensing (QS), a density-dependent signaling mechanism. This project models how cells previously exposed to high cell density can exhibit an enhanced response due to the carry-over of signaling molecules from the QS-active (ON) state. This effect, known as phenotypic memory, arises from sustained cellular states rather than genetic changes.

Such memory can enhance responsiveness under dynamic or stressful conditions, such as antibiotic exposure, and may influence survival outcomes at the population level.


We explore:
- **Numerical models** based on ordinary differential equations (ODEs)
- **Analytical modeling** to generalize results and identify cellular parameters influencing memory

---

## Code Contents

- `phenotypic_memory_qs.ipnb` / notebook – Simulates QS activation and memory decay
- Reusable functions – For steady-state analysis, parameter sweeps, and memory zone detection
- **Key plots only** – ON/OFF transitions, decay rates, and memory zone

> **Note:** Full results and complete plot set are available in the original publication.

---

## Setup

Clone the repository and install dependencies with:

```bash
pip install -r requirements.txt

