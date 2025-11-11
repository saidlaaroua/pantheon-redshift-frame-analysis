# pantheon-redshift-frame-analysis
Pantheon-redshift-frame-analysis
# Pantheon+ / SH0ES Redshift-Frame Analysis
Reproduction repository for the paper  
**“Full-sky covariance-weighted redshift-frame consistency in the Pantheon+ Type Ia supernova sample”**  
(Submitted to *Physical Review D*, 2025)

---

## Overview
This repository reproduces all numerical results and figures from the paper.  
The analysis quantifies systematic offsets between heliocentric and CMB redshift frames in the Pantheon+ Type Ia supernova dataset and measures the resulting frame dependence of the Hubble constant.

---

## Contents
| File | Description |
|------|--------------|
| `analyze_redshift_dependence.py` | Main analysis script (runs end-to-end). |
| `Pantheon_SH0ES_data.csv` | Supernova data (deduplicated sample). |
| `Pantheon_SH0ES_STAT_SYS.csv` | Flattened STAT+SYS covariance matrix. |
| `pantheon_redshift_systematics_final.png` | Final four-panel figure produced by the script. |

---

## Requirements
Python ≥ 3.10 with  
`numpy`, `pandas`, `scipy`, `matplotlib`.

Install in Colab or locally:
```bash
pip install numpy pandas scipy matplotlib
