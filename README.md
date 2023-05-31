# **Social Media Friend Recommendation System**
A social media friend recommendation system is a project that suggests potential friends or connections to users based on their interests, demographics, location, and other relevant factors. This repository contains the code and resources to build and deploy such a recommendation system.

## **Table of Contents**
- **[Introduction](#introduction)**
- **[Features](#features)**
- **[Requirements](#requirements)**
- **[Dataset](#dataset)**
- **[Implementation](#implementation)**

## **Introduction**
The social media friend recommendation system aims to enhance user experience and engagement on social media platforms by suggesting connections that align with users' interests and preferences. This project utilizes machine learning techniques to analyze user data, extract relevant features, and calculate user similarities to generate personalized friend recommendations.

## **Features**
- Extraction of user features, including interests, demographics, location, and mutual friends.
- Calculation of user similarities based on cosine similarity or other suitable similarity measures.
- Personalized friend recommendations based on user similarities and preferences.
- Integration of social graph and user connections for improved recommendations.
- Evaluation metrics to measure the performance and effectiveness of the recommendation system.
- Example code and data to get started quickly.

## **Requirements**
Python 3.x
Pandas
NumPy
scikit-learn

## **Dataset**
The Link to the dataset : https://www.kaggle.com/datasets/arindamsahoo/social-media-users

The dataset used for this project should include the following fields:

UserID: Unique identifier for each user.
Name: User's name or username.
Gender: User's gender.
DOB: User's date of birth.
Interests: User's interests, separated by commas.
City: User's city or place of residence.
Country: User's country.
Ensure that your dataset is properly formatted and includes sufficient information to extract features for user similarity calculations.

## **Implementation**
The project implementation includes the following components:

- Feature extraction: Extracting relevant features such as interests, demographics, location, and mutual friends.
- Similarity calculation: Using cosine similarity or other suitable similarity measures to compute user similarities.
- Personalized recommendations: Generating friend recommendations based on user similarities and preferences.

