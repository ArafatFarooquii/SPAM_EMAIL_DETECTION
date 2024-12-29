# spam_email_detection
Welcome to the Spam Email Detection project! This repository contains code for building a machine learning model to classify emails as either spam or non-spam (ham).
Table of Contents

Overview

Features

Technologies Used

Dataset

Model Training

Usage

Results

Future Enhancements

Contributing

License
Overview

This project implements a spam email detection system using a logistic regression model. It preprocesses email text data, extracts relevant features, and classifies the emails. The system is efficient and achieves high accuracy on both training and test datasets.

Features

Preprocessing of email data including handling missing values and converting text labels to numerical format.

Feature extraction using TF-IDF Vectorization.

Spam classification using Logistic Regression.

High accuracy on training and test datasets.

Example input and output demonstration for user mail classification.

Technologies Used

Programming Language: Python

Libraries: pandas, numpy, scikit-learn

Machine Learning Algorithm: Logistic Regression

Dataset

The dataset used for this project is a collection of labeled email messages with the following columns:

Category: Indicates whether the email is spam (0) or ham (1).

Message: The email content.

Dataset Statistics

Total emails: 5,572

Spam emails: ~13.4%

Ham emails: ~86.6%

Note:

The dataset is not included in this repository. However, you can use publicly available datasets such as the SMS Spam Collection Dataset.

Model Training

Data Preprocessing:

Handle missing values.

Convert categorical labels to numerical (spam: 0, ham: 1).

Split the dataset into training and testing sets (80% training, 20% testing).

Feature Extraction:

Use TF-IDF Vectorization to convert email text into numerical features.

Model Training:

Train a Logistic Regression model on the training dataset.

Evaluate the model using accuracy scores on both training and testing datasets.

Usage

Prerequisites

Ensure you have Python 3.x installed and the required libraries. You can install the dependencies using:

pip install -r requirements.txt

Running the Project

Clone this repository:

git clone https://github.com/yourusername/spam-email-detection.git

Navigate to the project directory:

cd spam-email-detection

Run the script:

python main.py

Input your email text to check whether it is spam or not.

Results

Training Accuracy: 96.70%

Test Accuracy: 96.59%

The model shows consistent performance across training and test datasets, indicating effective generalization.

Example Output

Input Email:

As a valued customer, I am pleased to advise you that following recent review of your Mob No. you are awarded with a £1500 Bonus Prize, call 09066364589

Output:

SPAM_MAIL

Future Enhancements

Incorporate more advanced models like Naive Bayes or ensemble techniques for comparison.

Extend the model to handle multi-language email datasets.

Build a user-friendly web or mobile interface for real-time email classification.

Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure your code adheres to the project’s coding standards and includes appropriate documentation.

License

This project is licensed under the MIT License. See the LICENSE file for details.
