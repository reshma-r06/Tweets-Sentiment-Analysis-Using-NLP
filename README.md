# Tweets-Sentiment-Analysis-Using-NLP

Twitter is one of the largest social media platform, where it is estimated that 6000 tweets per second are tweeted by people in the whole world related to different topics. The aim of this case study is to identify the emotions of the tweet, whether they are positive or negative. A dataset containing a large collection of tweets is taken and it uses natural language processing and machine learning algorithms to classify tweets automatically as positive, negative.

I learned many new concepts while doing this project and in this readme section, I will highlight the major concepts used here for a quick overview.

 # Sentiment Analysis :
  Sentiment analysis is the process of determining whether a writting or a statement is positive or negative or neutral. Sentiment analysis is commonly used by businesses to better understand customer feedback.
 # Text Mining
  To derive meaningful information from unstructured data. Text mining is the process of exploring and analyzing large amounts of unstructured text data aided by software that can identify concepts, patterns, topics, keywords and other attributes in the data.
  # NLP - Natural Language Processing
  Natural language processing (NLP) is a subset of artificial intelligence, computer science, and linguistics focused on making human communication, such as speech and text, comprehensible to computers.
  NLP Techniques include,
* Sentiment analysis: An NLP technique that analyzes text to identify its sentiments, such as “positive,” “negative,” or “neutral.” Sentiment analysis is commonly used by businesses to better understand customer feedback. 
* Summarization: An NLP technique that summarizes a longer text, in order to make it more manageable for time-sensitive readers. Some common texts that are summarized include reports and articles. 
* Keyword extraction: An NLP technique that analyzes a text to identify the most important keywords or phrases. Keyword extraction is commonly used for search engine optimization (SEO), social media monitoring, and business intelligence purposes. 
* Tokenization: The process of breaking characters, words, or subwords down into “tokens” that can be analyzed by a program. Tokenization undergirds common NLP tasks like word modeling, vocabulary building, and frequent word occurrence.

# Text Normalisation
Reducing the randomness in a particular piece of text.This helps us to reduce the amount of different information that the computer has to deal with, and therefore improves efficiency.

# Text cleaning
The process of removing or transforming certain parts of the text so that the text becomes more easily understandable for NLP models that are learning the text. Most common methods are lowercasing the data, removing punctuations,numbers,extra space, emoticons etc.

# WordCloud
A cloud filled with lots of words in different sizes, which represent the frequency or the importance of each word. This is called a Tag Cloud or word cloud. They're similar to bar blots but are often more visually appealing. Word clouds can be particularly helpful when you want to:
* Quickly identify the most important themes or topics in a large body of text
* Understand the overall sentiment or tone of a piece of writing
* Explore patterns or trends in data that contain textual information
* Communicate the key ideas or concepts in a visually engaging way

# RegEx 
A RegEx, or Regular Expression, is a sequence of characters that forms a search pattern.
RegEx can be used to check if a string contains the specified search pattern.Python has a built-in package called re, which can be used to work with Regular Expressions.findall	Returns a list containing all matches, search	Returns a Match object if there is a match anywhere in the string, split	Returns a list where the string has been split at each match, sub	Replaces one or many matches with a string.

# Word Contractions
A contraction is a word made by shortening and combining two words e.g., can + not = can't.
# Stemming
Stemming is the process of reducing the words to their word stem or root form. The objective of stemming is to reduce related words to the same stem even if the stem is not a dictionary word. For example, connection, connected, connecting word reduce to a common word “connect”.
# Lemmatization
Lemmatization reduces words to their base word, reducing the inflected words properly and ensuring that the root word belongs to the language. It’s usually more sophisticated than stemming, since stemmers works on an individual word without knowledge of the context. In lemmatization, a root word is called lemma. A lemma is the canonical form, dictionary form, or citation form of a set of words.Lemmatization is similar to stemming, but it brings context to the words. For example, "building has floors" reduces to "build have floor" upon lemmatization

# Text Vectorization
The process of converting text into numerical representation.The popular methods are Binary term Frequency, Bag of words term frequency, L1 Normalized term frequency, L2 normalized TF-IDF, Word2Vec

# Sources:
Applied Text Mining and Sentiment Analysis with Python Course by Teacher Benjamin Termonia - This is my first step where I was introduced to NLP and made me to do this case study project.
And here are the major websites where the detailed and easy to understand concepts are explained and I referred them when I was having many confusions while doing this project.
https://towardsdatascience.com/text-normalization-for-natural-language-processing-nlp-70a314bfa646
https://www.datacamp.com/tutorial/wordcloud-python
https://www.w3schools.com/python/ There are also many other good websites on the internet which provide good explanation on these concepts and I have mentioned only the websites I referred more number of times while serching for different concepts to do this case study project.


