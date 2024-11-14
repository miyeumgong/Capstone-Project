### Project Title

**Author**

#### Executive summary
This project explores user churn within an OTT platform, employing machine learning models to predict which users are likely to churn based on engagement and demographic factors. Using models like Logistic Regression, K-Nearest Neighbors (KNN), Decision Tree, Gradient Boosting, and Support Vector Machines (SVM), I identified the most accurate predictors of churn. The findings indicate key factors associated with churn and provide insights for developing retention strategies, ultimately guiding data-driven decisions to reduce churn rates.

#### Rationale
Why should anyone care about this question?
Understanding and predicting user churn is crucial for OTT platforms facing stiff competition. High churn rates increase acquisition costs and affect profitability, as retaining existing users is more cost-effective than acquiring new ones. Predicting churn allows OTT platforms to proactively engage at-risk users, tailor content, and develop targeted interventions. This insight benefits not only the OTT providers but also enhances user experience by addressing user-specific needs.

#### Research Question
What are you trying to answer?
What factors contribute most significantly to user churn on an OTT platform, and how can machine learning models predict at-risk users to help mitigate churn?

#### Data Sources
What data will you use to answer you question?
I used "Churn Modeling for OTT Platforms" data from 
https://www.kaggle.com/datasets/santhoshvr97/ott-chrun-modeling-ott

#### Methodology
What methods are you using to answer the question?
I followed a structured machine learning pipeline, which included:
    1.    Data Preprocessing: Data cleaning, encoding categorical variables, handling missing values, and feature scaling.
    2.    Model Selection and Training: Using Logistic Regression, K-Nearest Neighbors, Decision Tree, Gradient Boosting, and Support Vector Machines to compare their effectiveness in predicting churn.
    3.    Model Evaluation: I evaluated each model based on accuracy, precision, recall, F1-score, and AUC-ROC to identify the most predictive and reliable models.
    4.    Result Interpretation: Key metrics were analyzed to assess each model’s predictive power, helping highlight the most important factors influencing churn.
    
#### Results
What did your research find?
The machine learning models provided a range of performance metrics, with Gradient Boosting and SVM showing the highest AUC-ROC scores, indicating strong predictive power. Logistic Regression performed adequately but with lower recall, indicating it missed some churn cases. Decision Tree and KNN provided moderate precision and recall but showed lower AUC-ROC compared to Gradient Boosting and SVM. These results suggest that the top-performing models can reliably identify at-risk users based on their engagement and usage patterns.

#### Next steps
What suggestions do you have for next steps?
    1.    Model Fine-Tuning: Refine the models further through hyperparameter tuning, especially for Gradient Boosting and SVM, to improve accuracy and recall.
    2.    Feature Engineering: Experiment with additional derived features or interaction terms to capture more complex relationships within the data.
    3.    Segmented Retention Strategies: Use churn probability scores to segment users and create targeted retention strategies, such as special offers, personalized recommendations, or timely notifications.

#### Outline of project
    1.    Introduction and Background: Overview of the OTT industry and the importance of understanding churn.
    2.    Research Question and Objectives: Define the goals of the analysis and key questions being answered.
    3.    Data Overview: Detailed description of the dataset and features.
    4.    Exploratory Data Analysis (EDA): Insights on data trends, correlations, and initial observations.
    5.    Modeling Approach: Explanation of chosen machine learning models and the rationale behind each.
    6.    Evaluation and Results: Presentation of model evaluation metrics and comparison of performance.
    7.    Conclusions and Recommendations: Summary of findings and practical suggestions for reducing churn.
    8.    Next Steps and Future Work: Outline of potential developments and applications for ongoing churn prediction efforts.

##### Contact and Further Information
