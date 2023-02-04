# Lung_Cancer_Prediction_Machine_Learning
Lung cancer, also known as lung carcinoma, is a malignant lung tumor characterized by uncontrolled cell growth in tissues of the lung. This growth can spread beyond the lung by the process of metastasis into nearby tissue or other parts of the body.

# Motivation:

Cancer is one of the leading causes of death both in the U.S. and worldwide, and lung cancer is one of the most widespread and deadly varieties. Much research has been done on the link between smoking tobacco and lung cancer risk; it is estimated that ~85% of lung cancer cases are attributed to smoking tobacco. The remaining 10-15% is not as well understood (but a very significant portion given how prevalent lung cancer is). In addition to working in the carcinogenic environment exposure to various chemicals (radon, asbestos, arsenic, cadmium, etc.) explains much of the rest of lung cancer. Currently, only 17% of lung cancers are diagnosed while the tumor is still localized—that is, only found at the site where it started. This is commonly referred to as stage I. The major challenge is that most people with lung cancer only have symptoms when they are in the later stages of the disease, so lung cancer is not usually suspected and discovered until it has had the chance to grow and spread. However, lung cancer is most easily and effectively treated when it is found at an early stage. Statistically, those with lung cancer caught early on have a much higher likelihood of surviving at least five years after diagnosis than those diagnosed when the lung cancer is more advanced. So our moto is spread the awareness among the people by predicting the early stage using machine learning models.

# Data Preparation:

The original dataset contains 18 columns and 510 rows with the "GENDER" and "LUNG_CANCER" columns containing object data types while the rest of the columns were integer datatypes. The data was then cleaned and processed for modeling by changing the following: The values "M" and "F" in the "GENDER column were converted to 1 and 0 respectively. The values "Positive" and "Negative" in the "LUNG_CANCER" column were converted to “YES” and “N0” respectively. The values "Yes" and "No" in the rest of the columns were converted to 2 and 1 respectively. The processed dataset was then saved as processed_lung_cancer.csv

# Original Dataset:

https://github.com/tanzina-islam/Lung_Cancer_Prediction_Using_ML/blob/main/LungCancerSurvey.csv

# Modeling:

In this thesis, we tried to predict Lung Cancer using 6 different algorithm: Logistic regression classification, SVM (Support Vector Machine) classification, Naive Bayes classification, Decision Tree classification, Random Forest classification, K-Nearest Neighbor classification, The final model used for the prediction was the Logistic Regression Model which had an accuracy score of 0.79.
