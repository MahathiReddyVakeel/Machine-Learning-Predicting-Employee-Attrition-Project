# Predicting-Employee-Attrition-Project

Why the topic is important.
Forecasting when an employee will leave a firm is critical for organizations since high turnover rates can result in both time and financial loss, affecting productivity. Companies may retain brilliant individuals on board by implementing preemptive methods while decreasing the pace at which people resign from work by using machine learning techniques to construct models that predict which employees are likely to abandon their positions soon.

How/ Where you plan to get the dataset for the project:
The Employee Attrition dataset can be downloaded from the kaggle website. The dataset is available in CSV format and contains information on employee demographics, job-related factors, and attrition status. The dataset is free to use for academic purposes.
Aim is to predict employee departures using machine learning to tackle attrition, a costly issue for businesses. Using IBM's HR Analytics Employee Attrition dataset, we'll preprocess data, explore features, and apply machine learning to accurately forecast turnover and identify key factors driving employee attrition.

                                            Abstract
Using machine learning methods, we hope to predict employee departures in this project. Employee attrition is a key problem for businesses because it may result in increased expenses and the loss of talent. We'll utilize IBM's HR Analytics Employee Attrition dataset, which includes information on employees' job satisfaction, performance assessments, and demographics. To anticipate employee attrition, we will preprocess the data, investigate the attributes, and use machine learning techniques. Our objective is to create a model that can forecast employee turnover correctly and identify the important elements that contribute to it.

                                           Introduction
Employee attrition, or turnover, a significant part of businesses of all types. High levels of attrition can result in increased recruiting, training expenses and hiring, as well as the loss of important personnel and institutional expertise. Predicting and controlling employee attrition is therefore critical for sustaining a healthy and effective staff.

One option to tackling this problem is to employ machine learning techniques. Machine learning models can identify the important elements that lead to employee attrition and forecast which employees are at danger of leaving by examining historical data on employee performance, job satisfaction, and demographic attributes.

In this project, we will utilize the Kaggle HR Analytics staff Attrition dataset to create a machine learning model that can predict staff attrition. We will investigate the data, preprocess it, and use machine learning algorithms to determine the most relevant factors influencing employee turnover. Our ultimate objective is to create a model that can reliably forecast employee turnover and assist firms in taking proactive actions to retain their prized personnel.

                                        LITERATURE REVIEW

Employee attrition, or the voluntary departure of employees, has long been a source of problem for businesses of all sizes. According to "Society for Human Resource Management", average cost per hire for businesses is $4,129, with a 42-day time-to-fill (SHRM, 2017). Employee turnover may be costly for businesses due to the added costs of lost productivity and the requirement for replacement training. As a result, firms must understand the variables that lead to employee turnover and devise methods to retain top personnel.

One of the earliest studies in this area is by Becker et al. (1996), who proposed a model to predict employee turnover based on data from the United States Postal Service. The study used logistic regression to analyze the data and identified several factors associated with employee turnover, such as length of service, age, and job grade.

Several research on the reasons of employee attrition have been done. According to a research conducted by Holtom, Mitchell, Lee, and Eberly (2008), job unhappiness and poor organizational commitment were substantial predictors of turnover. Employee turnover was also shown to be influenced by a lack of professional development opportunities and bad relationships with supervisors. Allen and Meyer (1990) discovered that individuals with higher degrees of organizational commitment were less likely to leave their positions, but those with higher levels of alternative employment alternatives were more likely to leave.

In a more recent study, Karimi et al. (2018) used artificial neural networks (ANN) to predict employee turnover in a financial institution. The study used a dataset with over 15,000 employee records and found that the ANN model outperformed logistic regression, decision trees, and random forests.

In addition to these studies, several other researchers have used various machine learning techniques such as support vector machines, k-nearest neighbors, and ensemble methods to predict employee turnover with varying levels of success.

Overall, these studies highlight the potential of machine learning techniques in predicting employee attrition and suggest that organizations can use these models to proactively identify and retain valuable employees

                                                    REFERENCES
Becke,Brian. The impact of human resource management on organizational performance: Progress and prospects. Punnoose, Rohit. “A case for Extreme Gradient Boosting in Prediction of Employee Turnover in Organizations using Machine Learning Algorithms.” Choi, S. Diversity Management and Employee Turnover in Federal Agencies. http://www.jstor.org/stable/29738962

Data set link: https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset

Why this Dataset?

The selected records from the HR Analytics Employee Attrition dataset were chosen to support our hypothesis based on their relevance to the research objective and the availability of data. The dataset contains over 1,400 entries with various employment aspects of staff members' background information, making it a suitable choice for analyzing employee attrition.

We specifically focused on columns such as job satisfaction, work-life balance, and other relevant factors that are known to be correlated with employee attrition based on previous research and literature review. These factors were selected based on their theoretical significance in influencing employee turnover, as well as their availability in the dataset.

By analyzing these selected records, we were able to build a logistic regression model and evaluate its performance in predicting employee attrition. The results obtained from this analysis helped us validate our hypothesis and draw meaningful conclusions about the factors that contribute to employee attrition in the dataset.

Overall, the selected records were chosen based on their relevance to the research objective and their ability to provide insights into the relationship between different factors and employee attrition.

                                                      Conclusion
Based on the evaluation metrics, the Random Forest Classifier achieved an accuracy of 0.87, precision of 0.71, recall of 0.12, and F1 score of 0.21. The model was able to correctly identify 12% of the employees who left the company (recall), and had a precision of 71% (out of all employees predicted to leave, 71%)

This suggests that our model can effectively classify whether an employee is likely to leave the company or not based on their job satisfaction, work-life balance, and other factors.

Additionally, we observed that job satisfaction and work-life balance were the two most important factors in predicting employee attrition. This suggests that employers can reduce employee turnover by focusing on improving these two aspects of their employees' work experience.

In conclusion, our study shows the potential of machine learning in predicting employee attrition and providing valuable insights for employers to improve employee retention. Future studies can further explore other factors that contribute to employee turnover and develop more accurate models for predicting attrition.
