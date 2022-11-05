# HRAnalytics
As industrialization is running at a decent pace, MNCs are establishing and growing day by day, with increase in the number of employees in companies.
Which asks for multiple HRs to analyse employees to decide the promotion of employees.<br>
This project helps in predicting promotion of employees based on their portfolios and KPIs, hence, shedding burden of HRs.

# Methodologies

### 1. Data preparation: <br>
<ul>
<li>The dataset, that we are working with, is unrefined and skimmed. I started with finding correlation between different columns and performed EDA.</li>
<li>I, then, did Feature Engineering: Broke down some columnns in multiple columns for a good, understandable heat map and for better training and testing. Also, I removed some useless columns.</li>
</ul>

### 2. Model training: <br>
<ul>
<li>I broke my dataset into two parts: x_start(without is_promoted column) and y_start(only is_promoted column ).</li>
<li>I, then, used resampling to balance my imbalanced dataset.</li>
<li>I split the data into x_train, y_train(for training) and x_test, y_test(for testing).</li>
<li>I implemented 3 models in major: Logistic Regression, Gradient Boosting, Random Forest.</li>
<li>I considered Random Forest as my Final Model.</li>
</ul>

### 3. Model testing: <br>
<ul>
<li>I tested my model on x_test and checked my accuracies on y_test.</li>
<li>I used confusion matrix, precision_score, recall_score and f1 score for checking model's accuracies.</li>
</ul>
   
