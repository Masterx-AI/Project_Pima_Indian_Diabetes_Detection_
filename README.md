# <center> ML Project - Pima Indian Diabetes Detection 💉</center>

<p align="center"><img src="https://user-images.githubusercontent.com/54996245/140967414-b556e8ab-0322-4c77-a349-d83ce6d698a7.png" style="width: 600px;"/></p>

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

**1. Target Variable Distribution**
<p align="left"><img src="https://user-images.githubusercontent.com/54996245/140968400-955f7936-5364-46e5-93ab-7f377967337d.png" /></p>

**2. Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/140968604-ada9ef59-72b0-4d34-9ca8-83df78c7234c.png)
![image](https://user-images.githubusercontent.com/54996245/140968617-ceaa45a1-35cc-4d3e-bc72-3b8d221f2e1c.png)

**3. Relationship between the Feature-set**

![image](https://user-images.githubusercontent.com/54996245/140968656-574e4edc-3f4c-4c3a-9359-07bde41d538a.png)

**4. Data Retention after preforming preprocessing step**

![image](https://user-images.githubusercontent.com/54996245/140968701-7b426b4b-9740-4398-a3c0-0e5ae190cc8e.png)

**5. Correlation plot for features**

![image](https://user-images.githubusercontent.com/54996245/140968731-2d37bde1-3235-4a07-813d-1313339e481c.png)

**6. ROC Plots**

![image](https://user-images.githubusercontent.com/54996245/140968858-ac6271bb-f3a6-4a07-a353-6529eea56b2b.png)


**5. ML Algorithm's Scores for the Iris Dataset**
![image](https://user-images.githubusercontent.com/54996245/140968943-d4051d54-2b91-4b59-921f-0629c925a86d.png)
![image](https://user-images.githubusercontent.com/54996245/140968960-fb10b8e0-1787-46be-bf4b-af1d8bbb6418.png)



### Here are some of the key outcomes of the project:
- The Dataset was quiet small totally just 768 samples & after preprocessing 17.2% of the datasamples were dropped. 
- The diabetic samples were 30% more than non-diabetic ones, hence SMOTE Technique was applied on the data to  balance the classes, adding 11.8% more samples to the dataset.
- Visualising the distribution of data & their relationships, helped us to get some insights on the class seperability.
- Feature selection or feature extracting was not exercised, as there were only 8 features, which overall contributed towards the right prediction.
- Testing multiple algorithms with default hyperparamters gave us some understanding for various models performance on this specific dataset.
- Random Forest perform the best on the current dataset, followed by Support Vector Machines & Boosting Algorithms
- Yet it wise to also consider simpler models as they are more generalisable & take lesser training time.

