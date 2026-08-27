# SMS Spam Detection

A machine learning project that classifies SMS messages as spam or not spam.

## Objective

The objective of this project is to build a machine learning model that can automatically classify SMS messages into two categories: spam and ham (not spam).

## Technologies Used

- Python
- Pandas
- Scikit-learn
- TF-IDF
- Multinomial Naive Bayes
- Google Colab

## Workflow

1. Load and explore the SMS dataset
2. Separate messages and labels
3. Convert text into numerical features using TF-IDF
4. Split the data into training and testing sets
5. Train a Multinomial Naive Bayes classifier
6. Evaluate the model
7. Test the model on new SMS messages

## Model

Multinomial Naive Bayes was used for text classification because it is computationally efficient and commonly used for text-based classification tasks.

## Results

The model achieved approximately 96% accuracy on the test dataset.

## Example

Input:
"Congratulations! You have won a free prize. Click now!"

Prediction:
Spam

Input:
"Hey, I'll call you after class."

Prediction:
Ham

## Project File

`SMS_Spam_Detector.ipynb` contains the complete implementation.

## How to Run

Open the notebook in Google Colab and run the cells from top to bottom.
