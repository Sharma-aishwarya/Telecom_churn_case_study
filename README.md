# Telecom Churn Case Study - README

Welcome to the Telecom Churn Case Study project! In this document, we will provide an overview of the problem, the dataset, data preparation, modeling, and key insights gained from our analysis.

## Business Problem Overview

The telecom industry is highly competitive, with customers having the freedom to choose from multiple service providers. However, this industry also faces a significant challenge - customer churn. Churn, the rate at which customers switch to other operators, can cost telecom companies dearly. To address this issue, we aim to predict which customers are at high risk of churning and identify key indicators of churn.

## Understanding Churn

Churn is defined as the act of customers discontinuing their services. In the prepaid model, where customers pay in advance, it's challenging to identify churn as customers can stop using services without notice. Our focus is on **usage-based churn**, where customers who haven't used any services over a period are considered potential churners.

## High-Value Churn

High-value customers contribute significantly to telecom revenue. We aim to reduce churn among these customers. We define high-value customers as those with a certain level of average recharge amount.

## Data Preparation

**1. Derive New Features:** We create meaningful features that may serve as indicators of churn.

**2. Filter High-Value Customers:** High-value customers are identified based on recharge amounts, ensuring that we focus on predicting churn for these customers.

**3. Tag Churners and Remove Churn Phase Attributes:** Customers who have stopped using services entirely in the churn phase are tagged as churners. Attributes related to the churn phase are removed from analysis.

## Modelling

Our modeling approach includes the following steps:

**1. Preprocess Data:** We handle data formatting and missing values.

**2. Exploratory Analysis:** Extract insights that are valuable for both business and modeling.

**3. Derive New Features:** Create additional features that may enhance model performance.

**4. Dimensionality Reduction:** We use Principal Component Analysis (PCA) to reduce the number of variables.

**5. Train Models:** Develop predictive models while addressing class imbalance.

**6. Evaluate Models:** Use appropriate metrics, with a focus on sensitivity, to identify potential churners.

**7. Identify Important Predictors:** Build models to identify key indicators of churn, providing insights into why customers switch to other networks.

## Dataset and Data Dictionary

- **Dataset:** The data consists of customer-level information spanning four consecutive months (June, July, August, and September).

- **Data Dictionary:** We provide a data dictionary explaining the meaning of abbreviations used in the dataset.

## Key Insights

1. **Top Predictors:** We identified critical predictors of churn, including loc_ic_mou_8, og_others_7, isd_og_mou_8, and others.

2. **Recommendations:** Strategies to manage churn include targeting customers with decreasing usage, offering incentives, addressing increased costs, and monitoring roaming usage.

## Project File
 
 **Data Files:** You can access the dataset [here](https://drive.google.com/file/d/1SWnADIda31mVFevFcfkGtcgBHTKKI94J/view).

For a more detailed exploration and insights, please refer to the notebooks.

This project aims to empower the telecom company to reduce churn by understanding customer behavior and implementing effective strategies.