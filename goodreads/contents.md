# Characteristic words

## Research question

"What words are most characteristic for the the Guardian top 100 novels?".

Additionally: "Can you use summaries of books to find characteristic words?"

## Data

The list of top 100 novels (in English) according to the Guardian:[the Guardian](https://www.theguardian.com/books/2015/aug/17/the-100-best-novels-written-in-english-the-full-list)
A good source for of books descriptions: [Goodreads](https://www.goodreads.com/)

## Description

In order to quickly find books that might interest you, it can be useful to have a list keywords describing each book. Often such keywords are created by hand, but they can also be automatically generated from the text.  

A first step is to find out for each word, how representative it is for the text. There is many ways to do this, but a popular one is TF-IDF (Term Frequency - Inversed Document Frequency).

Calculating the TF-IDF score for each word for each text, can become time very consuming for large corpora, so it can be helpful to reduce the problem.

Instead of taking the whole text, you might only want to use a summary. We can assume that a good summary contains relevant keywords to the book. Further you might want to remove stop words (frequent words like "the" or "so") from the text as they don't carry a lot of information. It can also be useful to only focus on specific grammatical categories such as nouns ("house", "big-brother").

The Guardian has compiled a list of the top 100 novels in English you can use as a reference. However they link to books reviews rather than summaries. Reviews might contain a lot of distracting text that is not really about the content of the book. So, it's might be better to cross reference the titels from the Guardian with a corpus of descriptions, such as provided by Goodreads.

The research question stated above is quite simple, you might be able to think of additional question.

## Resources

* Learn how to use the Python spaCy library: [spaCy](https://course.spacy.io/en). Pay special attention to chapter 1 and 2. Try to find out the following: How to tokenize text using spaCy? How to get rid of stop words? How to get only nouns?
* Read about the TF-IDF measure: https://monkeylearn.com/blog/what-is-tf-idf/
* A video about the same subject: https://www.youtube.com/watch?v=OymqCnh-APA

## Outline

Create your own analysis in order to answer the research question. This can be done in many ways. The project should be complex enough to be interesting. Have a look at these guidelines:

* Use spaCy to tokenize the text and remove stopwords.
* Make sure to use only the [lemma](https://en-academic.com/dic.nsf/enwiki/1247338) of each word, not the word itself. (When you tokenize a text with spaCy you can easily get the lemma of each token.)
* For computing a TF-IDF score, you need to know the frequency of each word in each text. Think well about which data structures can be convenient to use for that.
* The output should be some sort of data file containing at least the 15 key words with the highest TF-IDF score for each book. Preferably it should also be visualized with a plot.
* Think of at least another interesting research question you can answer with the data.
* The code that is used to create the keywords should be well designed, clear, and neatly formatted. Use functions, choose useful names for your variables, prevent code repetition, place comments, etc.
* (Bonus) Additionally you can have a look of how valid it is to use only summaries of books. For some books you can find the whole text online. You might be able to validate your algorithm by running it on the full text and the summary and compare the results. You'd need to think of a metric. Have a look here for full texts: [Project Gutenberg](https://www.gutenberg.org/ebooks/search/?query=1984&submit_search=Go%21)
* Make sure you provide a clear answer your research questions.

_If you use any other sources than the ones we pointed out, be sure to include the source in your GitHub repository!_
