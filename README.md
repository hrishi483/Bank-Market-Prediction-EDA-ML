
# Bank-Market-Prediction-EDA-ML 🏦💰💹



#### Context:
Find the best strategies to improve for the next marketing campaign. How can the financial institution have a greater effectiveness for future marketing campaigns? In order to answer this, we have to analyze the last marketing campaign the bank performed and identify the patterns that will help us find conclusions in order to develop future strategies.

### Source:
[Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31, June 2014.

### Dataset:
you can find the dataset on Kaggle:
https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset
## Lessons Learned 
In this project, I explored the fascinating world of banking data to gain insights into customer behavior and predict the success of marketing campaigns. The dataset contains information related to a Portuguese banking institution's marketing campaigns, including details about the customers and the outcome of the campaign (whether they subscribed to a term deposit or not).

#### 📊 Exploratory Data Analysis (EDA): 🔍
To start the project, I performed a comprehensive Exploratory Data Analysis (EDA) to understand the data's structure, distribution, and relationships between variables. I utilized various Python libraries, such as Pandas, NumPy, and Matplotlib, to clean the data and create insightful visualizations. During EDA, I identified key patterns, trends, and potential challenges for modeling.

#### Some highlights from the EDA process include:

- Uncovering the distribution of the target variable and identifying class imbalances.
- Analyzing customer demographics, such as age, job, education, and marital status, to identify any patterns that may influence campaign success.
- Investigating the impact of economic indicators, like employment variation and consumer price index, on the campaign outcome.
- Exploring customer contact information and behavioral attributes, such as contact duration and the number of contacts, to understand their relevance in predicting subscription success.


#### 🤖 Machine Learning Models 🤖 📉 :
After gaining valuable insights from EDA, I proceeded to develop predictive models using various machine learning algorithms. The primary objective was to predict whether a customer would subscribe to a term deposit based on the available features.

I employed the following machine learning techniques:

 

    1.Baseline Models: As a starting point, I built a Logistic Regression,Naive Bayes,Decision Tree classifier and SVM models to establish a baseline performance for classification.
    2. Ensemble Methods 🌳🌳:
    Random Forest Classifier: I utilized ensemble methods like Random Forest to harness the collective wisdom of multiple decision trees, improving prediction accuracy.
    3. Gradient Boosting Classifier,AdaBoost,XGBoost 🚀🚀🚀: Additionally, I implemented Gradient Boosting, a powerful boosting algorithm that sequentially combines weak learners to build a robust predictive model.
    4. Model Evaluation and Hyperparameter Tuning:
    I evaluated the model performance using metrics such as accuracy,since the dataset was balanced.
    5. Comparing Performance of different Models: After lot of hyperparametre tuning I was able to get best hyperparametres for each algorithm.The best accuracy was for XGBoost (train: 94.2%, test: 80.08%) but it was overfitting so instead I chose next best GradBoost (train:88.2%,test:80%).
    6. To gain insights into the model's decision-making process, I employed feature importance techniques to identify which features significantly influenced the model's predictions.
    
#### 📝 Conclusion 📋:
This project provided a hands-on experience in real-world data analysis and the application of machine learning algorithms to solve a practical problem in the banking domain. The combination of Exploratory Data Analysis and Machine Learning helped me gain valuable insights into customer behavior and build models to predict campaign success.

🙋🏼‍♂️🙋🏼‍♂️
Feel free to explore the Jupyter Notebooks and Python scripts in the respective directories to delve deeper into the project's codebase. If you have any questions or suggestions for improvement, please don't hesitate to reach out. I look forward to expanding my knowledge and skills in Data Science through more exciting projects in the future!😊


## Authors

- Visit my Kaggle Profile :https://www.kaggle.com/hrishikeshkarande483


## Support
- Please upvote this notebook https://www.kaggle.com/code/hrishikeshkarande483/bank-marketing/notebook#Explore-the-data

