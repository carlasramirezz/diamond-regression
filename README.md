# Diamond Regression Project (March-April 2023)

# Overview
This project uses multiple linear regression to analyse which diamond attributes most strongly influence price. The goal is to build an interpretable model, clean the dataset appropriately, and translate coefficients into commercially meaningful insights.

# Files in this repo
RegressionProject.ipynb — full analysis and model build (created in Google Colab)

diamond_datarevised.csv — dataset used by the notebook

# What I did
Explored the dataset to understand distributions and relationships

Cleaned the data (handled missing values and removed/adjusted variables as needed)

Built a regression model to estimate the impact of diamond characteristics on price

Interpreted coefficients to identify the strongest pricing drivers

# Key takeaways

Carat is the dominant driver of price, with the largest positive effect

Quality factors (e.g., cut/clarity/color depending on encoding) add incremental value beyond size

Model interpretation highlights which features have meaningful marginal impact once others are controlled for

# Tools

Python

pandas, numpy

scikit-learn

Google Colab

# Running the notebook

This notebook was developed in Google Colab, so it loads the dataset using a Colab path:

df = pd.read_csv("/content/diamond_datarevised.csv")

If you’re running locally (or directly after cloning the repo), change it to a relative path (assuming the CSV is in the same folder as the notebook):

df = pd.read_csv("diamond_datarevised.csv")

# Notes for reviewers

All analysis steps, modelling decisions, and interpretation are documented within the notebook for transparency and reproducibility.
