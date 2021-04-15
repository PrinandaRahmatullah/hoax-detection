# Hoax Detection

Code Implementation from Big Data Challenge on Satria Data 2020

### Technologies

- Machine Learning with NLP
- Neural Network (NN)
- BERT

## Dataset

You can download dataset from [This link](https://drive.google.com/drive/folders/1KFBPq1orHLW2XSsRFiTHbYAsJ4Gr2i0V?usp=sharing) :wink:

## Results

Results from hoax detection experiment using each algorithms is on **result** directory.
Validation accuracy shown below :wink:

### Traditional Machine Learning with NLP Technique

| NLP                                                                                                                      | KNN  | Naive Bayes | SVM  |
| ------------------------------------------------------------------------------------------------------------------------ | ---- | ----------- | ---- |
| [CountVectorizer](https://github.com/PrinandaRahmatullah/hoax-detection/blob/main/traditional_ml/count_vectorizer.ipynb) | 0.77 | 0.73        | 0.83 |
| [TF-IDF](https://github.com/PrinandaRahmatullah/hoax-detection/blob/main/traditional_ml/tf_idf.ipynb)                    | 0.73 | 0.73        | 0.83 |

### Neural Network (NN)

| Neural Network     | Accuracy | Loss |
| ------------------ | -------- | ---- |
| [Word Embedding]() |          |      |
| [RNN-LSTM]()       |          |      |
| [CNN]()            |          |      |

### BERT

**Soon**

## Conclusion

Actually, validation accuracy is not enough to determine performance from model.
We need actual label from this competition organizer to get model's performance in predicting document whether hoax or not. At least, we know the steps binary classification on detecting hoax. I'm waiting for your outstanding project.
