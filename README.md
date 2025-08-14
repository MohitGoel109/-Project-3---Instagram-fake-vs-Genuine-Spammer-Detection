# -Project-3---Instagram-fake-vs-Genuine-Spammer-Detection
This project aims to identify fake Instagram accounts by analyzing user profile features and applying machine learning classification models. The dataset contains labeled accounts (real or fake) with various metadata collected from Instagram profiles.

Dataset Features

profile pic – Binary indicator of whether the account has a profile picture.

nums/length username – Ratio of numeric characters to total username length.

fullname words – Count of words in the full name.

name==username – Binary flag for identical full name and username.

description length – Number of characters in the bio.

external URL – Binary indicator of a website link in bio.

private – Privacy status of the account.

#posts – Number of posts.

#followers – Number of followers.

#follows – Number of accounts followed.

fake – Target label (1 = fake, 0 = real).

Workflow

Data Exploration – Understanding class distribution, correlations, and missing values.

Data Preprocessing – Handling null values, scaling numerical features, and encoding categorical variables.

Model Training – Implementing multiple classifiers such as Logistic Regression, Random Forest, Decision Tree, and Support Vector Machine (SVM).

Model Evaluation – Measuring performance using Accuracy, Precision, Recall, and F1-score.

Hyperparameter Tuning – Using GridSearchCV to optimize model performance.

Technologies Used

Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Environment: Google Colab

Insights

The analysis reveals clear patterns: fake accounts often lack profile pictures, have usernames with more numbers, very few posts, and suspicious follower-to-following ratios. Models like Random Forest and SVM achieve high accuracy in classifying accounts.

Applications

Social media security

Automated moderation tools

Spam detection in online communities

This project demonstrates a complete supervised machine learning workflow — from raw data preprocessing to training and evaluating classification models — with practical applications in detecting online fraud and fake accounts.
