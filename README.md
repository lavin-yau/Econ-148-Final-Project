# ECON 148 Project

This repository contains a Jupyter notebook replication of *The Fake News Effect*
(Thaler, 2024).

## Run Locally

Install dependencies once:

```bash
pip install -r requirements.txt
```

Then open `ECON148_Project.ipynb` in Jupyter.

The notebook can load data in either of two ways:

- Upload `cleaned_data.csv` with the notebook's file picker.
- Place `cleaned_data.csv` in the same folder as the notebook.

## Binder

Binder will install packages from `requirements.txt`. Because `cleaned_data.csv` is
ignored by Git, upload it inside the notebook after Binder starts unless you later
decide the dataset can be committed to the repository.
