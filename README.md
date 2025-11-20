# 📘 Beyond the Inversion — Structural Yield Curve Analysis

### 🔎 Overview  
This repository contains Beyond the Inversion, an academic project that builds on the structural yield-curve framework of **Smets & Tsatsaronis (1997)**. The original SVAR model—designed to decompose movements in the term spread—has been extended by adding a fifth variable: the Economic Policy Uncertainty (EPU) index, treated as an exogenous shock within the identification scheme.

This extension allows the model to capture a dimension absent from the original framework: the role of uncertainty-driven risk premia, flight-to-safety dynamics, and policy responses that can alter both ends of the yield curve simultaneously
The goal is to provide a more realistic, state-dependent interpretation of the yield curve’s predictive power.

---

## 📘 Project Description  
This repository contains *Beyond the Inversion*, an academic project analyzing the structural origins of the yield curve’s predictive power.  
The model:

- Reproduces the **SVAR identification strategy** of Smets & Tsatsaronis (1997)  
- Adds **EPU** as an exogenous variable  
- Performs **structural decomposition**, **impulse responses**, and **historical analysis**  
- Evaluates when the yield curve issues:  
  - **True positives** (policy-driven inversions)  
  - **False positives** (inflation-driven flattenings)  
  - **False negatives** (uncertainty-driven recessions without inversion)  

A regime-specific probit model further shows that the spread is significantly more predictive in **low-uncertainty regimes**, consistent with the SVAR evidence.

This framework emphasizes that **what drives an inversion matters as much as the inversion itself**.

---

## 📁 Repository Contents
- `BeyondTheInversion.pdf` — Full thesis document  
- Figures and diagnostics (IRFs, variance decompositions, probit output)  
- Documentation and supporting notes  

---

## 📌 Disclaimer  
*This project was developed during my economics degree.  
It may contain simplifications or methodological limitations typical of student work.  
Its purpose is to demonstrate analytical interest, structural thinking, and empirical modeling skills in macro-finance.*

---

## ✍️ Author  
**Enrique Ruiz de Almirón Da Silva**  
Economics — UC3M  
Structural Macro | Yield Curve | SVAR | Quantitative Methods
