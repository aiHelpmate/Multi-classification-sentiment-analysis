# Multi-classification-sentiment-analysis

The project collects online news reports on China's poverty alleviation policies and conducts sentiment analysis. This will give a significant boost to your crawling skills and nlp abilities.

If you want to try a PyTorch-based deep learning project, this is the best choice！

## Data crawling
Crawl the data by searching foreign media that have news reports on China's poverty alleviation policies -- the data and code are saved in the "News" folder

## Data preprocessing
* Drop unwanted colomns.
* Removal of HTML tags, quotations marks, emoticons, and URLs.
* Convert all words to lowcase, remove duplicates.
* Replace concatenated words with their full forms.
* Removal of punctuation, stopwords, numbers and special characters.
* Spellchecker for spelling correction.

## LSTM model construction

<img src = "https://github.com/aiHelpmate/Multi-classification-sentiment-analysis/blob/main/Images/3a027f1c11186cf975c45fc4e920e64.png" width="500">

You can adjust the parameters based on this to achieve better results.

## Results:  
#### Pytorch_LSTM:  

| Test loss | Test accuracy | 
|--------------|-----------|
|          0.175 |      0.937 |
