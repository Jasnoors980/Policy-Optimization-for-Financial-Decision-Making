# Policy Optimization for Financial Decision-Making

**Author:** Jasnoor Singh  
**Dataset:** LendingClub Loan Data (2007–2018)  
**Objective:** Build an end-to-end system that uses Machine Learning and Offline Reinforcement Learning to optimize loan approval decisions and maximize financial returns.

---

## Project Overview

This project builds an intelligent financial decision-making system for loan approvals.  
It involves both **Supervised Learning** and **Offline Reinforcement Learning (RL)** approaches to decide whether to approve or deny a loan, maximizing company profit and minimizing risk.

---

## Key Objectives

1. Perform **Exploratory Data Analysis (EDA)** and preprocessing.  
2. Train a **Deep Learning model (MLP)** to predict loan defaults.  
3. Frame the same task as an **Offline RL problem** with rewards based on profit/loss.  
4. Compare both models by accuracy, F1, AUC, and financial reward metrics.

---
#  How to Run Code

### Step 1 - Ensure you have requirements.txt  
Make sure the `requirements.txt` file is present in your project directory.

---

### Step 2 - Download the Dataset  
Download the **LendingClub Loan Data (2007–2018)** dataset from Kaggle:  
🔗 https://www.kaggle.com/datasets/wordsforthewise/lending-club  

Once downloaded, locate the file:  
`accepted_2007_to_2018Q4.csv.gz`

---

### Step 3 - Download the Project Files  
Ensure that you have the following files in your project folder:  
- `EDA_and_Preprocessing.ipynb`  
- `DeepLearning_model.ipynb`  
- `RL_baseline_agent.ipynb`  
- `Analysis_and_Comparison.ipynb`  
- `main.py`  
- `requirements.txt`

---

### Step 4 - Update Dataset Path  
In the first cell of the notebook **EDA_and_Preprocessing.ipynb**, update the dataset path to where you saved it locally.

---

### Step 5 - Run the Main Script  
This script will:
- `Run all four notebooks in sequence`
- `Perform EDA, preprocessing, model training, and RL policy evaluation`
- `Save all outputs in the data/, models/, and analysis/ folders`

### Step 6 - View Results and Report
After successful execution:
- `Check the generated outputs and metrics in the analysis/ folder`
- `Review the visualizations and model comparisons in the executed notebooks`




