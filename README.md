# password_strength_classifier
 Project Description: "Password Strength Classifier"

Objective: The goal of this project is to build a machine learning model that accurately assesses the strength of a given password.

Data: The project will use a dataset of passwords and their known strengths, such as length, complexity, and the use of special characters. The data will be trained based on the classification of - weak, medium and strong. Dataset - [Kaggle.com](https://www.kaggle.com/datasets/bhavikbb/password-strength-classifier-dataset)

Methodology: The project will use various machine learning algorithms, such as decision trees, random forests, tokenization to train a password strength classifier. The model will be trained on the pre-processed password data and then tested even on user inputs. The libraries and modules used are :
1. import pandas as pd
2. import numpy as np
3. from sklearn.feature_extraction.text import CountVectorizer
4. from sklearn.feature_extraction.text import TfidfVectorizer
5. from sklearn.ensemble import RandomForestClassifier
6. from sklearn.model_selection import train_test_split
7. import getpass

Results: The results of the project will be a machine learning model that can accurately assess the strength of a given password. The model will be tested on new, unseen data to ensure that it generalizes well to new passwords.

Conclusion: This project will provide a valuable tool for helping users create stronger passwords and improve the security of their accounts. The results of this project will also contribute to the wider field of computer security by exploring new ways to enhance password security and protect against unauthorized access.

References:

https://thecleverprogrammer.com/2022/08/22/password-strength-checker-with-machine-learning/

https://www.kaggle.com/datasets/bhavikbb/password-strength-classifier-dataset

