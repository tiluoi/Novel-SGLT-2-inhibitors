# Novel-SGLT-2-inhibitors
# Cardiovascular outcomes of novel SGLT2 inhibitors in patients with type 2 diabetes: a network meta-analysis of bexagliflozin, ertugliflozin and sotagliflozin

## 1. Overview
This repository contains the R source code and analytical pipeline used to evaluate the cardiovascular outcomes of novel SGLT2 inhibitors. The project demonstrates a complete workflow for conducting a network meta-analysis, including data wrangling, statistical modeling, and the generation of publication-ready visualizations (e.g., forest plots).

## 2. Publication
The code and methodology in this repository support the findings published in **Diabetes Research and Clinical Practice** (May 2026).
* **Title:** Cardiovascular outcomes of novel SGLT2 inhibitors in patients with type 2 diabetes: a network meta-analysis of bexagliflozin, ertugliflozin and sotagliflozin
* **DOI/Link:** 10.1016/j.diabres.2026.113282

## 3. Repository Structure
To ensure reproducibility, the project is organized as follows:
* `data/`: Contains the aggregated clinical trial data used for the analysis. 
* `scripts/`: Contains the R scripts for the analysis.
* `gifure/`: Output folder containing high-resolution figures (.pdf, .png).

## 4. Prerequisites
The analysis was performed using **R (version 4.5.1)**. To run the scripts, the following R packages are required:
* `netmeta` (for network meta-analysis)
* `meta` (for standard pairwise meta-analysis)
* `dplyr` / `tidyverse` (for data manipulation)
* `ggplot2` (for data visualization)

## 5. Usage
To reproduce the findings:
1. Clone this repository to your local machine.
2. Open the `Novel-SGLT-2-inhibitors.Rproj` file in RStudio.
3. Run the scripts in the `scripts/` folder in numerical order.

## 6. Author
* **Tien-Phat Dao** * **Contact:** dtphat0503@gmail.com
* **Profile:** Pharmacist | MSc. in Public Health
