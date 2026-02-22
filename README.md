# GEI1092_Projet1 Sentiment Analysis


## Project Overview
This project builds an AI-based sentiment analysis pipeline for movie reviews using a classical and interpretable approach:
- **Text preprocessing**
- **TF-IDF feature extraction**
- **Logistic Regression** for binary sentiment classification (positive vs negative)

In addition to model performance, the project emphasizes **responsible AI** by including:
- **Carbon footprint tracking** during training (CodeCarbon)
- **Explainability** with **SHAP** (word-level contributions)
- **C++ Embedded deployment insights**, including **fixed-point quantization** and export of model parameters for Arduino-style inference

## Objectives
- Train a binary sentiment classifier on movie reviews
- Evaluate the model using standard classification metrics
- Track training emissions and energy usage
- Explain predictions using SHAP to improve transparency
- Discuss ethics: bias, fairness, and accountability
- Export a quantized version of the model for embedded systems

## Repository Structure
> Adjust file names if needed.

- `Mini_Project1.ipynb` — main notebook (tasks and results)
- `sentiment_model.h` — generated C++ header for embedded inference (Task 10)
- `emissions.csv` — CodeCarbon output (generated after tracking)
- `README.md` — project documentation


## Dataset Download & Preprocessing

### Dataset
This project uses the **IMDb movie reviews dataset** (binary sentiment).  
Download instructions and dataset format are described in the notebook.
Credit Dataset: Andrew L. Maas, Raymond E. Daly, Peter T. Pham, Dan Huang, Andrew Y. Ng, and Christopher Potts. (2011). Learning Word Vectors for Sentiment Analysis. The 49th Annual Meeting of the Association for Computational Linguistics (ACL 2011).

## Setup & Installation

### Requirements
Recommended Python environment:
- Python 3.10+
- scikit-learn
- numpy
- pandas
- matplotlib
- shap
- codecarbon
- (optional) nltk

