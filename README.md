

# Basic Sentiment Analysis using Decision Tree Classifier

This project implements a basic sentiment analysis model using a Decision Tree Classifier to categorize messages as spam or not spam. The analysis uses the Bag of Words (BoW) approach to convert text into numerical features, allowing the machine learning model to process and classify the data.

## Project Overview

The project includes the following steps:
1. **Data Loading**: A function to load and process the training and test datasets, which contain labeled messages.
2. **Text Preprocessing**: Use of `CountVectorizer` to convert text messages into a Bag of Words representation.
3. **Model Training**: Training a Decision Tree Classifier using the training dataset.
4. **Model Evaluation**: Evaluating the model's performance using precision, recall, and f-measure metrics.

## Libraries Used

- **scikit-learn**: For machine learning model implementation and evaluation.
- **CountVectorizer**: For converting text data into feature vectors.
- **DecisionTreeClassifier**: For training the classifier on the dataset.
- **classification_report**: For generating a detailed performance report of the model.

## Data

The project uses two datasets:
- `smsspamdataset.training.csv`: The training data containing labeled messages.
- `smsspamdataset.test.csv`: The test data for evaluating the model's performance.

## Usage

1. **Data Loading**: The `csvload()` function is used to load the messages and their labels from the CSV files.
2. **Feature Extraction**: The text data is converted into a Bag of Words model using `CountVectorizer`.
3. **Model Training and Testing**: A Decision Tree Classifier is trained on the training data, and its predictions are tested on the test data.
4. **Evaluation**: The results are evaluated using the classification report to measure precision, recall, and f-measure.

## How to Run

1. Ensure you have the required Python libraries installed:
   ```bash
   pip install scikit-learn
   ```
2. Load the datasets by specifying their paths in the code.
3. Run the Jupyter Notebook to execute the model training and testing.

## Results

The output of the `classification_report` provides detailed metrics on how well the classifier performs in distinguishing between spam and non-spam messages.

## Improvements

Potential improvements for this project include:
- Enhancing feature extraction with techniques like TF-IDF.

### Contact
For any questions or feedback, please connect with me on [LinkedIn](https://www.linkedin.com/in/jayceeuzo/).
