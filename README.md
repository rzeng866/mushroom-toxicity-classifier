# mushroom-toxicity-classifier
This project uses supervised machine learning to classify mushrooms as edible or poisonous based on their physical characteristics. Using the UCI Mushroom Dataset, I built and compared multiple classification models—including logistic regression, elastic net, decision tree, and random forest—to evaluate which approach best predicts toxicity.

## 🔍 Summary
- Built classification models in R
- Evaluated performance using ROC AUC (area under curve) and confusion matrix
- Compared model results to identify best fit

## 🚀 How to Run
Open `finalproject.html` to see full report

OR

1. Open `finalproject.Rmd` in RStudio
2. Run all chunks to reproduce results

## 📁 Files
- `Codebook.txt`: Describes all features
- `agaricus-lepiota.data`: UCI Mushroom Dataset
- `finalproject.Rmd`: Source R Markdown file used to generate the report
- `finalproject.html`: Rendered HTML report containing analysis results
-  Files ending in .rda: Saved results from models (to increase efficiency)

## ✅ Results
- Accuracy: 99%
- Elastic Net and Random Forest models performed best

## 🧪 Tools
tidyverse, tidymodels, ggplot2, etc.
