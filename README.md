## What is this PGMP_v1?

<img src="https://github.com/Amincheminfom/PGMP_v1/blob/main/PGMP_logo.jpg?raw=1" alt="pDILI Logo" width="250" align="right"/>

**PGMP_v1** is an online tool hosted on Google Colab [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1olKS2e1Z27vD-0cwTz8DEgV4a--Ur27D#scrollTo=56oA9WQHE1_d) that predict the peroxisome proliferator-activated receptor gamma (PPAR-gamma) modulatory property (1 = Active, 0 = Inactive) of a small molecule and also visualize the molecule.

PGMP stands fro **P**PAR-**G**amma **M**odulator(s) **P**redictor.

This Google Colab notebook is a supplementary material of the article "PPARγ modulator predictor (PGMP_v1): chemical space exploration and computational insights for enhanced type 2 diabetes mellitus management" (https://doi.org/10.1007/s11030-025-11118-5).

---
Please follow these three steps before running this notebook.

1: Download the two csv files provided herewith (named 'PGMPv1_Train.csv' and 'PGMPv1_Test.csv') and create a folder named "PGMP_v1_datasets". Move these two csv files in to the folder **PGMP_v1_datasets**.

or Download the folder named "PGMP_v1_datasets" [Directly Download](https://drive.google.com/drive/folders/1jL34B1yuN6UlADfpmmMXDW7WFXBqlW6S?usp=sharing).

2: Upload this folder (**PGMP_v1_datasets**) in your Google Drive. Copy this path. Make sure that 'PGMPv1_Train.csv' and 'PGMPv1_Test.csv' are present in that folder **PGMP_v1_datasets**.

3: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1olKS2e1Z27vD-0cwTz8DEgV4a--Ur27D#scrollTo=56oA9WQHE1_d) and execute it to predict the PPAR-gamma modulatory property of the query molecule as well as visualize the molecule.

---
Example Smiles:

(a) PPAR-g Inactive/CHEMBL465746: COc1ccc(NC(=S)NS(=O)(=O)c2ccc(CCNS(=O)(=O)c3ccccc3)cc2)cc1

(b) Known PPAR-g Active/CHEMBL3695901: Cc1c(C)n(Cc2ccc(-c3ccccc3)cc2)c2ccc(C(=O)NC(C)(C)c3ccc(Br)cc3)cc12

(c) Imatinib: Cc1ccc(NC(=O)c2ccc(CN3CCN(C)CC3)cc2)cc1Nc1nccc(-c2cccnc2)n1

---
Bugs: If you encounter any bugs, please report the issue to [Dr. Sk. Abdul Amin](mailto:pharmacist.amin@gmail.com).
