# Fake News Detection Data Science Project Using Python.

### Terms Used. 

**TfidfVectorizer.**
**TF** , short form for, **Term Frequency:** The number of times a word appears in a document is its Term Frequency. A higher value means a term appears more often than others, and so, the document is a good match when the term is part of the search terms.

**IDF** ,short form for, **Inverse Document Frequency:** Words that occur many times a document, but also occur many times in many others, may be irrelevant. IDF is a measure of how significant a term is in the entire corpus.

The **TfidfVectorizer** converts a collection of raw documents into a matrix of TF-IDF features.

**PassiveAggressiveClassifier.** 

Passive Aggressive algorithms are online learning algorithms. Such an algorithm remains passive for a correct classification outcome, and turns aggressive in the event of a miscalculation, updating and adjusting. Unlike most other algorithms, it does not converge. Its purpose is to make updates that correct the loss, causing very little change in the norm of the weight vector.



#### Dataset used: 

The dataset  used for this python project is **news.csv**. This dataset has a shape of **7796×4**. The first column identifies the news, the second and third are the title and text, and the fourth column has labels denoting whether the news is REAL or FAKE. The dataset takes up 30MB of space.

#### Python libraries used

Pandas, numpy and sklearn


#### The source code 
Get the all source code in Main.ipynb file
