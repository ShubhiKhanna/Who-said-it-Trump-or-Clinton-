# Who said it? Hillary or Trump?

![Hillary vs Trump](https://github.com/ShubhiKhanna/Who-said-it-Trump-or-Clinton-/blob/main/trumpclinton.jpg)

Twitter played an increasingly prominent role in the 2016 US Presidential Election. Debates had raged and candidates had risen and fallen based on tweets. 

[This](https://www.kaggle.com/benhamner/clinton-trump-tweets/home) dataset provides ~6000 recent tweets from Hillary Clinton and Donald Trump, the two major-party presidential nominees.

Our goal is to develop a model which determines the author of a given tweet.

To do so, we're using the Multinomial Naive Bayes Classifier. You can read more about it [here](https://www.mygreatlearning.com/blog/multinomial-naive-bayes-explained/).

|              | Precision | Recall | f1-score | Support |
|--------------|-----------|--------|----------|---------|
| Hillary      | 0.92      | 0.93   | 0.92     | 521     |
| Trump        | 0.94      | 0.93   | 0.94     | 624     |
| accuracy     |           |        | 0.93     | 1145    |
| Macro Avg    | 0.93      | 0.93   | 0.93     | 1145    |
| Weighted Avg | 0.93      | 0.93   | 0.93     | 1145    |
