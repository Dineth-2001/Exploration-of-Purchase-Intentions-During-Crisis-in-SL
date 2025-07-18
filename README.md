# Exploration of Factors Influencing Consumers’ Online Purchase Intentions During Crises in Sri Lanka

## Project Overview

This project analyzes the factors affecting **Sri Lankan consumers’ intentions to shop online during crisis situations**. Wolt — a major supermarket and shopping mall operator in Sri Lanka — seeks actionable insights to **adapt its marketing strategies and strengthen its online presence** during such times.

Through a comprehensive survey (836 responses collected) and detailed data analysis, we explore **behavioral patterns, motivations, and barriers** associated with online purchasing in crisis contexts (e.g., economic, pandemic, or fuel crises).

---

## Problem Statement

During times of national or economic crisis, consumer behavior tends to shift significantly, particularly in how and where they shop. Understanding **what drives or prevents online shopping** is essential for businesses like Wolt to align their operations and marketing efforts with real consumer needs.

---

## Objectives

- Examine how crises affect **consumer online purchase behavior**.
- Identify **key influencing factors** such as Perceived Usefulness, Ease of Use, Structural Assurance, and Social Influence.
- Use **data-driven techniques** to generate insights and actionable recommendations.
- Perform **hypothesis testing** and **rule mining** to uncover strong behavioral patterns.

---

## Repository Structure
├── Datasets/
│ ├── Original_Dataset.xlsx 
│ └── Preprocessed_Datasets/ # Contains the preprocessed datasets
│
├── Notebooks/
│ ├── Data Preprocessing/
│ ├── DDA/
│ ├── EDA/
│ └── Hypothesis Testing/
│ └── Rule Mining/
│
├── Exploration_of_Factors_Influencing_Consumers’_Online_Purchase_Intentions_During_Crises_in_Sri_Lanka.pdf
│
└── README.md


---

## Datasets

- **Original Dataset**:  
  [Online Payment Intentions – Raw Data](https://www.kaggle.com/datasets/madhushankhadesilva/online-payment-intentions)

- **Preprocessed Dataset (used for analysis)**:  
  [Online Payment Intentions – Cleaned Data](https://www.kaggle.com/datasets/dinethrandula/online-payment-intentions-preprocessed)

---

## Methodology

### 1. Data Preprocessing
- Handled missing values and outliers
- Encoded categorical variables
- Normalized Likert-scale responses
- Generated derived variables (e.g., platform familiarity index)

### 2. Exploratory & Descriptive Data Analysis (EDA & DDA)
- Examined trends across demographics, platforms, and perceptions
- Identified feature correlations with online purchase intention

### 3. Hypothesis Testing
- Tested assumptions related to gender, age, platform familiarity, etc.
- Applied t-tests, chi-square, and ANOVA where appropriate

### 4. Rule Mining
- Extracted confidence-based rules (e.g., "If high PU & high SI → strong intention")
- Used support-confidence frameworks to find hidden patterns

### 5. Insights & Recommendations
- Key barriers: trust in payment systems, lack of perceived usefulness
- Key motivators: peer influence, platform familiarity, simplicity of interface
- Actionable strategies provided for Wolt to increase customer trust and engagement

---

## Citation and Acknowledgment

The dataset used in this project was provided by the instructors of the **CS3121 – Data Science and Engineering** course, Department of Computer Science and Engineering, University of Moratuwa. 

It was temporarily uploaded to Kaggle by the project team to facilitate usage in Jupyter Notebooks and cloud-based analysis environments. The Kaggle upload is not the original source.

---

## Authors

- **Dineth Randula**  
  [LinkedIn](linkedin.com/in/dineth-randula-11814b283)
- **Thimira Sahan**  
  [LinkedIn](linkedin.com/in/thimira-sahan)
- **Madhushankha de Silva**  
  [LinkedIn](linkedin.com/in/madhushankha-de-silva-5bb58129a)
- **Anas Hussaindeen**  
  [LinkedIn](linkedin.com/in/anas-hussaindeen)
- **Vihnaga Muthumala**  
  [LinkedIn](linkedin.com/in/vihanga-muthumala-678451277)

---
