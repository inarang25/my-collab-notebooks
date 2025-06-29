# my-collab-notebooks
# SNC Bank Credit Card Project

This repository contains two Jupyter notebooks detailing an analysis for the launch of a new credit card product by SNC Bank. The project aims to identify a target market and assess the impact of a new credit card product through A/B testing.

## Notebooks

### 1. `EDA_&_Target_Market_Identification.ipynb`

This notebook focuses on Exploratory Data Analysis (EDA) and identifying a target market for the SNC Bank credit card launch.

* **Objective**: Analyze customers' transactions and credit profiles to identify a suitable target group for the new credit card.
* **Key Insights**:
    * Detailed exploration of customer data, credit profiles, and transaction data.
    * Identification of an "untapped market" segment.
    * Insights into demographics and spending habits to define the target audience for the credit card.

### 2. `AB_Testing.ipynb`

This notebook details the A/B testing methodology and results for the new SNC Bank credit card, specifically targeting the identified customer segment.

* **Objective**: Conduct an A/B test to evaluate the effectiveness of the new credit card product within the 18-25 age group.
* **Key Insights**:
    * **Business Analysis and AB Testing Launch**: Focuses on targeting the 18-25 age group.
    * **Pre-Campaign Analysis**: Determines the required sample size for control and test groups based on statistical power and effect size.
    * **Insights specific to customers with age group of 18 - 25**:
        * This age group accounts for approximately 25% of the customer base.
        * Average annual income is less than 50k.
        * They generally have limited credit history, impacting credit scores and limits.
        * Credit card usage and average transaction amounts are relatively low compared to other age groups.
        * Top spending categories include Electronics, Fashion & Apparel, and Beauty & Personal care.
    * **Conclusion**: The A/B test showed a statistically significant increase in average transaction amounts in the test group (18-25 age group) exposed to the new credit card, leading to a recommendation for wider rollout.

## Data

The analysis uses three datasets:
* `customers.csv`
* `credit_profiles.csv`
* `transactions.csv`

(Note: These files are expected to be located in a `Personal/Codebasics/AB Testing/` folder within a mounted Google Drive, as indicated in the notebooks.)

## How to Run

To run these notebooks, you will need to:
1.  Open the `.ipynb` files in Google Colab.
2.  Mount your Google Drive and ensure the dataset files (`customers.csv`, `credit_profiles.csv`, `transactions.csv`) are placed in the specified folder path: `/content/drive/My Drive/Personal/Codebasics/AB Testing/`.
3.  Run all cells in sequence.
