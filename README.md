# AI221-Project-LendingClub
This repository contains the team project for the AI 221 Classical Machine Learning course at UP Diliman in 2023 where we worked with the Lending Club dataset obtained from Kaggle. The dataset includes accepted loans data from 2007 to 2020 and rejected loans data from 2007 to 2018.

## Dataset Details
- **Accepted and Rejected Loans 2007 to 2018:** [Kaggle Dataset Link](https://www.kaggle.com/datasets/wordsforthewise/lending-club)
- **Accepted Loans 2007 to 2020:** [Kaggle Dataset Link](https://www.kaggle.com/datasets/ethon0426/lending-club-20072020q1)

The accepted loans dataset contains 2.9 million rows and 142 columns, while the rejected loans dataset has 27.6 million rows and 9 columns. We will primarily focus on the accepted loans dataset to predict loan ratings and delinquency. However, we also plan to explore the rejected loans dataset to understand the reasons for loan rejections.

## Project Workflow
From our initial exploration, we have determined that this dataset is rich enough to cover the required workflow and more. Our intended workflow for this project is as follows:

1. **Preprocessing Step:** The dataset contains null values, categorical features, and inconsistent labels, which require preprocessing to ensure data quality and reliability.

2. **Unsupervised Learning Step:** The accepted loans dataset with its 142 features presents an opportunity to employ dimensionality reduction techniques to handle high-dimensional data effectively.

3. **Supervised Learning Step:** The accepted dataset offers numerous interesting features that can serve as target variables. Currently, we are considering loan ratings and delinquency, but additional target variables may be incorporated as we delve deeper into the data.

4. **Explainable AI Techniques:** We plan to utilize explainable AI techniques such as permutation feature importance, SHAP (SHapley Additive exPlanations), or DiCE (Distribution Counterfactual Explanation) to interpret the results of our models and gain insights into the factors influencing loan ratings and delinquency.

5. **Exploring Market Shocks:** We are particularly interested in exploring the impact of significant market shocks, such as the 2008 financial crisis and the 2019 pandemic, on loan trends. Analyzing these changes in trend can provide valuable insights into the dynamics of the lending industry during challenging periods.

