# CreditCardFraudProject Description

Buisness problem: The problem I will be trying to tackle is dealing with credit card fraud. There are enormous amounts of transactions passed each day, and it is important that our model can respond quickly and accuratly to ensure the safety and security of our customers. However many challenges come with creating the model. The dataset will be massive, and with that most of the transactions within the dataset will be non fraudulent. In fact in my exploratory data analysis I found that there were 249,243 non fraudulent cases compared to 456 fraudulent cases. In order to help prove accuracy for imbalanced data we will have to pay more attention to our recall score, rather than overall accuracy. In addition, to protect the privacy of the customers PCA was done ahead of time in order to keep the data secure. 

Plan of attack: In order to tackle this problem, we will first visualize and inspect the dataset, as well as look at any possible correlations within the dataset. We will also make sure that the dataset is cleaned and that no data is missing. We will then focus on model testing and making sure we have the best parameters necessaary for the most accurate version of our model. 

Importing libraries: The libraries I will be using for this project will be numpy, pandas, matplotlib, and seaborn.

Inspecting the dataset: First, I import the dataset with pandas and read in the head of the dataset. I can see that the data had undergone PCA and has seemed to be scaled as well, eliminating the necessity to do this later although can be simple added with a StandardScaler. I then continue inspecting some important features such as mean and standard deviation, and then split the data by normal and fraud cases to check their important features as well. Next I move on to check if there is any missing data, which seems to be contained in one row. I simply remove this one row, leaving us with a clean dataset.  

Visualizing the data: My next step was to visualize some of the data, but due to PCA it was unnecessaary to do much except use seaborn to create a heatmap of the correlations. I used this heatmap on the dataset as a whole, and then seperatly on the normal and fraud cases, where I was able to view some of the more correlated data points. 

Data preprocessing: 

Model testing: 

Grid search and cross validation: 

Final model selection: 
