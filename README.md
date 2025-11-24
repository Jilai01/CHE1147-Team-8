# CHE1147-Team-8
Term project analyzing EAF steelmaking with machine learning techniques.

## Repo Description
Breakdown:
- `raw_data/` -> contains raw data from Kaggle (https://www.kaggle.com/datasets/yuriykatser/industrial-data-from-the-arc-furnace) stored here with Github large file storage (LFS).
- `preprocessed_data/` -> contains csv of preprocessed data which is an input to the EAF energy supervised learning model.
- `graveyard/` -> backup of old and/or local copies of files from early in the term

Running Code:
1. After cloning the repo, running 'EAF_data_preprocess_EDA.ipynb' is the notebook that contains pre-processing of the data, and EDA figures are generated. At the end of the notebook, data is merged into a single feature matrix which can optionally be saved. This file is the 'design_matrix_ver_1' file which has been saved in the 'preprocessed_data/' folder.
2. The 'EAF_Supervised_Learning.ipynb' notebook contains code related to training and assessing the various SL models described in the final report.

## Setup
For continuity with the other deliverables and lessons in CHE1147, the code runs in an environment based on the CHE1147 environment, and modified for this project. (CHE1147 Repo: https://github.com/AI4ChemS/CHE1147/tree/main)

Reproduce:

`conda env create -f environment.yml`

`conda activate che1147`
