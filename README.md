# IPD Meta-Analysis Pro

**Browser-based Individual Participant Data meta-analysis with one-stage/two-stage models, survival analysis, and network meta-analysis.**

## Quick Start
1. Open `ipd-meta-pro.html` in Chrome, Firefox, or Edge
2. Import IPD data (CSV/Excel) or load a demo dataset
3. Configure model (Fixed/Random, DL/REML/PM, HKSJ)
4. Run Analysis

No installation required.

## Features
- **One-stage IPD analysis** (mixed-effects logistic/Cox)
- **Two-stage IPD analysis** (study-level pooling)
- **Survival analysis** (Kaplan-Meier, Cox, hazard ratio pooling)
- **7 tau-squared estimators** (DL, REML, PM, ML, HS, HE, EB)
- **HKSJ adjustment** with proper t-distribution
- **Network meta-analysis** (pairwise comparison)
- **Meta-regression** (patient-level and study-level covariates)
- **Influence diagnostics** (leave-one-out, Cook's distance)
- **WebR in-browser validation** (metafor::rma REML)
- **Export**: PDF, Excel, R/Stata/SAS code, TruthCert bundle
- **Seeded PRNG** (xoshiro128**) for reproducibility

## Validation
R parity gate: metafor v4.8-0, meta, survival, lme4

## Citation
> Ahmad M, et al. IPD Meta-Analysis Pro: a browser-based platform for individual participant data meta-analysis. *F1000Research*. 2026. [DOI pending]

## License
MIT
