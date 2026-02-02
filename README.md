# US Medical Insurance Cost Data Analysis

## 📌 Project Overview
This project performs a comprehensive exploratory data analysis (EDA) on a dataset of U.S. Medical Insurance costs. As part of the **Codecademy Data Scientist: Machine Learning Career Path**, this analysis focuses on investigating patient demographics and identifying key factors that contribute to insurance premiums.

The primary goal was to build a robust analytical toolset using **pure Python** (no external libraries like Pandas) to parse, clean, and analyze real-world data.

## 🎯 Research Questions
The analysis seeks to answer the following questions:
* What is the average age of the patients?
* How is gender distributed within the dataset?
* Which geographical regions are represented?
* What is the smoking prevalence among patients?
* What is the average annual insurance cost, and how does it differ for smokers?
* What is the average number of children per patient?

## 🛠️ Tech Stack & Skills
* **Language:** Python 3
* **Environment:** Jupyter Notebook
* **Libraries:** `csv` (for data ingestion)
* **Core Concepts:** Custom function definitions, list comprehensions, control flow (if/else), loops, and data type manipulation.

## 📊 Key Findings & Insights
Based on the analysis of `insurance.csv`, here are the key takeaways:

| Category | Metric | Result |
| :--- | :--- | :--- |
| **Age** | Average Patient Age | **39.2 years** |
| **Gender** | Male / Female | **51% / 49%** |
| **Smoking** | Smoker Prevalence | **20% Yes / 80% No** |
| **Avg Cost** | Overall Annual Premium | **$13,270.42** |
| **Avg Cost** | Smokers vs. Non-Smokers | **$32,050.23 vs. $8,434.27** |
| **Family** | Avg Number of Children | **1.09 per patient** |

> **Major Insight:** Smoking status is the most significant factor affecting costs, with smokers paying nearly **4x more** on average than non-smokers.

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)

2. Ensure you have the insurance.csv file in the same directory as the notebook.

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook US_Medical_Insurance_Costs.ipynb

## 🪜 Future Work

* **Bias Analysis:** Investigate if certain regions are overrepresented or if age groups are skewed.

* **Predictive Modeling:** Implement a basic linear regression to predict insurance costs based on BMI and age.

* **Dictionary Mapping:** Refactor the code to store patient data in a nested dictionary for more efficient querying.




