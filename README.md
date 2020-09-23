# Motivation 
Diabetes has become a more and more severe problem. According to the following  <a href="https://www.diabetes.org/resources/statistics/statistics-about-diabetes#:~:text=Prevalence%3A%20In%202018%2C%2034.2%20million,of%20the%20population%2C%20had%20diabetes.&text=Undiagnosed%3A%20Of%20the%2034.2%20million,and%207.3%20million%20were%20undiagnosed"> website </a>, more than 10% of Americans had diabetes in 2018. 

In 2017 alone, diabetes caused more than 200,000 deaths in America. In the same year, the total cost to treat diabetes is $327 billion.

These alarming numbers urge scientists to build more precise models to predict diabetes so that appropriate actions could be taken to combat the disease. That is precisely the aim of our project. We will use a public dataset to train and evaluate several machine learning models to predict diabetes. More precisely, we will use the data set "Pima Indians Diabetes Database"-which is available on <a href="https://www.kaggle.com/uciml/pima-indians-diabetes-database" > Kaggle </a> to find factors that could be correlated with diabetes and build our machine learning models. 


# Some challenges 

This problem poses some rather severe challenges. Some of them are:

(1) The dataset is relatively small. There are only 768 samples.

(2) Some of the features have missing values. Note that this is a subtle issue because missing values are recorded by 0 in the dataset. 

# Our methodology

We built a comprehensive pipeline to solve this problem. We chose decision trees and KNN models because of their interpretability both to doctors and patients. Furthermore, decision tree models also help us identify features that are most relevant in detecting diabetes. 

Additionally, we also built some neural network models. The use of deep learning in medical research has proved to be powerful lately, and we want to demonstrate that point in this project. 

# Our results 

In our project, we focus on optimizing our ability to predict someone with diabetes correctly. Most of our models can predict this disease at least 75% of the time. Our most powerful model (decision tree) can detect at least 93% of women with diabetes. 

# References 

[1] Jack W. Smith, J.E. Everhart, W.C. Dickson, W.C. Knowler, and R.S. Johannes, <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2245318/"> Using the ADAP Learning Algorithm to Forecast the Onset of Diabetes Mellitus </a>

[2] https://www.kaggle.com/ravichaubey1506/predictive-modelling-knn-ann-xgboost

[3] Aurélien Géron, Hands-On Machine Learning with Scikit-Learn and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems, Second edition
