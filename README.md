# Hoax Detection

Code Implementation from Big Data Challenge on Satria Data 2020

### Technologies

- Machine Learning with NLP
- Neural Network (NN)
- BERT

## Dataset

Download dataset from [This link](https://drive.google.com/drive/folders/1KFBPq1orHLW2XSsRFiTHbYAsJ4Gr2i0V?usp=sharing)

## Results

Label Predictions from the experiment test data are on **result** directory. Validation accuracy are shown below:

### Traditional Machine Learning with NLP Technique

| NLP                  | KNN  | Naive Bayes | SVM  |
| -------------------- | ---- | ----------- | ---- |
| [CountVectorizer](#) | 0.77 | 0.73        | 0.83 |
| [TF-IDF](#)          | 0.73 | 0.73        | 0.83 |

### Neural Network (NN)

Word Embedding and LSTM use text dataset, whereas CNN use image dataset

| Neural Network      | Accuracy | Loss   | Val Accuracy | Val Loss |
| ------------------- | -------- | ------ | ------------ | -------- |
| [Word Embedding](#) | 0.8750   | 0.2697 | 0.8264       | 0.4235   |
| [RNN-LSTM](#)       | 0.8189   | 0.6469 | 0.8194       | 0.6468   |
| [CNN](#)            |          |        |              |          |

### BERT

**Soon**

## Conclusion

Actually, validation accuracy is not enough to determine performance from model.
We need actual label from this competition organizer to get model's performance in predicting document whether hoax or not. At least, we know the steps binary classification on detecting hoax. I'm waiting for your outstanding project.
