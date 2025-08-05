After text preprocessing, next, we'd need to feed our NLP or ML algorithm
our text in the form that it understands.

Text vectorization is the process of converting words or sentences into 
numbers (vectors) so that machines can understand and process them.

Since computers can't understand raw words like “hello” or “pizza,” we turn those words 
into numbers — but in a way that preserves their meaning or structure.

There are two common techniques:
- Bag of words
- TF - IDF(Term Frequency - Inverse Document Frequency)

### Bag of words
Counts which words appear in which documents. It is simple, but you lose context

Bag of Words is a technique for extracting features from text data for machine 
learning tasks, such as text classification and sentiment analysis. This is 
important because machine learning algorithms can’t process textual data. 
The process of converting the text to numbers is known as feature extraction 
or feature encoding.

A Bag of Words is based on the occurrence of words in a document. The process 
starts with finding the vocabulary in the text and measuring their occurrence. 
It is called a bag because the order and structure of words are not considered, 
just their occurrence. 

In Bag-of-Words (BoW), text is represented by treating each word as a feature in a vector. 
The model completely ignores word order, syntax, and semantics. Each word in the corpus 
corresponds to a dimension in the vector, and the value represents how many times the 
word appears in the document.

On the other hand, TF-IDF enhances the BoW model by adding layer of consideration: the 
rarity of the word across the entire dataset. It still considers word frequency (TF) but 
introduces the inverse document frequency (IDF) to adjust the weight of each word. Words 
that appear frequently in a document but are rare across the entire corpus are given more 
importance.







