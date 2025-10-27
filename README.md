# Team-06
Smart Healthcare

Task 03

1. I import librabries- pandas, sklearn, seaborn, and matplotlib for data handling, model training, evaluation, and visualization respectively

2. Then I created a small dataset with their severity and convert it into a pandas Dataframe

3. Then I splitted the data into 75% training and 25% testing sets, and used TfidfVectorizer to convert symptom text into numerical feature vectors

4. Used Logistic Regression and fit it on the TF-IDF transformed training data, then I displayed the classification report (precision, recall, F1-score)

5. Next I generated a visual confusion matrix using seaborn heatmap

6. Then I took input from user and predicted the severity with confidence value
