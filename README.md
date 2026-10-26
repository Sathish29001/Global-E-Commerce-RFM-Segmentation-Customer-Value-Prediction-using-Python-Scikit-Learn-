# Global-E-Commerce-RFM-Segmentation-Customer-Value-Prediction-using-Python-Scikit-Learn-
In this project, I simulated and analyzed a dataset of 3,000 global e-commerce customers to solve a core business challenge: understanding customer purchasing behavior, grouping high-value cohorts, and predicting customer lifetime spend.

🔍 Project Architecture & Workflow: 
    Data Cleaning & Exploratory Data Analysis (EDA): Inspected data distributions across countries, ages, genders, and membership tiers.  
    Feature Engineering & Log Transformation: Applied log transformations to handle skewness in monetary and transactional data (RecencyDays, Frequency, MonetaryValue).       Unsupervised Learning (K-Means Clustering): Segmented customers into 4 distinct behavioral clusters using standardized RFM features. 
    Supervised Machine Learning Pipeline: Built a robust Pipeline with ColumnTransformer (handling numerical scaling and categorical One-Hot Encoding) to prevent data leakage.  
     Multiple Linear Regression (MLR) Modeling: Trained an MLR model to predict customer spend, achieving an R2 Score of 0.5732 and an RMSE of $0.28.   
     
  📊 Model Evaluation & Visualizations: 
    Actual vs. Predicted Customer Spend: Evaluated model performance against ideal fit lines ($y=x$) to assess prediction accuracy.  
    Residuals Plot: Analyzed error variance and homoscedasticity to ensure robust linear regression assumptions. 
    
  🛠️ Tech Stack & Libraries Used:
    Python 
    Pandas & NumPy  
    Scikit-Learn (KMeans, LinearRegression, Pipeline, ColumnTransformer, StandardScaler, OneHotEncoder)
    Matplotlib & Seaborn (for visualization suites)   
    
  Check out the snapshot of my actual vs. predicted regression and residual plots below! 👇 I'd love to connect with fellow data enthusiasts, recruiters, and data scientists. Let me know your thoughts or feedback in the comments!
  
  #DataScience #MachineLearning #Python #ECommerce #DataAnalytics #RFMSegmentation #ScikitLearn #PortfolioProject
