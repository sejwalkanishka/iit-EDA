About data:
The data contains two files: train.csv and test.csv

train.csv - which contains the training set observations. 2,016 rows, which have the target variable (age_group) values as well for training the model.

test.csv - which contains the testing set observations. 312 rows, with the target column missing. Use the trained model to predict and submit the values of the target column.


Additionally, a sample-submission.csv file is provided to show you what your CSV submission should look like. Note that the header has 'age_group' for the column name and the number of rows is equal to the number of rows in the test set.

Respondents 65 years old and older were labeled as “Senior” and all individuals under 65 years old as “Adult”. 

Make sure to mark Adult as 0 and Senior as 1. This is important. Look at sample submission file, it accepts only 0 or 1. 

Target Variable Classes:
age_group: Adult - 0

age_group: Senior - 1


Features:
The dataset contains the following features:

SEQN: Sequence number (identifier)

RIAGENDR: Respondent's Gender (1=Male, 2=Female)

PAQ605: Physical activity questionnaire response: If the respondent engages in moderate or vigorous-intensity sports, fitness, or recreational activities in the typical week

BMXBMI: Body Mass Index

LBXGLU: Glucose level

DIQ010: Diabetes questionnaire response

LBXGLT: Glucose tolerance (Oral)

LBXIN: Insulin level
