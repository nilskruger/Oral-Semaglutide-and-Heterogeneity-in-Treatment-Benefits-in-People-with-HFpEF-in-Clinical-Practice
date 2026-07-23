# Oral-Semaglutide-and-Heterogeneity-in-Treatment-Benefits-in-People-with-HFpEF-in-Clinical-Practice

# Supplementary Analysis Code

This repository contains illustrative code related to the study comparing **oral semaglutide and sitagliptin in people with heart failure with preserved ejection fraction (HFpEF)**, as registered under:

**ClinicalTrials.gov IDs**: [NCT07390110](https://clinicaltrials.gov/ct2/show/NCT07390110)

---

## 🧪 About the Analysis

The primary analyses were conducted on the **Aetion Evidence Platform**, a validated system for generating regulatory-grade real-world evidence and trial emulations. This platform has been rigorously benchmarked against FDA Sentinel workflows and validated in the RCT-DUPLICATE initiative.

The code provided here is **not sufficient to replicate study results**, as it:
- Does **not include source data** (due to privacy restrictions)
- Supplements the Aetion-based analysis by illustrating:
  - Post-processing steps
  - Plotting of outputs
  - Follow-up time summaries
  - Covariate balance visualization

---

## 📁 Contents

| Script | Purpose |
|--------|---------|
| `Overlap_weights_covariate_balance.ipynb` | Visualizes covariate balance and calculates effective sample size (ESS) using overlap weights. |
| `Cumulative_Incidence_Curve.ipynb` | Plots cumulative incidence curves from weighted outputs. |
| `Forest_plots.ipynb` | Generates forest plots from summary tables of treatment effects. |
| `Mean_FUP.ipynb` | Summarizes mean and median follow-up time, using weighted and unweighted methods. |

---

## 📦 Dependencies

These scripts require:

- `pandas`
- `numpy`
- `matplotlib`
- `lifelines`
- `seaborn`

Install via:

```bash
pip install -r requirements.txt
