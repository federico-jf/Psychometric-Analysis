# Classical Test Theory (CTT) Item Analysis in R  
**A realistic simulation using the `psych` package**  
*Federico Ferrero*

---

## 1. Purpose of this tutorial

This tutorial shows how to simulate a realistic multiple-choice test, conduct a Classical Test Theory (CTT) item analysis, and interpret item-level and test-level statistics using R. The focus is pedagogical: the workflow mirrors what is typically done in operational assessment and evaluation contexts.

---

## 2. Setup

```r
# Clean workspace
rm(list = ls())

# Load required library
library(psych)

# Reproducibility
set.seed(123)
