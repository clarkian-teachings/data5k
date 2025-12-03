# DATA 5K — Colab-Compatible Teaching Notebooks

This repository contains **updated, Colab-compatible versions** of the weekly
notebooks used in DATA5000. These materials are provided **solely as
supplementary teaching support**, ensuring they run smoothly under **Google
Colab’s current Python runtime (Python 3.12, as of 3 December 2025)**.

The goal of this repository is to provide:
- reliable in-class demonstration notebooks  
- clean, reproducible examples for students  
- fixes for library, import, and dependency issues arising from Colab updates  
- a consistent structure that can be used across teaching weeks  

These notebooks **do not replace** the official materials hosted on MyKBS.

---

## ⚖️ Source and Licence

These notebooks are adapted from the open-source repository:  
https://github.com/data-5000/data5000

The upstream materials were released under the **MIT Licence**, which permits
copying, modification, redistribution, and reuse.

**Source material © data-5000/data5000 (MIT Licence).**  
**Modifications © 2025 Iain J. Clark.**  

All modified content in this repository is also provided under the MIT Licence.

No assessment materials or Kaplan-owned documents are included.

---

## 📁 Repository Structure

```
data5k/
├── week_00/        # Compatibility checks (Week 0)
├── week_01/
├── week_02/
├── week_03/
├── ...
├── week_12/
├── README.md
└── LICENSE
```

## 🧪 A detailed breakdown:

- **week_00**  
  Contains a “Week 0 Compatibility Checker” notebook designed for instructors to
  verify import compatibility and basic execution before teaching weeks begin.

  It will verify:
  - Python version  
  - pandas, numpy, sklearn, matplotlib versions  
  - import compatibility  
  - basic functionality of common methods  
  - first-cell execution for each weekly notebook  

  This ensures that **all teaching notebooks run cleanly before Week 1**.

- **week_01 → week_12**  
  Contains the weekly teaching notebooks, updated for Colab compatibility.

---

## 🎯 Purpose and Pedagogical Intent

This repository exists to:

- stabilise the technical side of DATA5000  
- support teaching workflows with reproducible code  
- minimise Colab version mismatches  
- help students focus on learning, not debugging  
- promote high-quality, industry-aligned data science pedagogy  

It is intended for **educational use only**.

---