SMS Spam Detection Using Logistic Regression

This project demonstrates a machine learning model that classifies SMS messages as either spam or legitimate (ham). The model is trained using logistic regression and utilizes TF-IDF vectorization for feature extraction.

Overview:

- Dataset: spam.csv
- Algorithm: Logistic Regression
- Text Preprocessing: Lowercasing, punctuation removal, stopword filtering
- Feature Extraction: TF-IDF Vectorizer
- Achieved Accuracy: 96%
- Visualization: Confusion matrix represented as a line chart using Matplotlib

Model Summary:

1. Messages are cleaned and preprocessed to remove noise.
2. Labels are encoded: 'ham' as 0 and 'spam' as 1.
3. Text data is converted into numerical features using TF-IDF.
4. A logistic regression model is trained on the transformed data.
5. Model performance is evaluated using a confusion matrix and accuracy score.

Confusion Matrix:

              Predicted Ham   Predicted Spam
Actual Ham         978              41
Actual Spam         42              91

Files Included:

- spam_detector.ipynb : Contains the complete implementation of the model
- spam.csv : Dataset used for training and testing
- README.md : Project overview and summary

Future Improvements:

- Experiment with other classification models such as Naive Bayes or Support Vector Machines
- Add visual insights using Word Clouds
- Deploy the model using a simple web interface (e.g., Gradio or Streamlit)

Author:

Basil Diecon Disilva  
Artificial Intelligence and Data Science Student  
Chennai, India
