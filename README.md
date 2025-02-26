# SPAM-SMS-DETECTION
Overview
This project aims to build a machine learning model to detect spam messages in SMS. The model takes an SMS as input and predicts whether the message is spam or not.

Technology Used
Python

Scikit-learn

Pandas

NumPy

Streamlit

Features
Data Collection: The dataset used is the SMS Spam Collection dataset from Kaggle, containing over 5,500 SMS messages labeled as spam or not spam.

Data Cleaning and Preprocessing: Handling null and duplicate values, converting text to lowercase, removing special characters, stop words, and punctuation, and stemming the data.
Exploratory Data Analysis: Insights into the dataset, including character, word, and sentence counts, correlation between variables, and visualizations like word clouds.

Model Building and Selection: Multiple classifiers like Naive Bayes, Random Forest, KNN, Decision Tree, Logistic Regression, ExtraTreesClassifier, and SVC were tried. The best classifier was chosen based on precision.

Web Deployment: The model was deployed on the web using Streamlit, with a simple input box for users to input a message and get a prediction.

Usage
Clone the repository.

Install the required Python packages using pip install -r requirements.txt.

Run the model using streamlit run app.py.

Visit localhost:8501 on your web browser to access the web app.
