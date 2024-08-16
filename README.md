This project demonstrates the use of Natural Language Processing (NLP) and machine learning to detect emotions in text. The model is trained using a Random Forest classifier to predict emotions such as joy, anger, sadness, and others based on the input text.
Project Steps:
Load the Dataset: The dataset is loaded into a Pandas DataFrame for further processing.
Data Cleaning: Text data is preprocessed by converting to lowercase, removing punctuation, numbers, and stopwords.
Label Encoding: The target emotion labels are encoded into numerical values using LabelEncoder.
Model Training: A Random Forest classifier is trained using TF-IDF features derived from the cleaned text data.
Model Evaluation: The model’s accuracy is calculated on a test set.
Technologies Used
Programming Language: Python
Libraries:
Data Handling: Pandas, NumPy
NLP: NLTK, re
Machine Learning: Scikit-learn
Model: Random Forest Classifier
