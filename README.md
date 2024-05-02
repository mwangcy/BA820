# Analyzing CNN Article Sentiment with Natural Language Processing

Group Project BA820

**Contributors** : Mauro Wang, Lyushen Song, Pengru Lin, Leonardo Trucious, Ashley Mercado

**Problem Statement and Motivation:**
In today's digital age, online media platforms like CNN play a pivotal role in shaping public opinion and disseminating news. However, interpreting the underlying tone and sentiment of news articles can be challenging due to potential biases or editorial nuances. Our project aims to leverage Natural Language Processing (NLP) techniques to analyze the sentiment of CNN articles, providing insights into the platform's messaging strategies and audience engagement tactics.

**Dataset:**
We utilize a comprehensive dataset sourced primarily from Kaggle, comprising CNN articles published between 2011 and 2022. This dataset, extracted via a custom web crawling process targeting the CNN Site Map, consists of 38,000 rows and 9 columns, including metadata such as author, dates, and article content.

**Proposed Methodology:**
Our methodology involves several steps to preprocess and analyze the data. We begin by performing exploratory data analysis to ensure data integrity, followed by cleaning and standardizing text data for consistency. Tokenization, removal of stop words, stemming, and lemmatization are employed to prepare the text for sentiment analysis. Rather than traditional Bag of Words approaches, we leverage the NLTK sentiment analyzer to derive sentiment scores for each article. Additionally, market basket analysis and temporal analysis are conducted to identify patterns and trends in CNN's article sentiment over time.

**Business Relevance:**
Understanding the sentiment and tone of CNN articles has significant implications for media companies and content creators. Insights gained from our analysis can inform content optimization strategies, audience engagement tactics, and editorial decision-making processes. Media companies can tailor content based on audience interests, optimize messaging for specific topics, and manage their public image effectively. Furthermore, our analysis provides valuable insights into shifting trends and interests, benefiting not only CNN but also other media organizations seeking to stay abreast of industry dynamics.



