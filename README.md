# Station Choice Modeling for Public Transportation
> **Project of Module Business Analytics | RWTH Aachen University**

This repository contains the source code and datasets for modeling public transportation station choices, developed as part of the Business Analytics module.

---
Before running the project, please install the required libraries: biogeme, gamspy, pandas and numpy

## How to Run the Project
1. Run **`datagen.ipynb`** first to generate the necessary `dataset_output.xlsx` file.
2. Open and execute **`Biogeme.ipynb`** to view the estimated coefficients. *Note: Ensure this notebook and `dataset_output.xlsx` are saved in the same directory before running.*
3. Execute **`Gamspy.ipynb`**. The estimated coefficients from the Biogeme step have already been hardcoded at the beginning of this file. Running it will output the optimized station choices along with the total transit share.

---

## Authors
*Students of BSc. Wirtschaftsmathematik at RWTH Aachen University:*
* **Thi Vien Phuong Do**
* **Kaiyu Liu**
* **Susanna Minasian**
