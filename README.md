# Fake News Classification

This project focuses on classifying news articles as **Fake** or **Real** using machine learning techniques. It aims to address the growing issue of misinformation by developing a robust system that can help identify fake news.

## Features

- **Text Preprocessing**: Cleans and preprocesses the news articles by removing stop words, stemming, tokenizing, and vectorizing.
- **Machine Learning Models**: Implements various machine learning models to classify news articles:
  - Logistic Regression
  - Random Forest
  - Support Vector Machine (SVM)
  - Naive Bayes
  - Gradient Boosting
  - XGBoost
- **Model Evaluation**: Compares models based on accuracy, precision, recall, and F1-score.
- **Dataset Splitting**: Divides the dataset into training and testing sets to evaluate model performance.

## Tech Stack

- **Programming Language**: Python
- **Libraries**: 
  - scikit-learn
  - pandas
  - NumPy
  - NLTK (Natural Language Toolkit)
  - TfidfVectorizer (from scikit-learn)
  - matplotlib
  - seaborn

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/AryanDaksh/Fake-News-Classification.git
   cd Fake-News-Classification

## Dataset

The dataset used for this project contains news articles labeled as **Fake** or **Real**. The data is split into training and testing sets, allowing the models to be trained and evaluated effectively.

## How It Works

- **Text Preprocessing**: News articles are preprocessed by removing punctuation, stop words, and stemming. The cleaned text is then tokenized and vectorized using TfidfVectorizer.
- **Model Training**: Several machine learning models are trained on the processed dataset.
- **Model Evaluation**: Models are evaluated based on their performance metrics such as accuracy, precision, recall, and F1-score.
- **News Classification**: The trained models classify news articles into **Fake** or **Real** categories.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you'd like to contribute to the project.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE.txt) file for more details.