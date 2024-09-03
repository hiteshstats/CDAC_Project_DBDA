# Credit Score Predictor : System that Predicts Customer Credit Scores based on Financial Data
- Tool Stack : Microsoft Azure, Databricks, PySpark, Machine Learning, MongoDB
- Data was ingested from mongoDB (on-premises) to Azure Data Lake Storage in bronze layer
- Followed medallion architecture for efficient data management
- ETL was Performed using Data Flow activity in Azure Data Factory
- Databricks was mounted to Azure Data Lake Storage container (landing)
- Advance data cleaning was done in Databricks using PySpark and data was made ready for predictive analysis
- New features were engineered to make the model more effective
- Credit Score Predictor function was built which takes file as input and return a downloadable file with predicted credit score and a bar plot
  
## Problem Statement
* In the current financial landscape, credit scoring is crucial for financial institutions to assess the creditworthiness of potential customers. This project aims to develop a machine learning model that predicts the credit score of customers based on a comprehensive set of financial and behavioral data. 
* By leveraging this diverse set of features, the goal is to build a robust predictive model that provides accurate credit scores. This model will assist financial institutions in making informed decisions, reducing the risk of loan defaults, and offering tailored financial products to customers based on their risk profiles

## Architecture Design
![Alt Text](https://github.com/hiteshstats/CDAC_Project_DBDA/blob/main/Architecture%20Design.png?raw=true)
