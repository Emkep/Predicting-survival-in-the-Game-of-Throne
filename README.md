# Predicting-survival-in-the-Game-of-Throne
<b>Objective:</b> Purpose of the script is to predict as to whether a give character of the popular TV show 'Game of Throne' will survive or not, based on several features such as age, title, father, mother, spouse, heir, house, culture, etc. We do feature engineering in the given dataset to create additional features such as gender and surname.<br><br>
<b>Analytical Objective:</b> Analytical objective is to find the best predictive model where area under curve (AUC) is maximized, and other parameters like Train-Test gap and Confusion Matrix (contains Accuracy, Precision, Sensitivity, and Specificity of the model based on True Positives, True Negatives, False Positives, False Negatives of the predictions) are within the pre-defined thresholds.<br><br>
<b>Dataset:</b> The dataset has 1946 observations and 25 features. GOT_data_dictionary explains various features of the database.<br><br>
<b>Models:</b> We use Logistic linear regression tools from Statsmodels and sklearn, Decision Tree Classifier from sklearn, and RandomForestClassifier from sklearn.<br><br>
<b>Result:</b> We get the best results from the Random Forest Classifier, as below:<br><br>
Random Forest Training Accuracy: 0.7995<br>
Random Forest Testing  Accuracy: 0.8462<br>
Random Forest Train-Test Gap   : 0.0467<br>
Random Forest AUC Score        : 0.7328<br><br>
The important features to predict as to whether a Character will be alive or not are ‘popularity, ‘surname_Targaryen’, ‘culture_Valyrian’, and ‘book4_A_Feast_For_Crows’.
