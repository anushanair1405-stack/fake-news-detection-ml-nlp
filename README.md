# Fake News Detection Using Machine Learning and NLP

## Project Overview
This project uses Machine Learning and Natural Language Processing (NLP) to classify news articles as FAKE or REAL using patterns learned from labelled news data.

## Objectives
- Preprocess news article text.
- Convert text into numerical features using TF-IDF.
- Train a Logistic Regression model.
- Evaluate the model using accuracy, precision, recall, and F1-score.
- Predict whether new news text is classified as FAKE or REAL.

## Technologies Used
- Python
- Google Colab
- Pandas and NumPy
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression

## Methodology
1. Load the labelled news dataset.
2. Handle missing values.
3. Combine the title and article text.
4. Split the data into 80% training and 20% testing sets.
5. Apply TF-IDF vectorization.
6. Train the Logistic Regression model.
7. Evaluate model performance.
8. Predict the label of new news text.

## How to Run
1. Open the notebook in Google Colab.
2. Upload the labelled news dataset when prompted.
3. Run all cells in order.
4. Review the evaluation metrics.
5. Enter news text to test a prediction.

## Results
Run the notebook and add the actual accuracy, precision, recall, and F1-score from your results.

## Limitations
The model learns patterns from its training data. It does not independently verify news facts, and predictions may be incorrect.

## Future Scope
- Develop a Streamlit web application.
- Test on more recent news datasets.
- Compare additional machine learning models.

## Author
Anusha Nair

## Disclaimer
This project is for educational purposes. A prediction is not proof that a news article is true or false.
