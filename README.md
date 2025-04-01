This project demonstrates how to build a machine learning model to predict the likelihood of heart disease using a dataset that includes various health-related features. We used a k-Nearest Neighbors (k-NN) classifier to predict whether a patient has heart disease based on features like age, sex, exercise capacity, and chest pain type.
This project involves predicting whether a patient has heart disease or not using a dataset that contains various health-related features. The k-NN algorithm was chosen as the model, and we experimented with different hyperparameters (such as n_neighbors and metric) to optimize the model’s performance. We also focused on addressing class imbalance in the dataset to ensure fairness and accuracy in the predictions.

The main steps of the project are as follows:

Data Preprocessing: Loading and exploring the dataset, handling missing values, and performing feature scaling.

Model Building: Implementing a k-NN classifier and evaluating it using cross-validation.

Hyperparameter Tuning: Using GridSearchCV to search for the best hyperparameters.

Evaluation: Analyzing the model’s performance on both training and test datasets.
Results
After tuning the hyperparameters and evaluating the model on both the validation and test sets, we obtained the following results:

Test Accuracy: ~87%

Best Parameters: n_neighbors = 19 and metric = Minkowski

Observations:
The model performed better on the test set than on the validation set, which can be attributed to dataset imbalance and other factors like the prevalence of male patients.

We used cross-validation to get a more reliable estimate of model performance during hyperparameter tuning.

Improvements
Data Balancing: The dataset was imbalanced, and using techniques like oversampling or undersampling could help improve the model's fairness.

Hyperparameter Tuning: More fine-grained searches over the hyperparameters could yield better results.

Additional Features: Exploring more features, or removing less relevant ones, might further improve model performance.

