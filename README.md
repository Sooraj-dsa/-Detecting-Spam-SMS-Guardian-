# SMS Guardian 📬✉️🤖

## Overview
Detecting Spam and Ham in SMS messages using state-of-the-art Natural Language Processing (NLP) techniques. This project employs machine learning models to sift through messages and identify potential spam, ensuring your SMS inbox remains secure.

## Problem Statement
With the rise of spam messages, it becomes crucial to have a reliable system that can differentiate between genuine messages (ham) and unwanted spam. This project addresses this challenge by building a robust SMS classifier.

## Project Workflow

### 1. Data Exploration and Feature Engineering
- **Dataset:** Explored a dataset containing 5,574 messages in English, classifying them as ham or spam.
- **Feature Engineering:** Created new features, identified outliers, and preprocessed data for effective modeling.

### 2. Text Data Cleaning
- **Punctuation and Numbers Removal:** Extracted alphabetic characters for cleaner text.
- **Lowercasing:** Ensured uniformity by converting all characters to lowercase.

### 3. Text Processing and Vectorization
- **Tokenization:** Broke down text into words for better analysis.
- **Stopword Removal:** Eliminated common and less informative words.
- **Lemmatization:** Simplified words to their base form.
- **TF-IDF Vectorization:** Converted processed text into numerical vectors.

### 4. Model Building
- **Model Pipeline:** Developed a comprehensive pipeline with Naïve Bayes, RandomForest, KNeighbors, and Support Vector Machines.
- **Cross-Validation:** Ensured model reliability through cross-validation on the training set, assessing accuracy and overall performance.

### 5. Project Title and Theme
The project name "SMS Guardian" with emojis to visually communicate its purpose and theme. 📬✉️🤖

## Usage
1. Clone the repository: `git clone https://github.com/Sooraj-dsa/SMS-Guardian.git`
2. Navigate to the project directory: `cd SMS-Guardian`
3. Install dependencies: `pip install -r requirements.txt`
4. Run the Jupyter Notebook or Python script for the complete project.

## Full Analysis
Check out the full analysis notebook on [Kaggle](https://www.kaggle.com/code/soorajgupta7/detecting-spam-sms-guardian)!


## Contributions
Contributions are welcome! Feel free to submit issues, feature requests, or pull requests.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- Special thanks to [NLTK Library](https://www.nltk.org/) for providing essential NLP tools.
- Emoji art by [Emojipedia](https://emojipedia.org/).

