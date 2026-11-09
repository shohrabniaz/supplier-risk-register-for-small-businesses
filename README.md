# Supplier Risk Register for Small Businesses

**Author:** Md Shohrab Hossen Niaz  
**Focus:** general  
**Visibility guidance:** public-ok

## Overview

Third-party/supplier cyber-adjacent risk register.

## Research questions

1. What business problem does “Supplier Risk Register for Small Businesses” solve for an SME or partner organisation?
2. Which artefacts demonstrate a credible, implementable solution?
3. How is success measured without overstating lab or synthetic evidence?

## Deliverables

- problem framing
- solution design
- evaluation plan
- Report and presentation (`Final_Submission/`)
- Evaluation scorecard (`02_Evaluation/`)
- Design notes (`01_Design/`)
- Baseline evidence JSON (`evidence/`)

## Repository layout

```
01_Design/           Design and method notes
02_Evaluation/       Scorecard workbook
evidence/            Baseline evidence model
Final_Submission/    Report, slides, appendices
```

## Limits

Synthetic or laboratory baselines are labelled. No production tenant secrets. Where a topic could imply offensive techniques, this pack stays defensive and high-level.

**GitHub:** `supplier-risk-register-for-small-businesses`


## Run the automation

Working code is in `src/`. Sample inputs are in `data/`. Results write to `output/`.

```powershell
.\automation\run.ps1
```

Manual:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
python -m src.cli run
python tests\test_smoke.py
```

Domain engine kind: `general`.

**Author:** Md Shohrab Hossen Niaz  
**GitHub:** `supplier-risk-register-for-small-businesses`
