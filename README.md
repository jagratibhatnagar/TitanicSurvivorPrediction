# TitanicSurvivorPrediction

                                        Project 3: Titanic Survivor Prediction
                                        
__Problem Statement:__ Complete the analysis of what sorts of people were likely to survive.
In particular, we ask you to apply the tools of machine learning to predict which passengers survived the Titanic tragedy. 

Dataset has been downloaded from: __*https://www.kaggle.com/c/titanic/data*__

__Steps Involved:__
  1.	Importing necessary libraries
  2.	Loading dataset
  3.	Exploring or analyzing Data
  
              Data Dictionary:

                  •	Survived: 0 = No, 1 = Yes

                  •	pclass: Ticket class 1 = 1st, 2 = 2nd, 3 = 3rd

                  •	sibsp: # of siblings / spouses aboard the Titanic

                  •	parch: # of parents / children aboard the Titanic

                  •	ticket: Ticket number

                  •	cabin: Cabin number

                  •	embarked: Port of Embarkation C = Cherbourg, Q = Queenstown, S = Southampton

  4.	Data Visualization
  
            Bar Chart for following Categorical Features:

                •	Pclass

                •	Sex

                •	SibSp ( # of siblings and spouse)

                •	Parch ( # of parents and children)

                •	Embarked

                •	Cabin
          
  5.	Feature Engineering
  
  Feature engineering is the process of using domain knowledge of the data
  to create features (feature vectors) that make machine learning algorithms work.
  feature vector is an n-dimensional vector of numerical features that represent some object.
  Many algorithms in machine learning require a numerical representation of objects,
  since such representations facilitate processing and statistical analysis.
  
  6.	Modelling
  
      •	Cross Validation(k-Fold)
          	kNN
          	Decision Tree
          	Random Forest
          	Naïve Bayes
          	SVM
          
  7.	Testing

__Output:__ Output of tested data is stored in csv file Submission.csv
