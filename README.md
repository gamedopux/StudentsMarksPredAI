Here,s how to use this StudentsMarksPredictionAI

1.Download the joblib file called 'StudentMarksPredAI.joblib'

2.Download scikit-learn by using 'pip install scikit-learn'

3.Move the model file in a folder you will be using it else it won,t work

4.Create an python file and write this code 

import joblib

model = joblib.load('StudentMarksPredAI.joblib')

print(model.predict([[2]]))

In the predicting model part type the total hours that students have studied in for eg. [[9]] output = [12.60135895]

Ignore the warning when running this code






