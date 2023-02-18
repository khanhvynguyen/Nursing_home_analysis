The objective of [this project](https://github.com/khanhvynguyen/Keyword_network_and_word_frequency_analysis) is to perform keyword network analysis and word frequency analysis

The first dataset is acquired from [this link](https://docs.google.com/spreadsheets/d/1GTwv07i98vL7S-J9eeP8NV1fJVnymm1eJ31RDyt4Mxw/edit#gid=822007629).

After that, I extracted keyword data anf converted it to a weighted adjacency matrix and a weighted network.

The second dataset is the twitter data of Elon Musk from 2017-2022 (https://www.kaggle.com/datasets/ayhmrba/elon-musk-tweets-2010-2021). Each year has thousands of tweets. Assume each year to be a document (all the tweets in one year will be considered as a document). 

Word frequency analysis was done by following these steps: 
- Compute word frequencies for each year. Exclude the stop words
- Show top 10 words (for each year) by the highest value of word frequency
- Plot histogram of word frequencies for each year
- Use Zipf’s law and plot log-log plots of word frequencies and rank for each year
- Create bigram network graphs for each year

Jupyter Notebook [Link](https://github.com/khanhvynguyen/Keyword_network_and_word_frequency_analysis/blob/main/keyword_netword_and_word_frequency.ipynb)
