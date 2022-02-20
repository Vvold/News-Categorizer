# News Categolizer
____
This program uses `Naive Bayes Classifier` and `Linear Support Vector Machine` from `sklearn` to classify news by their short description.

### Data
Data for this project were taken from **kaggle**:  
https://www.kaggle.com/rmisra/news-category-dataset


3000 news items were selected for the 5 most popular categories, which were divided into `train` and `test` samples

### Preprocessing
Before training the model, you need to pre-process the data:
- delete punctuation marks
- delete of numbers
- delete multiple spaces 

Also need to delete stopwords, we will do it with help:
```
from nltk.corpus import stopwords
```
Also need to staming text, we will do it with help:
```
from nltk.stem.snowball import SnowballStemmer
```
Also need to lemmatize text, we will do it with help:
```
from nltk.stem.snowball import SnowballStemmer
```

## Classification

To build a classification model we use two models [Naive Bayes Classifier]() and [Linear Support Vector Machine]() to compare them.

The first method showed an accuracy of 85,3%:

The second method showed an accuracy of 83,5%
## Contacts

----
### Vitkovskiy Volodymyr
- email: VitkovskyiVB@gmail.com
- telegram: @wvld_11
- github: [Vvold](https://github.com/Vvold)
