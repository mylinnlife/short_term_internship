# Short-term Internship
## Problem
Businesses face growing challenges in retaining customers, as churn leads to lost revenue, higher marketing costs, and reduced competitiveness. Traditional retention strategies are often reactive and fail to capture real customer behavior. This project addresses the problem by conducting **a cohort-based analysis of customer retention** to track how different groups behave over time. I will also develop **a predictive model for Customer Lifetime Value (CLTV)** to estimate the long-term value of customer segments. The insights will support data-driven strategies to reduce churn, strengthen loyalty, and drive sustainable growth.
## Implementation
### Dataset: 
- I use **Online Retail II UCI dataset** that is from the UCI Machine Learning Repository, is a popular real-world transactional dataset. This dataset contains
transactional data from a UK-registered, non-store online retailer, collected between 01/12/2009 and 09/12/2011.
### Implementation
My project will be executed through a structured four-phase approach to ensure a comprehensive analysis and effective outcomes:
- Phase 1. Data Collection:   This initial phase involves identifying the business problem and collecting the necessary dataset. The process begins with defining the core issue, including understanding customer behavior and predicting customer lifetime value, followed by collecting relevant data to support the analysis.
- Phase 2. Data Processing: In this phase, the collected data undergoes a series of preparatory steps. This includes:
 1. **EDA** to understand data patterns
 2. **Data cleaning** to address inconsistencies, missing values and duplicates data.
 3. **Data preprocessing** to standardize and prepare the dataset for cohort analysis and modeling
 4. **Feature engineering** to identify relevant features that will be used to predict CLTV.
- Phase 3. Data Analysis and Modeling: This phase focuses on in-depth analysis and predictive modeling. It encompasses business analysis to derive actionable insights, cohort analysis to analyze and track customer retention, and modeling to predict CLTV, enabling targeted strategies and forecasts.
- Phase 4. Evaluation and Conclusion: The final phase involves assessing the results and drawing conclusions. This includes evaluation of the models and analyses, comparison of different approaches to determine the most effective methods, and a conclusion that summarizes findings and provides recommendations for future actions.
## Results
- The business shows strong seasonal growth (Nov–Dec) driven by high-volume, low-cost items, but revenue is concentrated in the UK, indicating an opportunity for international expansion.
- Cohort analysis revealed natural retention decline across groups, but the 2010Q1 cohort showed exceptionally high loyalty (benchmark for engagement), while the 2010Q4 cohort suffered a sharp drop-off, signaling operational/marketing issues.
- The CLTV prediction model (BG-NBD + Gamma Gamma) effectively captured spending patterns, but accuracy weakened for mid-frequency and high-value customers, suggesting room for model refinement.
- Model comparison showed:
    1. Linear Regression → most reliable for purchase frequency.
    2. BG-NBD/Gamma Gamma → underfitting due to limited data.
    3. Decision Tree & MLP → overfitting caused by small dataset size.