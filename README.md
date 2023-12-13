Churning Dataset

README

The Churning Dataset is a dataset with various features for a client/individual such as Geography, Gender, and Tenure. These features are used to determine if a customer will leave the company based on these features. The excel dataset was identified and extracted using the data science platform Kaggle. Find out further information on the dataset using the file path https://www.kaggle.com/datasets/shubh0799/churn-modelling/data. 

Python Jupyter Notebook is the program the team used to analyze the Churning Dataset. The team leveraged several Python libraries, primarily Pandas, NumPy, Matplotlib, Seaborn, and Scikit-Learn. The dataset (D) was loaded into a Pandas Data Frame for initial analysis. We started with exploratory data analysis (EDA), using Matplotlib and Seaborn to visualize data distribution, correlations, and statistical properties. Notations for our feature matrix and target variable are X and y, respectively.

The team conducted machine learning on the Churning Dataset to find if a future customer were to meet certain idenifiers, how likely they would be to leave the company. This testing was completed by removing unneccesary features, checking for duplicates, and using SVM, KNN, and Logistic Regression Models.

By following the Churning Model codes in the Jupyter Notebook, all library installation will be uploaded into the notebook.

PROJECT STEPS

Following file installation into Jupyter, the applicable libraries will be uploaded. A statistical analysis was completed reviewing statistical metrics, missing value review, and removal of non-essential features. 

Visualization analysis of variables relating to Geography, Gender, Tenure, NumofProducts, HasCrCard, and IsActiveMember for client exits was completed to review. A correlation of remaining variables and pie chart relating to total count of exited customers to gain a better understanding is shown. 

Following gaining a better understanding by the data analysis, the categorical variables were converted to binary features. The exited variable was than removed from the dataset for its own created dataset. The dataset was tested for skewness and standarized following an output of Right Skewed. 

Project Usage
The project usage comes in the form of 3 seperate models: Logistic Regression, Support Vector Machine (SVM), and K-Nearest Neighbor (KNN). The models have been trained and tested that as new customers join the company, based on the various variables, the model can project the likelyhood the customers will exit the company.
