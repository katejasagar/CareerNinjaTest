This project is NLP-based text filtering and finding similarities in the text and complete sentences.

The project contains 3 ipynb Files and a description of each is given below:
CrninjaDClean.ipynb: 
  1. In this file we are making a list of URL 
  2. Collecting the transcript in the URL.
  3. Saving data in the pandas DataFrame
  4. Removing Punctuations, escape strings, Numbers in round1 cleaning
  5. Removing the \n and Quotes in the second round cleaning
  6. Removing the stop words and normalizing the words
  7. Converting the whole script in the document term matrix.

crninjaEDA.ipynb:
  1. Finding the most repetitive words.
  2. Adding the repetitive words in the stop words
  3. Removing the repetitive words.
  4. Converting document term matrix after removing repetitive words
  5. plotting the word cloud.
  6. Analysing the most unique word used
  
crninjaTopicmodeling.ipynb: This is the main file where we will find the relevance of the topic searched with each website.
  1. Creating the LDA model. We are using the gensim library
  2. Converting the data into the required gensim format
  3. Generating the list of the topic with all words in the Document term metrix
  4. Generating the list of the topic with only Nouns
  5. Generating the list of the topic with only Nouns and Adjectives
  6. We found out that it works best with Nouns and Adjective filter with 3 clusters.
  7. Finding which website belongs to which cluster
  8. Finding which cluster matches best with Our searched word.
