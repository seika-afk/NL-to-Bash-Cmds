# Data Preprocessing for Neural Machine Translation (NMT)

This repository contains the initial steps for preparing data for a NL to Bash cmds.  
The work primarily focuses on text preprocessing, tokenization, and preparation for sequence-to-sequence models.

---
## Note :
Work is still Undergoing .
The completed steps are given below.

- Data ingestion
- Data Preprocessing


## Contents

- **`Datapreprocessing.ipynb`**  
  A Jupyter Notebook that includes:
  - Data loading
  - Text normalization and cleaning
  - Tokenization
  - Sequence padding
  - Handling masks for zero-padding (`mask_zero=True` in embedding layer)
  - Preparation of input and target sequences for training

---

## Requirements

Install the following dependencies before running the notebook:

```bash
pip install tensorflow keras numpy pandas
