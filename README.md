# ml3-proj

In this project, we want to compare the accuracy of predicting categories for news articles in order to see which is best to be used for classification among the following<br><br>

1.   Headline - simple set of a few keywords
2.   Short description - meaningful sentence or two
<br>
<br>
**The motivation for this is to be able to tell which data is best to be scraped if we want to obtain a news feed with certain categories - e.g. it is faster to just scrape headline text than descriptions - but is it the best method?**



We will first take a Kaggle dataset in JSON from here https://www.kaggle.com/datasets/rmisra/news-category-dataset.<br><br>We need to clean this dataset, explore the data, and try deep learning algorithms on it in order to get the best model and feature.<br> Afterwards, we will try out **two different types of deep learnign models - the LSTM model, which is standard for language processing and the convolutional neural network for text (a surprising but effective in some cases kind of approach)**  to classify based on descriptions and titles, and perform **hyperparameter tuning** on these networks to get the best **accuracy score.**
