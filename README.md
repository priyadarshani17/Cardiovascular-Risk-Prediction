# Cardiovascular-Risk-Prediction
Problem Statment
The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes.
Data Description
Demographic:
• Sex: male or female("M" or "F")

• Age: Age of the patient

Behavioral:
• is_smoking: whether or not the patient is a current smoker ("YES" or "NO")

• Cigs Per Day: the number of cigarettes that the person smoked on average in one day.

Medical( history):
• BP Meds: whether or not the patient was on blood pressure medication

• Prevalent Stroke: whether or not the patient had previously had a stroke

• Prevalent Hyp: whether or not the patient was hypertensive

• Diabetes: whether or not the patient had diabetes

Medical(current):
• Tot Chol: total cholesterol level

• Sys BP: systolic blood pressure

• Dia BP: diastolic blood pressure

• BMI: Body Mass Index

• Heart Rate: heart rate

• Glucose: glucose level

Predict variable (desired target)
• 10-year risk of coronary heart disease CHD(binary: “1”, means “Yes”, “0” means “No”) - DV

Project Description:
Heart disease is the major cause of morbidity and mortality globally:

It accounts for more deaths annually than any other cause. According to the World Health Organizartion, an estimated 17.9 million people died from heart diseases in 2016, representing 31% of all global deaths. Over three quarters of these deaths took place in low- and middle-income countries.

Of all heart diseases, coronary heart disease is by far the most common and the most fatal. In the United States, for example, it is estimated that someone has a heart attack every 40 seconds and about 805,000 Americans have a heart attack every year (CDC 2019).

Doctors and scientists alike have turned to machine learning (ML) techniques to develop screening tools and this is because of their superiority in pattern recognition and classification as compared to other traditional statistical approaches.

In this project, We will be giving a walk through on the development of a screening tool for predicting whether a patient has a 10-year risk of developing coronary heart disease(CHD) using different Machine Learning techniques.

So, where does machine learning fit in ?
Due to the multi-contributory risk factors such as high blood pressure, high cholesterol, diabetes and various others it gets very constrained to identify the risk factors for some of the patients. That's why we are turning to data visualization and machine learning for predicting the disease to avert the risks. Machine learning (ML), due to its distinction in pattern detection and classification, proves to be effective in assisting decision making and risk assessment from the large quantity of data produced by the healthcare industry on heart disease.

Conclusion:
We trained 7 Machine Learning models using the training dataset, and hyperparameter tuning was used in some models to improve the model performance.
To build the models, missing values were handled, feature engineering and feature selection was performed, and the training dataset was oversampled using SMOTE to reduce bias on one outcome.
Recall was chosen as the model evaluation metric because it was very important that we reduce the false negatives.
Initial set of predictions were obtained using the baseline model, ie, logistic regression model, and other commonly used classification models were also build in search of better predictions.
From our analysis, it is also found that the age of a person was the most important feature in determining the risk of a patient getting infected with CHD, followed by pulse pressure, prevalent hypertension and total cholesterol.
Diabetes, prevalent stroke and BP medication were the least important features in determining the risk of CHD
