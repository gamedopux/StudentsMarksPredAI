Here,s how to use this StudentsMarksPredictionAI

1.Download the joblib file called 'StudentMarksPredAI.joblib'

2.Download scikit-learn by using 'pip install scikit-learn'

3.Create an python file and write this code 

import joblib
#Load models joblib file
model = joblib.load('StudentMarksPredAI.joblib')
#Enter the study hours total
print(model.predict([[2]]))




