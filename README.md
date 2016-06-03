# machine-learning-python
Learning machine learning with python. These are hightlights and points I learned from the *Understanding Machine Learning with Python* on Pluralsight.

##What is Machine Learning
- Data gets passed to algorithm and analyzes the data to create a model
## Types of Machine Learning
- Supervised - Given a set of training data, the algorithm analyzes that data and createsa  model to predict a value. 
 - Value Prediction
 - Needs training data containg value being predicted
 - Trains model predcits value in new data
 - For example, predicting a price of the house based off of a data set of existing house attributes such as rooms, location, square feet.
- Unsupervised - Looking at cluster of like data with similar traits, classifies data to a model to predict a value. 
 - Identiy cluster of like data
 - Data does not contain cluster membership.
 - Model proives access to data by cluster. 
 - For example, determining pitch of a voice to determine a particular voice.

##Why?
Data Science is a blend of Software development and Math/Statistics

##Tools
- Python
 - numpy - scientific computing
 - pandas - data frames
 - matplotlib - 2d plotting
 - scikit-learn
  - Algorithms
  - Pre-processing
  - Performance evaluation
  - More...
- Jupyter Notebook
 - Notebook that contains code and text
 - Shareable
 - Multiple language support
 - [Anacaoda Distribution](https://www.continuum.io/downloads)

##Machine Learning Workflow
- An orchestrated and *repeatable pattern* which systematically transforms and processes information to create predictive solutions.
- Steps
 - Asking the right question
 - Preparing the Data
 - selecting the algorithm
 - Training the model
 - Testing the model
- Guidelines
 - Early steps are most important
 - Expect to go backwards 
  - later knowledge effects previous steps
- Data is never as you need it
 - Data will have to be altered
- More data is better
 - Better results
- Don't purse a bad solution
 - reevaluate, fix or quit
 
 ###  Asking the right question
 - Predict if a person will develop diabetes"
 - Define Solution Statement Goals
  - Understand features in data
  - IDentitfy critical features
  - Focus on at risk population

### Preparing the Data
- Tidy datasets are easy to manipulate, model,and visaulize, and have a specific structure
 - each *variable* is a *column*
 - each *observation* is a *row*
 - each type of *observational unit*  unit is a *table*
- Getting Data
 - Find via Google, Gov't DB, professional Data Srouces, your company, department, etc.
- Data Rules
 1. Closer the data is to what you are predicting the better
 2. Data will never be in the format you need.
- Remove duplicated columns
- Correlated Columsn - Same information but in a different format.
 - Example - an Id as a string vs an ID as a number
 - this can amplify data as a bias, add little info, can cause algorithms to get confused.
