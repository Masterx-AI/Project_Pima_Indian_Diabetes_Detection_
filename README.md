# <center> Project-Pima_Indian_Diabetes_Classification 💉</center>

<p align="center"><img src="https://user-images.githubusercontent.com/54996245/140967414-b556e8ab-0322-4c77-a349-d83ce6d698a7.png" /></p>

### Description:
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage. <br><br>The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on. Can you build a machine learning model to accurately predict whether or not the patients in the dataset have diabetes or not?

### Objective:
- Understand the Dataset & cleanup (if required).
- Build classification models to predict whether or not the patients have diabetes.
- Compare the evaluation metrics of vaious classification algorithms.

### The Project is divided into the following steps:
1. Data Exploration
2. Exploratory Data Analysis
3. Data Preprocessing
4. Feature Selection/Extraction
5. Feature Scaling
6. Predictive Modeling
7. Project Outcomes & Conclusions
  
### Some Visuals of the Project:

1. Target Variable Distribution
<p align="left"><img src="https://user-images.githubusercontent.com/54996245/140614833-b4743269-e3e0-4cef-b3c4-cbc17529cad3.png" /></p>

2. Feature-set Distribution
![image](https://user-images.githubusercontent.com/54996245/140614979-eb4fedf4-ed65-4022-9c5e-e92003d481b0.png)
![image](https://user-images.githubusercontent.com/54996245/140614994-bececcc9-23d9-4428-a5b5-48cd028c18d4.png)

3. Relationship between the Feature-set
![image](https://user-images.githubusercontent.com/54996245/140615006-63a294ef-e66b-4819-94de-152d60d9e6f1.png)

4. Data Retention after preforming preprocessing step

![image](https://user-images.githubusercontent.com/54996245/140615012-ba0ea2a2-9b8c-4aa7-82c9-8ce2bca6c4ad.png)

5. ML Algorithm's Scores for the Iris Dataset
![image](https://user-images.githubusercontent.com/54996245/140615041-10ae0518-b801-41cd-a3fa-9ca186d6e82a.png)


### Here are some of the key outcomes of the project:
- The Dataset was quiet small totally just 768samples & after preprocessing 17.2% of the datasamples were dropped. 
- The diabetic samples were 30% more than non-diabetic ones, hence SMOTE Technique was applied on the data to  balance the classes, adding 11.8% more samples to the dataset.
- Visualising the distribution of data & their relationships, helped us to get some insights on the class seperability.
- Feature selection or feature extracting was not exercised, as there were only 8 features, which overall contributed towards the right prediction.
- Testing multiple algorithms with default hyperparamters gave us some understanding for various models performance on this specific dataset.
- Random Forest perform the best on the current dataset, followed by Support Vector Machines & Boosting Algorithms
- Yet it wise to also consider simpler models as they are more generalisable & take lesser training time.

