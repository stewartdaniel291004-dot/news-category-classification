
# News Category Classification using Machine Learning

## Project Overview
This project classifies news articles into four categories:
- World
- Sports
- Business
- Sci/Tech

The project uses the AG News dataset and compares two
machine learning models using TF-IDF text features.

## Dataset
- Dataset: AG News
- Training articles: 120,000
- Testing articles: 7,600
- Categories: 4

## Methodology
1. Load and inspect the dataset.
2. Check for missing values and duplicates.
3. Convert text into numerical features using TF-IDF.
4. Train Logistic Regression and Linear SVM classifiers.
5. Evaluate accuracy and classification metrics.
6. Visualize model performance using charts and confusion matrices.
7. Test predictions on custom news examples.

## Models and Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 92.24% |
| Linear SVM | 92.43% |

Linear SVM achieved the highest accuracy in this experiment.

## Technologies
- Python
- Google Colab
- Pandas
- Matplotlib
- Scikit-learn
- Hugging Face Datasets

## How to Run
1. Open the notebook in Google Colab.
2. Install the required dependencies.
3. Load the AG News dataset.
4. Run the notebook cells from top to bottom.

## Project Status
Completed as a beginner machine learning NLP project.
