# Supplier-Risk-modeling-for-Insurance-industry
# Situation: 
A client company engaged in assessing vendor risks required an enhancement of their traditional Third-Party Risk Management (TPRM) frameworks. Previously, these frameworks primarily focused on financial and IT security risks, which often failed to capture the full spectrum of vendor risks effectively.

# Task: 
The project aimed to develop a vendor risk assessment model that integrates additional Key Risk Indicators (KRIs) beyond the traditional ones, thus providing a more robust evaluation of vendor risks. These KRIs included IT Security, Operational, Financial, Compliance, and Environmental, Social, and Governance (ESG) risks.

# Action: 
To achieve this, the project team executed the following steps for each KRI:

# IT Security:
Collected data through updated risk questionnaires via a platform called Coupa.
Modeled the data in two stages, focusing on company-specific and engagement-specific metrics.
Used machine learning techniques to process and evaluate IT security risks.

# Operational Risk:
Gathered data from internal questionnaires and external sources like web scraping.
Utilized Principal Component Analysis (PCA) for data modeling to assess operational risks effectively.

# Financial Risk:
Analyzed financial and operational performance attributes from historical data.
Applied techniques such as imputation of missing values, outlier removal, and handling class imbalance using SMOTE.
Trained and selected models using various machine learning algorithms to predict financial stability.

# Compliance Risk:
Collected compliance-related data through both web scraping and internal questionnaires.
Standardized and preprocessed the data, employing PCA to identify important features.
Calculated compliance scores based on the normalized importance of compliance indicators.

# ESG Risk:
Performed sentiment analysis on news articles related to ESG factors using the VADER sentiment analyzer integrated with a financial lexicon.
Calculated ESG scores based on the sentiment analysis, providing insights into the public perception of company's ESG practices.

# Result: 
The model was successfully developed and delivered, complete with comprehensive documentation and tools necessary for the client to deploy and operate the risk assessment model internally. This model enables the client to make informed decisions regarding vendor relationships, thereby proactively managing and mitigating vendor risks, ensuring operational resilience, and maintaining compliance across all vendor engagements.
