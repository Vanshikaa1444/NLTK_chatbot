# NLTK_chatbot
An intelligent chatbot using AI and ML to respond without any rules/intents fed into it.
<br>
Steps involved:
<br>
1. Reading a text corpus(block of info that you feed to your bots)
<br>
2.Preprocessing(Stop words removal, lower case conversions)
<br>
As chatbot is an apllication of text analytics we have to do that.
<br>
3.Tokenization(to convert a sentence into individual words or tokens), Stemming(finding similarities b/w words with same root words) and Lemmatization(returning the base word(we convert different variants of the word into the same word and return that word))
<br>
4.Bag of Words(collection of words post standardization, cleaning, stemming)- using these we convert words into numbers by generating their vector form and we use cosine similarity to find the most similar one to the user query
<br>
5. One hot encoding
