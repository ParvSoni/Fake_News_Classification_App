# Fake_News_Detection_App
The Fake News Detection App Project is a data science and machine learning endeavor aimed at developing a user-friendly application for the identification of fake news articles. In this project, a dataset of news articles was preprocessed, and a machine learning model, employing an advanced technique known as the Decision Tree Classifier, was trained to classify articles as either fake or real. The final output is a streamlined, user-friendly web application built with Streamlit, enabling users to easily verify the authenticity of news articles.
## Project Steps:
### Dataset Preprocessing:
Data Collection: The project began with the collection of a diverse dataset containing labeled news articles, specifying whether they were real or fake.
Data Cleaning: The collected dataset was cleaned to remove any inconsistencies, such as missing values or irrelevant features.
Text Preprocessing: Text data underwent preprocessing, including lowercasing, removal of stop words, punctuation, and tokenization. This made the text data suitable for machine learning algorithms.
### Feature Engineering:
TF-IDF Vectorization: The textual content of the news articles was transformed into numerical features using the Term Frequency-Inverse Document Frequency (TF-IDF) vectorization technique. TF-IDF represents the importance of words in documents.
### Model Selection:
Decision Tree Classifier: An advanced machine learning technique, the Decision Tree Classifier, was chosen as the classification algorithm. This algorithm is known for its interpretability and ability to handle both numerical and categorical features.
### Model Training:
Data Split: The dataset was divided into training and testing subsets to evaluate the model's performance.
Model Training: The Decision Tree Classifier was trained on the training data, and hyperparameter tuning was performed to optimize model accuracy.
### Model Evaluation:
Model Metrics: Various evaluation metrics such as accuracy, precision, recall, and F1-score were calculated to assess the model's performance.
Cross-validation: Cross-validation was utilized to ensure that the model's performance was robust and not overfit to the training data.
### Building the Streamlit App:
User Interface: A user-friendly web application was developed using Streamlit, a Python library for creating interactive web apps with minimal code.
Input Interface: The app allows users to input a news article for analysis.
Classification Output: The application provides an instant classification result, indicating whether the input article is real or fake.
Visualizations: Visual aids, such as decision tree diagrams, could be incorporated to help users understand how the model arrived at its decision.
