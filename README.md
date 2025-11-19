# Assignment-03-Ensemble-Methods-Comparison
Project Overview(Finance Industry Focus)

This project applies ensemble learning methods to predict whether a company’s stock in the S&P 500 will close higher or lower on June 30, 2025. Using short-term market indicators from June 26 and June 27, the project compares three supervised learning approaches:

A baseline Decision Tree

A Random Forest (bagging ensemble)

Gradient Boosting (boosting ensemble)

The goal is to evaluate how ensemble methods improve prediction accuracy, stability, and generalization compared to a single decision tree, while also interpreting feature importance and business relevance.

Objectives

Build and evaluate three models: Decision Tree, Random Forest, and Gradient Boosting.

Compare model performance using accuracy, precision, recall, and F1-score.

Analyze feature importance rankings across methods.

Translate technical findings into practical business meaning.

Reflect on model differences and the advantages of ensemble learning.

Dataset

The dataset contains daily trading data for 503 S&P 500 companies across the first half of 2025.
Features used in this project include:

Daily price change (June 26 and June 27)

Percent change (June 26 and June 27)

Trading volume (June 26 and June 27)

The target variable, price_up, indicates whether a stock closed higher on June 30 compared to its opening price.

Notebook Structure
Section 1 – Data Preparation

Loads the dataset, engineers features, and creates the target variable. Includes an 80/20 stratified train–test split.

Section 2 – Model Building

Trains:

A single Decision Tree (baseline)

A Random Forest (200 trees)

A Gradient Boosting Classifier (200 estimators)

Evaluates each model using accuracy, precision, recall, and F1-score.

Section 3 – Understanding the Methods

Explains the conceptual differences between bagging, boosting, and standalone trees, and when each should be used in practice.

Section 4 – Business Impact

Interprets model improvements and their relevance to short-term market prediction and risk-aware decision-making.

Section 5 – Feature Importance

Presents feature importance rankings for each model and discusses practical insights about price movement and trading activity.

Section 6 – Reflection

Summarizes lessons learned about ensemble learning, interpretability trade-offs, and practical financial analytics.

Key Findings

Gradient Boosting achieved the strongest overall accuracy, showing its ability to correct residual errors and capture subtle signals.

Random Forest delivered stable, well-balanced performance, reducing variance and overfitting compared to a single tree.

Percent change and trading volume consistently ranked as the most predictive features across models.

Ensembles provided meaningful performance gains, demonstrating why they are widely used in real-world financial modeling.
