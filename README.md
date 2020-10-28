### Problem Statement
# Bank Business Use Case
There has been a revenue decline for a Portuguese bank and they would like to know what actions to take. After investigation, they found out that the root cause is that their clients are not depositing as frequently as before. Knowing that term deposits allow banks to hold onto a deposit for a specific amount of time, so banks can invest in higher gain financial products to make a profit. In addition, banks also hold better chance to persuade term deposit clients into buying other products such as funds or insurance to further increase their revenues. As a result, the Portuguese bank would like to identify existing clients that have higher chance to subscribe for a term deposit and focus marketing efforts on such clients.

### Data Science Problem Statement
Predict if the client will subscribe to a term deposit based on the analysis of the marketing campaigns the bank performed.

### Evaluation Metric
We will be using AUC - Probability to discriminate between subscriber and non-subscriber.

### Objective of this template notebook
The main objective of this template is to take you through the entire working pipeline that you may follow while approaching a Machine Learning problem.

We will be defining a task to be performed and write the code to solve the task.

The tasks performed below should serve as a good guide regarding the steps that you should go about a Machine Learning Problem. But kindly do not restrict yourself to only the tasks that have been performed in this notebook and feel free to bring your ideas,skills and strategies and implement them as well.

#### Word of caution
This template is just an example of a data-science pipeline, every data science problem is unique and there are multiple ways to tackle them.

### Understanding the dataset
#### Data Set Information

The data is related to direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be subscribed ('yes') or not ('no') subscribed.

There are two datasets: train.csv with all examples (32950) and 14 inputs including the target feature, ordered by date (from May 2008 to November 2010), very close to the data analyzed in [Moro et al., 2014]

test.csv which is the test data that consists of 8238 observations and 13 features without the target feature

Goal:- The classification goal is to predict if the client will subscribe (yes/no) a term deposit (variable y).

### Features

![test1](https://user-images.githubusercontent.com/64673748/97472931-65ce9100-1970-11eb-8741-8342bf00f3eb.png)

### Target variable (desired output):

![test2](https://user-images.githubusercontent.com/64673748/97472953-69faae80-1970-11eb-91ec-d2d629d22972.png)

### Categorical and Numeric Data
#### Categorical Data
Categorical data is a type of data that can be stored into groups or categories with the aid of names or labels.

For example, gender is a categorical data because it can be categorized into male and female according to some unique qualities possessed by each gender.

#### Numeric Data
Numerical data is a type of data that is expressed in terms of numbers rather than natural language descriptions. Ex: Person's height, weight, IQ etc.


### The folder 'Data' contains the dataset used, and the folder 'Notebook' contains both the file related to the Explonatory Data Analysis(EDA) and the ML Model used.

Any queries regarding the project?? drop a mail to - revnth@outlook.com
