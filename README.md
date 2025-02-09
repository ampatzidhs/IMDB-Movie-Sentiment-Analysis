# IMDB-Movie-Sentiment-Analysis

Sentiment analysis for IMDB movie dataset, which contains 50.000 data, with positive/negative sentiments. 
The repository consists of: 
- data preprocessing
- different models used for classification </br>
The models we used were:
- Random Forest
- XGBoost
- Naive Bayes
- Bidirectional RNN
- MLP
- GRU
- DistilBERT (pretrained)
- DistilBERT (finetuned)

The best model was Naive Bayes with 89% accuracy and f1 score.

The best model was also used to classify data from a product reviews dataset. The dataset consisted of 258 samples for binary sentiment analysis and our model had 89% accuracy and 90% f1 score.
