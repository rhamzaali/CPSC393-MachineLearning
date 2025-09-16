### Assignment 01

#### Details
Using the Assignment 01 dataset (link on Canvas and GitHub), build the models listed below using all X variables to predict Y. Make sure that input variables are standard scaled (Z-score) appropriately. 

- Load the data and create a 80/20 Train/Test split
- Use Pipelines in sklearn to build a Support Vector Machine model. Use GridSearchCV to choose the kernel (either linear or rbf), C (choose from [0.001, 0.01, 1, 5, 25, 50]), and gamma (choose from [0.001, 0.01, 0.1, 0.5, 1, 2, 5]). Print out the Train and Test accuracies of the best model. Also print the ROC AUC value and the confusion matrix of Test data. 
- Use Pipelines in sklearn to build a Logistic Regression model on the data using the same Train/Test split as before. Print out the Train and Test accuracies of the best model. Also print the ROC AUC value and the confusion matrix of Test data. 
- Use Pipelines in sklearn to build a k-Nearest Neighbors model on the data using the same Train/Test split as before. Use GridSearchCV to choose n_neighbors value. Print out the Train and Test accuracies of the best model. Also print the ROC AUC value and the confusion matrix of Test data. 
 

#### Technical Report
You will also prepare a technical report to be submitted along side your code. Technical reports provide a good way of detailing your work to non-technical stakeholders. Here are some examples of technical reports from students: https://cs229.stanford.edu/projects2014.html Links to an external site. For this class, you will use the following format:

Analysis: Any exploratory data analysis of your data as well as general summarization (summary statistics, correlation matrices, plots comparing features etc.) Tell the reader the types of variables you have and some information about them; plots and tables are always great. Also include any data cleaning or joining you performed. 

Methodology: Explain the structure of your models. Describe what hyperparameter tuning you performed and which hyperparameters you ended up selecting. Also describe how these parameters control your models. Someone should be able to read this section and be able to tell exactly what model you have used. Keep it non-technical (no need to include any code.)

Results: Discuss in detail how your models performed based on the metrics you found. Compare the performance of the three models, and provide a justification of which model you would want to use "in production". 

Reflection: Reflect on what you learned or discovered in the process of doing this assignment. Write about any struggles you had (and hopefully overcame) during the process. Explain what things you would do differently in the future or ways you would approach similar problems in the future. 


#### Extra Credit
Using a dimensionality reduction algorithm like Principal Component Analysis (PCA), reduce your test dataset to two features. Next, create two plots: (1) plot your testing datapoints in 2D colored by the actual target, and (2) plot your testing datapoints in 2D colored by the predicted target. In your Technical Report, describe your methodology and discuss your findings. 

 
#### What to turn in:
A compressed or zipped folder that contains the following:

- A PDF of your Technical Report
- Your code as a .py, .ipynb
- A README file in .txt or .md format