# Hoax Detection

Code Implementation from Big Data Challenge on Satria Data 2020

### Technologies

- Machine Learning with NLP
- Recurrent Neural Network
- BERT

## Dataset

You can download dataset from [This link](https://drive.google.com/drive/folders/1KFBPq1orHLW2XSsRFiTHbYAsJ4Gr2i0V?usp=sharing) :wink:

## Results

Results from hoax detection experiment using each algorithms is on **result** directory.
Validation accuracy shown below :wink:

### Traditional Machine Learning with NLP Technique

| NLP             | KNN  | Naive Bayes | SVM  |
| --------------- | ---- | ----------- | ---- |
| CountVectorizer | 0.78 | 0.72        | 0.83 |
| TF-IDF          | 0.75 | 0.72        | 0.83 |

Actually, validation accuracy is not enough to determine performance from model.
We need actual label from this competition organizer to get model's performance in predicting document whether hoax or not.
