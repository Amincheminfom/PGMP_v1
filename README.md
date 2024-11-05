## What is this PGMP_v1?

**PGMP_v1** is an online tool hosted on Google Colab [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1k-amPhU1Pft8WQn3eKGddSD32aqsOHBa#scrollTo=4SVqxdmO0MQM) that predict the peroxisome proliferator-activated receptor gamma (PPAR-gamma) modulatory property (1 = Active, 0 = Inactive) of a small molecule and also visualize the molecule.

PGMP stands fro **P**PAR-**G**amma **M**odulator(s) **P**redictor.

This Google Colab notebook is a supplementary material of the paper "PPARg Predictor" (link here) and we encourage you to read it before using this pipeline.

---
Please follow these three steps before running this notebook.

1: Download the Folder named "PGMP_v1_datasets" [Download the folder](https://drive.google.com/drive/folders/1jL34B1yuN6UlADfpmmMXDW7WFXBqlW6S?usp=sharing)

2: Upload this folder in your Google Drive.

3: Confirm the presence train and test sets in that folder.

---
Example Smiles:
(a) PPAR-g Inactive/CHEMBL465746: COc1ccc(NC(=S)NS(=O)(=O)c2ccc(CCNS(=O)(=O)c3ccccc3)cc2)cc1
(b) Known PPAR-g Active/CHEMBL3695901: Cc1c(C)n(Cc2ccc(-c3ccccc3)cc2)c2ccc(C(=O)NC(C)(C)c3ccc(Br)cc3)cc12
(c) Imatinib: Cc1ccc(NC(=O)c2ccc(CN3CCN(C)CC3)cc2)cc1Nc1nccc(-c2cccnc2)n1

---
Bugs: If you encounter any bugs, please report the issue to [my mail id](mailto:pharmacist.amin@gmail.com).
