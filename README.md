# EmoCK
Facial expression recognition datasets with emotion categories

# 🧠 EmoCK / CK+ Facial Expression Recognition

## 📌 Overview
This competition focuses on facial expression recognition using the CK+ dataset, where participants classify emotions from facial images.

## 🎯 Task Description
Classify each image into one of 7 emotion classes:
anger, contempt, disgust, fear, happy, sadness, surprise.

## 🏆 Objective
Build a model that achieves the highest accuracy on unseen facial images.

## 🔗 Dataset Link
https://www.kaggle.com/datasets/shawon10/ckplus

## 📂 Dataset Description
CK+ is a standard benchmark dataset for emotion recognition with labeled facial expressions.

## 📁 Dataset Structure
train/ (labeled images), test/ (unlabeled images + predictions.csv)

### Public vs Private
- Public: train
- Private: test labels

## 📊 Leaderboard
Ranked by test performance.

## 📝 How to Submit Your Results
(Use your provided steps exactly here)

## 📏 Evaluation Metric
Accuracy, F1-score

## ✅ Allowed
CNNs, transfer learning

## ❌ Not Allowed
External emotion datasets, manual labeling

## 🧪 Baseline Model
2-layer CNN (Conv → MaxPool → Conv → MaxPool → Dense)

## 📚 References
Lucey et al., 2010

## 👩‍🏫 Organizer
Tasneem Selim
