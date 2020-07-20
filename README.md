# Who-will-SURVIVE

The project is based on predicting who will survive on sinking titanic using  Machine Learning .Find the relevant data from the sources like: Kaggle, UCI etc. Download the data set in .csv format from ⦁ www.kaggle.com


Steps followed to complete this project:
 Download the data set in .csv format from ⦁	www.kaggle.com
 Import the data from the data set
 Read In and Explore the Data and then
 We're going to consider the features in the dataset and how complete they are 
     Numerical Features: Age (Continuous), Fare (Continuous), SibSp (Discrete), Parch (Discrete)
     Categorical Features: Survived, Sex, Embarked, Pclass
     Alphanumeric Features: Ticket, Cabin
Then visualize our data so we can see whether our predictions were accurate!
Clean our data to account for missing values and unnecessary information such as
we need to fill in the missing values in the Embarked feature
Next we'll fill in the missing values in the Age feature
replace various titles with more common names
map each Age value to a numerical value
drop the name feature since it contains no more useful information
map each Embarked value to a numerical value
separate the fare values into some logical groups as well as filling in the single missing value in the test datase
Implement these Machine Learning algorithms to test the accuracyof our different models -
logistc regression 
svm

At last we have list of person who will survive. Compare  the models  on the basis of their accuracy and select the best working model for predictions.
