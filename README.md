# Fake-news-detection-model.
This project aims to detect fake news using a Deep learning approach model. The model processes news articles and predicts whether the given news is real or fake.

## Features
- Preprocessing of data includes stopword removal, tokenization, sequence padding and prediction.
- Utilization of tensorflow, nltk and sklearn to implement in the model.
- Loss curve, Accuracy curve, confusion matrix and ROC curve (Receiver-operating characteristic curve) is used to prediction.

## Getting Started

### Prerequisites
- Python 3.8 or above.
- Required libraries: `numpy`,`pandas`,`nltk`,`re`,`tensorflow`,`nlpaug.augmenter.word`,`matplotlib`,`seaborn`.

### Installation
- Install Dependencies:
  ```bash
  pip install -r requirements.txt
  ```
  
### Usage
1. Prepare the dataset by placing it in the root folder of the project and renaming it to `fake_and_real_news.csv`.
2. Run the main script to train the mode:
   ```bash
   python fake_news_detection_using_dl.py
   ```
3. Predict using the model by modifying the input text in the script.

## Model Summary
Here we developed a DL-based fake news detection system using a Bidirectional LSTM model to classify news articles as either real or fake. To enhance the accessibility, we deployed the system using flask and hosted it on AWS E2 instance, for real time prediction through web interface.

## Result
The high accuracy of 99% demonstrates the model's effictiveness in identifying misinformation.

## Author

Sudip Mahapatra - in collaboration with Souvik Haldar, Suchandra Das, Ankush Panja, Surojit Biswas.
