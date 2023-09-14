# sleeping.pattern
Sleep Disorder Evaluation and Sleep Pattern Enhancement Study
# real.estate.pp
Real Estate Price Prediction and Analysis
# How To see code in action
 * Step 1: Download data.csv as given data .
 * Step 2: Download Real.Estates.PP.ipynb.webloc .
 * Step 3: Save both the file in Desktop as real.estate.pp .
 * Step 4: Open Anaconda-Navigator and launch jupyter notebook .
 * Step 5: Go to Desktop -> real.estate.pp -> Real.Estates.PP and launch it .
   
Sleep Pattern Enhancement Study

# Step 1: Data Preprocessing:
* Importing a dataset from a CSV file and performing initial data exploration.
# Step 2: Feature Engineering:
* Splitting the "Blood Pressure" column into "SYSTOLIC" and "DIASTOLIC" columns.
* Creating a copy of the dataset for further processing.
* Encoding categorical variables like "Occupation," "BMI Category," "Gender," and "Sleep Disorder" using label encoding.
# Step 3: Data Analysis:
* Using data visualization (Seaborn) to explore the relationships between certain features and the "Sleep Disorder" variable.
# Step 4: Data Scaling:
* Applying Min-Max scaling to normalize the feature values.
# Step 5: Data Splitting:
* Splitting the data into training and testing sets.
# Step 6: Model Development:
* Implementing several machine learning algorithms, including K-Nearest Neighbors (KNN), Support Vector Classifier (SVC), Naive Bayes, Random Forest, Decision Tree, and AdaBoost.
* For the SVC and Random Forest models, performing hyperparameter tuning using GridSearchCV.
# Step 7: Model Evaluation:
* Evaluating each model's performance using classification reports.
# Step 8: Model Selection:
* Concluding that SVC, Random Forest, and Gradient Boosting Classifier are the most suitable algorithms based on their accuracy.
# Step 9: Model Saving:
* Saving the best-performing model (SVC) using pickle.
# Step 10: User Input and Prediction:
* Providing a code snippet for taking user input for various features and using the trained model to predict sleep disorders.
* Offering recommendations based on the predicted sleep disorder or declaring that the person is alright.
