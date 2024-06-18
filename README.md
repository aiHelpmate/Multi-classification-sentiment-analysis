# Multi-classification-sentiment-analysis

The project collects online news reports on China's poverty alleviation policies and conducts sentiment analysis. This will give a significant boost to your crawling skills and nlp abilities.

### data crawling
Crawl the data by searching foreign media that have news reports on China's poverty alleviation policies -- the data and code are saved in the "News" folder

### data preprocessing
* drop unwanted colomns
* removal of HTML tags, quotations marks, emoticons, and URLs
* convert all words to lowcase, remove duplicates
* Replace concatenated words with their full forms
* Removal of punctuation, stopwords, numbers and special characters
* Spellchecker for spelling correction

### LSTM model construction
Use pytorch tool and get 93% accuracy
