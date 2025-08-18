# IG Publication Bias 
## Project Context
**Immunogenicity Publication Bias and Its Consequences for Predictive Modelling**
This project accompanies the manuscript "_Immunogenicity Publication Bias and Its Consequences for Predictive Modelling: A Call for Transparent Reporting_". It investigates how publication bias — particularly the underreporting of early-phase clinical trial data with high immunogenicity — skews anti-drug antibody (ADA) incidence data. The R-based simulations in this repository reproduce and extend the findings presented in the paper, including ADA incidence modeling and visualizations across in-house and FDA-approved monoclonal antibody (mAb) datasets. The goal is to promote transparency and improve the reliability of immunogenicity prediction models by providing an openly accessible example.

## 📘 Summary
This project demonstrates the impact of publication bias on the modeling of ADA incidence for therapeutic monoclonal antibodies (mAbs). In particular, it compares ADA data from:
- **In-house Roche Phase I–III studies**, and
- **Published FDA-approved mAb data**,  
to simulate and visualize how ADA-positivity ratios evolve over time under different assumptions about data transparency.

## 📂 Repository Structure
- `Publication_Bias_Final.Rmd`: Source R Markdown (if added).
- `figures/`: Contains exported plots.
- `README.md`: This file.

## 📊 Features
- Simulation of ADA positivity trajectories using a logit-normal model.
- Visualizations of confidence intervals and median trajectories across phases.
- Comparison of ADA dynamics for:
  - Phase I, II, III Roche-internal data
  - FDA-approved monoclonal antibodies
  - Merged in-house simulations
 
## 🧪 Getting Started
1. Clone the repo or download the `.Rmd` file and open in RStudio.
2. Install necessary packages
3. Run the notebook to setup the model and simulations, and reproduce the figures from the manuscript

## 📄 License

## 🧠 Authors
  Sophie Tascedda
  Zicheng Hu
  Hans Peter Grimm
  Linnea C. Franssen

## 📎 Citation
If using this code or its results, please cite the manuscript once published. Preprint DOI or final citation info to be added here.
