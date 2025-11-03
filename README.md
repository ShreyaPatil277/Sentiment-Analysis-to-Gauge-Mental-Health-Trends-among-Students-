# Sentiment-Analysis-to-Gauge-Mental-Health-Trends-among-Students-



📌 Project Overview
This repository contains the official implementation of our research paper: "Sentiment Analysis to Gauge Mental Health Trends among Students".

The project aims to automatically detect and classify mental health conditions from textual data using a state-of-the-art Deep Learning approach. By fine-tuning the DistilRoBERTa-base transformer model, we can categorize student statements into one of seven mental health categories, providing a powerful tool for early intervention and trend analysis.

🎯 Key Features
Multi-Class Classification: Accurately classifies text into 7 mental health categories:

😊 Normal
😔 Depression
⚠️ Suicidal Thoughts
😥 Anxiety
🔄 Bipolar Disorder
😫 Stress
🧩 Personality Disorder

State-of-the-Art Model: Utilizes a fine-tuned DistilRoBERTa model, offering a balance between high accuracy and computational efficiency.

Comprehensive Text Analytics: Includes Exploratory Data Analysis (EDA), TF-IDF feature extraction, Bigram analysis, and PCA visualization.

Visual Analytics: Generates insightful visualizations like Word Clouds, Dendrograms, and Bar Plots to understand linguistic patterns associated with different mental health conditions.

Scalable & Reproducible: A well-documented, end-to-end pipeline from data preprocessing to model evaluation.

.

🗂️ Dataset
The model is trained on the "Sentiment Analysis for Mental Health" dataset from Kaggle, consisting of 53,043 text statements labeled across the seven categories mentioned above.

Class Distribution:
Normal: 16,351 (30.8%)
Depression: 15,404 (29.0%)
Suicidal: 10,653
Anxiety: 3,888
Bipolar: 2,877
Stress: 2,669
Personality Disorder: 1,201 (2.3%)

📊 Results and Insights
The fine-tuned RoBERTa model achieved high performance in multi-class mental health classification (specific metrics to be added from your paper).

Key Linguistic Insights from Visualizations:

Common Emotional Words: Words like "feel", "want", and "know" were dominant across anxiety and depression-related posts.

Prevalent Bigrams: Phrases such as "feel like", "just want", and "don't know" highlighted expressions of emotional struggle and uncertainty.

Distress Indicators: Bigrams like "want die" were identified as strong indicators of severe distress, particularly in the "Suicidal" category.
