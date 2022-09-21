# Explainability_Predictive_Modeling_to_Identify_Diabetic_Patients

#### Machine Learning Models Deployed (in Python)
Light GBM, Logistic Regression, Decision Tree Classifier, Random Forest, XGBoost

#### Techniques Employed
Exploratory Data Analysis, Data Visualization, Dimension Reduction, ROC Curve, Machine Learning, Surrogate Explainability Models

### Context
This project is a continuation of the earlier predictive modeling project which aimed to create classification models that could help detect early diabetes status of individuals in the United States (the project can be found <a href="https://github.com/salimwid/Predictive_Modeling_to_Identify_Diabetic_Patients/"> here</a>). <br>

The purpose of the extension is to enable stakeholders (in this case, those are doctors, insurers and patients) to understand and to trust the predictions by explaining the results and chosen features further.

### Datasets
The National Health and Nutrition Examination Survey (NHANES) dataset for diabetes were used. The dataset contains information akin to what insurance firms would have access to throughout the life of the customer relationship.<br>

The original dataset consists of 4 separate tables: <br>
(a) demographics, <br>
(b) blood mineral, <br>
(c) physical examination results and <br>
(d) the diabetic/non-diabetic labels. <br>

Overall, there were over 83 original features and 10,175 individual rows, which were joined using SEQN (individual id in the dataset) into one table.

### Impact from Findings
Three main explainability models were adopted and each gave new, actionable insights: <br>

(1) Permutation Feature Importance highlighted features which were most important, such as age, weight and physical health indicators. This would have helped stakeholders to allocate their resources accordingly. <br>
(2) Global SHAP Values indicated important features and the directions of their coefficients (whether it is negative or positive). <br>
(3) Local SHAP Values and LIME explored the direction of the selected features for specific cases, allowing further investigation on a particular unit when needed. <br>

These models extended the findings presented in the original project by facilitating stakeholders to deep dive into the prediction and interpret the results in an actionable and tangible manner. <br>

### Collaborators
Gino Martelli Tiu <br>
Wong Cheng An <br>
Widya Salim <br>
Susan Koruthu <br>
Felipe Chapa <br>
Rachel Sng <br>
