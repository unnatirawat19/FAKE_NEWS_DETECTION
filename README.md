
# Fake News Detection

## Overview
This project aims to classify news articles as real or fake using Natural Language Processing (NLP) and machine learning techniques. The dataset is preprocessed using text cleaning, stemming, and vectorization, and a Logistic Regression model is trained to make predictions.

## Features
- Preprocessing of textual data (handling missing values, stemming, and stopword removal).
- Conversion of text into numerical form using TF-IDF vectorization.
- Training and evaluation of a Logistic Regression model.
- Prediction system to classify news articles.

## Technologies Used
- Python
- NumPy
- Pandas
- NLTK (Natural Language Toolkit)
- Scikit-learn (sklearn)

## Dataset
The project uses a dataset containing:
- `author`: The author's name.
- `title`: The news title.
- `content`: A combination of the author's name and title.
- `label`: 0 for real news, 1 for fake news.

## Installation
### Prerequisites
Ensure you have Python installed along with the necessary libraries:
```bash
pip install numpy pandas nltk scikit-learn
```
### Download NLTK Stopwords
```python
import nltk
nltk.download('stopwords')
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/your-username/fake-news-detection.git
cd fake-news-detection
```
2. Place the dataset (`train.csv`) in the project directory.
3. Run the script:
```bash
python fake_news_detection.py
```
4. The model will preprocess the data, train using Logistic Regression, and output accuracy scores.

## Model Training & Evaluation
- The dataset is split into training (80%) and testing (20%).
- The `LogisticRegression` model is trained on the transformed text data.
- Accuracy is measured on both training and test datasets.

## Example Prediction
The model takes a sample news article and predicts:
```
The news is Fake
```

## Future Enhancements
- Implement deep learning models (e.g., LSTMs, Transformers).
- Use additional feature extraction techniques.
- Expand dataset for better generalization.

## Contributors
- [Unnati Rawat](https://github.com/unnatirawat19)


