# Sentiment Analysis of Amazon Alexa Reviews

# Project Overview:

This project focuses on performing sentiment analysis on reviews of Amazon Alexa. The primary goal is to analyze the sentiment (positive, negative, neutral) expressed in the customer reviews and to derive insights from the data.

# Table of Contents:

Project Overview

Dataset

Installation

Results

Contributing

Acknowledgements

# Dataset:

The dataset used in this project consists of customer reviews of Amazon Alexa products. It contains the following columns:

rating: 

The rating given by the customer (1 to 5 stars).

review: 

The text of the customer review.

date: 

The date the review was posted.

verified_purchase: 

Indicates whether the purchase was verified (true/false).

Link: https://www.kaggle.com/datasets/sid321axn/amazon-alexa-reviews

# Installation:
To run this project, you need to have Python installed. You can install the required packages using the following commands:
## HOW TO RUN

Step 1: Clone the repository
```
git clone https://github.com/Surbhit01/Amazon-Alexa-Reviews.git
```

Step 2: Open the cloned repository and create a conda environment. Activate the new environment
```
conda create -n amazonreview python=3.10
```
```
conda activate amazonreview
```

Step 3: Install the requirements file
```
pip install -r requirements.txt
```

Step 4: Run the app
```
flask --app api.py run
```

Step 5: The app will run on port 5000. 
```
localhost:5000
```
# Data Preprocessing:

Load the dataset.

Clean and preprocess the text data (remove stopwords, punctuation, etc.).

Tokenize and vectorize the text data.

# Exploratory Data Analysis:

Analyze the distribution of ratings.

Visualize the most common words in positive and negative reviews.

# Model Training:

Split the data into training and testing sets.

Train a machine learning model (e.g., Random Forest, Decision Tree ) to classify the sentiment of the reviews.

# Evaluation:

Evaluate the model's performance using metrics like accuracy, precision, recall, and F1-score.

# Visualization:

Visualize the results and insights derived from the analysis.

You can run the Jupyter notebook provided in the repository to execute the above steps.

# Results:
The model achieves an accuracy of 94% on the test set. The following are some of the key insights derived from the analysis:

Positive reviews often mention words like "great", "love", "easy", etc.
Negative reviews frequently include words like "problem", "bad", "disappointed", etc.

# Contributing:
We welcome contributions to this project. If you would like to contribute, please fork the repository and submit a pull request. Make sure to follow the coding guidelines and include appropriate tests.


# Acknowledgements
We would like to thank kaggle for providing the dataset. We also appreciate the contributions of the open-source community in developing the tools and libraries used in this project.



