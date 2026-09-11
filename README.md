# Spam Classifier 📩

A beginner-friendly ML project that classifies SMS/email messages as **spam** or **ham** (not spam).

## How it works
1. Cleans the text (lowercase, removes punctuation/numbers/stopwords)
2. Converts text to numbers using **TF-IDF**
3. Trains a **Multinomial Naive Bayes** model
4. Evaluates using accuracy, precision, recall, and a confusion matrix
5. Lets you test your own message interactively

## Run it
```bash
pip install pandas scikit-learn
python3 spam_classifier.py
```

Or open it directly in **Google Colab** — no installation needed.

## Example
```
Message: "Congratulations! You have won a free cruise. Call now to claim your prize!"
-> Prediction: SPAM (confidence: 68.2%)
```

## Dataset
Uses a small built-in sample dataset by default. To use the real [SMS Spam Collection dataset](https://archive.ics.uci.edu/dataset/228/sms+spam+collection), place the file as `SMSSpamCollection` in the same folder.
