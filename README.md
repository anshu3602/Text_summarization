# Text_summarization
An extractive text summarizer which uses word frequencies of the sentence and yields a score for each sentence. Three methods implemented. 
1)It uses the Natural Language Toolkit to process the text information and regular expressions to preprocess the data
2)Term frequency - Inverse Term freqeuncy used to quantify the words of the document , which signifies the importance of the word . 
TF-IDF uses vectorization as a tool to translate words to langauge that the computer will understand . 
3)Gensim-TextRank - Gensim is used to summarize the text . An davantage of gensim is that we will not have to go through preprocessing of the data 
as we did with word frequency and TF-IDF. Gensim removes stop words , stems text on its own .

