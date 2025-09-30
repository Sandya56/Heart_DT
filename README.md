Business Problem - Background
Heart disease and stroke can be fatal but they can also cause major sickness,
disablity, and a reduction in life quality. A stroke can result in substantial handicap including 
paralysis,speech problems and emotional issues

Individual who have had a heart attach usually experience exhaustion and despai and they may find it difficult 
to engage in physical activity.

Business problem - Explained
Healthcare companies collect a lot of historical data pertaining to these chronic diseases. These
datasets can be leveraged to rain machine learning algorithms and learn from the history which
eventually will help in predicting such chronic conditions in patients.



# age: Age of the patient (in years).
# sex: Gender of the patient (0 = female, 1 = male).
# cp: Chest pain type (categorical variable):
# 0: Typical angina
# 1: Atypical angina
# 2: Non-anginal pain
# 3: Asymptomatic
# trestbps: Resting blood pressure (in mm Hg on admission to the hospital).
# chol: Serum cholesterol level (in mg/dL).
# fbs: Fasting blood sugar > 120 mg/dL (1 = true; 0 = false).
# restecg: Resting electrocardiographic results (categorical):
# 0: Normal
# 1: Having ST-T wave abnormality (e.g., T wave inversions and/or ST elevation or depression of >0.05 mV)
# 2: Showing probable or definite left ventricular hypertrophy by Estes' criteria.
# thalach: Maximum heart rate achieved.
# exang: Exercise-induced angina (1 = yes; 0 = no).
# oldpeak: ST depression induced by exercise relative to rest (numeric).
# slope: The slope of the peak exercise ST segment:
# 0: Upsloping
# 1: Flat
# 2: Downsloping
# ca: Number of major vessels (0–3) colored by fluoroscopy.
# thal: Thalassemia (categorical):
# 0: Normal
# 1: Fixed defect
# 2: Reversible defect
# target: Presence of heart disease (binary):
# 0: No heart disease
# 1: Heart disease present


# Feature Selection:
# VIF- check the multicolinearity, that is not the problem in the Tree algorithms
# we can go ahed with other feature selection Techniques
# corelation
# RFE -Recursive feature Elimination
# In the Given dataset I will not Go ahead with any of the FS technique as it already have less feature and all have significance in medical Terms




