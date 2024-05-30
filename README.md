Project Title: Text Mining of Amazon Customer Reviews

Business Problem:
With the increasing volume of online customer reviews, businesses need to extract valuable insights to improve their products and services. Our team focused on analyzing Amazon customer reviews in the mobile electronics category, specifically speakers, to uncover trends and sentiments.

Task:
Our objective was to utilize text mining techniques to analyze customer reviews, identify key themes, and perform sentiment analysis. We aimed to provide actionable insights that could help businesses enhance product quality and customer satisfaction.

Action:
1.Data Preparation:
Dataset: Collected over 2 million reviews from the Amazon Mobile Electronics Reviews dataset.
Cleaning: Used Python, BeautifulSoup, Spacy, and Gensim to remove null values, irrelevant columns, special characters, and stopwords. Standardized and normalized text data.
2.Text Parsing and Filtering:
Tokenized text data into individual words using word_tokenizer.
Converted text to lowercase, removed punctuation, and unnecessary whitespace.
Employed the StemmerPorter algorithm for stemming.
3.Data Exploration:
Created word clouds for unigrams and bigrams to visualize frequently used words.
Analyzed count plots of top words and keywords in positive feedback, focusing on attributes like sound quality and Bluetooth.
4.Topic Modeling:
Utilized LDA (Latent Dirichlet Allocation) with Gensim to identify five main topics for each brand (ALTEC, Beats, Bose, JBL, Onyx).
Evaluated topics using coherence metrics and visualized with pyLDAvis.
5.Sentiment Analysis:
Used TextBlob to calculate polarity and subjectivity scores for each review.
Analyzed the distribution of negative, neutral, and positive sentiments for each brand.
Plotted polarity versus subjectivity to understand sentiment patterns.
6.Model Development and Comparison:
Developed regression and decision tree models using scikit-learn with various SVD values (10, 50, 70, 100).
Tested term weight combinations (entropy, mutual information) and performed cross-validation.
Selected the best model based on ROC values and misclassification rates, with the regression model (mutual information, SVD=100) achieving a ROC value of 93.8%.

Impact:
Enhanced Product Quality: Provided insights into key themes like sound quality, design, and durability, helping businesses focus on areas that drive customer satisfaction.
Informed Marketing Strategies: Identified brand-specific strengths, enabling targeted marketing campaigns that emphasize highly-rated features.
Customer Satisfaction: Highlighted issues in negative reviews, guiding improvements in product quality and customer service, leading to better customer retention.

Skills Used:
Data Cleaning and Preparation: Python, BeautifulSoup, Spacy, Gensim
Text Mining and Analysis: Word clouds, count plots, topic modeling (LDA), sentiment analysis (TextBlob)
Machine Learning Models: Regression and decision tree models (scikit-learn)
Visualization: pyLDAvis, matplotlib
Statistical Analysis: ROC values, cross-validation
By leveraging advanced text mining and sentiment analysis techniques, our project extracted actionable insights from customer reviews, significantly contributing to understanding customer preferences and improving product quality and marketing strategies.
