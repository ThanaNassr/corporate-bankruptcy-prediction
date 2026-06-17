# Bankruptcy Prediction Dissertation
Machine learning models for corporate bankruptcy prediction using Compustat financial data and U.S. Federal Judicial Center bankruptcy filings.

This repository contains the code, analysis, and documentation for my dissertation on corporate bankruptcy prediction using machine learning.

## Overview

The project combines:

* Compustat Fundamentals Annual financial statement data
* Federal Judicial Center (FJC) bankruptcy filings
* Machine learning classification models

The objective is to predict whether a firm will file for bankruptcy within the following year using accounting and financial indicators.

## Data

The underlying datasets are not included in this repository due to licensing and data usage restrictions.

Sources include:

* Compustat Fundamentals Annual
* Federal Judicial Center (FJC) Bankruptcy Database

## Project Structure

```text
.
├── analysis.ipynb
├── src/
├── data/          # ignored
├── outputs/       # ignored
├── models/        # ignored
└── README.md
```

## Methodology

* Time-based train/test split
* Bankruptcy prediction horizon of one year
* Class imbalance handled using class-weighted models
* Evaluation using ROC-AUC, PR-AUC, precision, recall, and confusion matrices

## Author

MSc Dissertation Project
