# Training classification models

Introduction :
<br>
Once your data has been processed, it is time to use it to train models. We
will start with classification models. This homework is intended to give you a
brief introduction on how to train classification models. It covers the following
topics :
<br>
• Perform classification with:<br>
-Decision Tree Classifier.<br>
-K-Nearest Neighbors Classifier.<br>
-Logistic regression Classifier.<br>
• Generate predictions from these models.<br>
• Plot confusion matrices.<br>
• Find accuracies of these models<br>


Tasks :<br>
Complete the following tasks, and export your work as a pdf file. Submit the
report along with the additional files (saved figures and data files) on Canvas.<br>
1. Load the patient.csv data file.<br>
2. Create a DataFrame called data using the following variables:<br>
Age<br>
Gender<br>
Systolic<br>
Diastolic<br>
Smoker<br>
Set Smoker as the response variable (Y), and select everything else
as a predictor variable (X).<br>

3. Train a Decision Tree Classifier Model<br>
Create a decision tree classifier.<br>
4. Plot the Systolic vs Diastolic data. Color by their response variable. And
change the style based on whether the prediction is correct or not.
Are the clusters clearly identifiable?<br>
Change the X-axis to other parameters such as gender and age. Do
they have better clustering?<br>
What is the Accuracy for the decision tree model? Is it a good?<br>
5. Plot the Confusion Matrix.<br>
How many false positives and false negatives do you have?<br>
6. Repeat the above steps, but choose only the Systolic and Diastolic values
as predictor variables.<br>
Does this improve the accuracy of the model?<br>
7. Make predictions using the trained model for the following inputs:<br>
Diastolic=90 mmHg, Systolic=125 mmHg<br>
Diastolic=85 mmHg, Systolic=130 mmHg<br>
8. Repeat the steps above for a KNN Model.<br>
9. Repeat the steps above for a Logistic Regression Model.<br>
What are the probability values generated in the Logistic regression
model using the input data.<br>
10. What was the best and worst model? What are their Accuracies?<br>
