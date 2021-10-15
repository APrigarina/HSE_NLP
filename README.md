# HSE_NLP

1.Text classification
=============

Medium Post Titles
-------------

### Description

Predict the category of posts by title and subtitle. <br>
Number of categories considered - 23. <br>
Original data can be downloaded [here](https://www.kaggle.com/nulldata/medium-post-titles) <br>
[Google Colab](https://colab.research.google.com/drive/1l2TmsU9Gm147XMHhg4UOGgNptNw5iH5J?usp=sharing)

    
### Classification results:

|   | ROC-AUC One-vs-rest | F1-score weighted |
| ------------- | ------------- | ------------- |
| Logistic Regression  | 0.962  | 0.642  |
| KNN  | 0.958  | 0.604  |
| CNN  | 0.934  | 0.621  |
| LSTM  | 0.945  | 0.610  |
