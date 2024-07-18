# Spam-Detection
To detect whether a website is spam or not using machine learning

# It can perform
Imports necessary libraries (pandas, sklearn modules).
Defines a small dataset (data) with example website texts and labels.
Creates a DataFrame (df) from the dataset.
Uses TfidfVectorizer to convert the website text data into numerical features (X).
Splits the data into training and testing sets (X_train, X_test, y_train, y_test).
Initializes a LogisticRegression model and trains it using the training data (model.fit).
Makes predictions on the test data (X_test) and calculates the accuracy of the model.
Uses the trained model to predict whether a new website text (new_website_text) is spam or not (prediction).
