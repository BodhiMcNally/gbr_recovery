# 🪸 Assessing Coral Recovery and Reassembly in the Great Barrier Reef

**Course:** STAT3926: Statistical Consulting  
**Author:** Bodhi McNally  
**Client:** Dr. Ana Paula da Silva  
**Date Published:** June 3, 2024

---

## 📌 Overview

This statistical consulting project investigates the **recovery** and **reassembly** processes of coral reef communities in the Great Barrier Reef (GBR) following ecological disturbances. Using similarity metrics and regression modelling, the project explores how coral morphologies and environmental conditions impact the recovery and structural reassembly of reef ecosystems.

---

## 🎯 Project Objectives

- Analyse recovery times of coral morphologies across regions and shelf positions.
- Determine whether successful recovery also results in reassembly of original community structure.
- Evaluate environmental and spatial predictors of successful reassembly.
- Identify morphological drivers influencing reassembly success.
- Forecast future coral cover disturbances using sea surface temperature (SST) under climate scenarios.

---

## 🧪 Methodology

### 🪸 Recovery & Reassembly Analysis
- Coral cover was tracked year-on-year by morphology.
- **Recovery** was defined as a return to pre-disturbance coral cover.
- **Bray–Curtis similarity** was used to measure how similar the post-disturbance community was to its original state.

### 📈 Statistical Modelling
- **Wilcoxon Rank Sum Test** assessed the effects of region, shelf, and morphology on recovery times.
- **Logistic Regression** analysed predictors of successful reassembly.
- **Generalised Additive Model (GAM)** explored nonlinear effects of SST on coral disturbances.
- Model selection included AIC and BIC comparisons for best fit.

---

## 📊 Key Results

- **Median Recovery Time:** 1 year across all morphologies.
- **Reassembly Success Rate:** 83% overall, higher in southern GBR regions.
- No significant predictors of successful reassembly were found in logistic models.
- SST disturbances are expected to increase, especially under the **RCP 8.5** climate scenario.
- GAM models explained more variance (21%) than linear models (12.75%).

---

## ⚠️ Limitations

- Morphological (not species-level) data limits ecological resolution.
- Other stressors (e.g. overfishing, acidification) not included.
- Broad-scale analysis may overlook local reef dynamics.
- No biotic interdependence modelling (e.g. fish populations, algae).

---

