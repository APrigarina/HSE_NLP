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


2.NER
=============

IOB Annotation of Abstracts in Computer Science
-------------
### Description

NER task for computer science related text. <br>
Number of sentences - 1390. <br>
Number of tags - 17. <br>
*   **PL**: Programming language (C++, Java, Python…)
*   **FRAM**: Tool, library or framework (Tensorflow, Microsoft Word, OpenCV…)
*   **STAN**: Computer standard (CSV, TXT, compiler…)
*   **PLAT**: Plateform (GPU, x86, Cloud Computer…)
*   **API**: Classes, event, functions or data structures (graph, init(), print(), object…)
*   **PENT**: Physical entity involved in CS field (Google, Microsoft, CNRS…)
*   **ALGO**: Algorithms (Dijkstra, KNN, Monte Carlo Search…)
*   **FIELD**: Field of application (Machine Learning, Robotic, security…)

Original data can be downloaded [here](https://www.kaggle.com/madjakul/iob-annotation-of-abstracts-in-computer-science) <br>
[Google Colab](https://colab.research.google.com/drive/1DQYlS4X-aXpJpZEbgpx7etSnRlfVBW9f?usp=sharing)

### Results:

|   |  F1-score weighted |
| ------------- | ------------- | 
| CRF  | 0.537  |
| CRF with entity dictionary  | 0.549  |
| bi-LSTM  | 0.420 |
| bi-LSTM with classes weights  | 0.428  |
