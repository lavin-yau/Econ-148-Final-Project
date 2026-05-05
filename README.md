# ECON 148 Project

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lavin-yau/Econ-148-Final-Project/main?urlpath=lab/tree/ECON148_Project.ipynb)

This repository contains a Jupyter notebook replication of the research paper *The Fake News Effect*
(Thaler, 2024).

## Run in Binder

Launch this project in Binder:

[https://mybinder.org/v2/gh/lavin-yau/Econ-148-Final-Project/main?urlpath=lab/tree/ECON148_Project.ipynb](https://mybinder.org/v2/gh/lavin-yau/Econ-148-Final-Project/main?urlpath=lab/tree/ECON148_Project.ipynb)

Binder installs the required packages from `requirements.txt` and opens the
Jupyter notebook directly with a prebuilt environment. The cleaned dataset, `data/cleaned_data.csv`, is
included in this repository, so users can run all notebook cells without
uploading data.

Recommended workflow:

1. Click the Binder badge or link above.
2. Wait for Binder to build the environment.
3. Open `ECON148_Project.ipynb` if it does not open automatically.
4. Select `Run` > `Run All Cells`.
5. Figures will be saved to figures folder.

## Run Locally with Jupyter Notebook

Download or clone this repository, then open a terminal in the project folder.

Install the required packages:

```bash
pip install -r requirements.txt
```

If the classic notebook interface is not installed, install it:

```bash
pip install notebook
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

In the browser window that opens, select `ECON148_Project.ipynb`, then choose
`Run` > `Run All Cells`. The notebook loads the dataset from
`data/cleaned_data.csv` and saves generated figures to the `figures/` folder.
