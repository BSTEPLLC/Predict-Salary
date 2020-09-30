# salarypredictionportfolio
Salary Prediction Project (Python)**

Examining a set of job postings with salaries and then predict salaries for a new set of job postings.

Data supplied Three CSV data files: • train_features.csv: Each row represents metadata for an individual job posting. The “jobId” column represents a unique identifier for the job posting. The remaining columns describe features of the job posting. • train_salaries.csv: Each row associates a “jobId” with a “salary”. • test_features.csv: Similar to train_features.csv, each row represents metadata for an individual job posting.

The task Build a model to predict the salaries for the job postings contained in test_features.csv. The output will be a CSV file entitled test_salaries.csv where each row has the following format: jobId, salary mirroring the format of train_salaries.csv.

Baseline Sucess Measure: MSE under 360

Deliverables 
• test_salaries.csv file containing the salary predictions for the test data set. 
• Solution Code file: Salary Portfolio Project.ipynb 

The data including Job Type and Industry, years of experience, and applicant Degree, Major, and location in miles From Metropolis, describes
the parameters from job posting requirements and applicant CV (the features) for the HR department to offer reasonable salary to staff and thereby be able to reduce unnecessary cost to the company while maintaining positive employee motivation.

Revision 3.0 Solution is a Python 3.0 analysis utilizing Pandas, Numpy, with matplotlib and Seaborn visualizations, and Sklearn for the machine learning modeling analysis. The EDA process lead to finding and engineer data to adust for with outlier.  The models considered where based on the Linear relationship between the features and the salary target.  

Machine learning models used, namely Linear Regression, Random Forest, and Gradient Boosting lead to MSE of 313.14 which is 79.1% below the baseline model that has MSE of 1499

Code Files: README.md this file
Data Explorations: Salary-Predictions-EDA.ipynb  - explored data features, cleaned data set, established baseline prediction models 
Prediction Analysis: Salary-Prediction-Analysis.ipynb - Utilized CLASS definitions for Data, Feature Generation, and ModuleContainer from code templates from available data science (DSDJ) to organize code and create a cleaner model and to be used in future projects.    

** Baseline project to gain full understanding of Michine Learning algorithm and Object Oriented Coding methods in Python
