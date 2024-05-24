# ai_ml

**How to do semantic search in a pdf?**

Semantic search refers to finding the answer to your query from the set of documents. For example, in a large pdf of product catalogue, a customer wants to know specific thing about the product. One approach is to read the entire pdf, another is to glance through all sections to find the metatopic of the query. However, this would take long time to fetch your answer. Thats where the concept of dense retrieval, retrieval augmented generation and other popular technique arrives.

Lets dive into dense retrieval first.

**Dense Retrieval
The most important thing in text processing, text generation and text understanding is to convert text into numbers. Because a machine learning algorithm works on various calculations, weight adjustments, walking along the gradient descent and finding the minima, therefore numbers or embeddings are essential and core to solving the problem forward. How this word embeddings are calculated is another topic to discuss but word embeddings simply is a numerical representation of text. This numerical representation either captures the meaning of a word invidually or it captures the meaning of words together in sentence. No doubt, the latter one in which word embeddings capture the meaning of words together is more meaningful because words makes sense only when they are read together. Each sentence provides some meaning in entirety. Each word of this sentence is dependent on the other word for meaning. 

Lets explain this with an example from stock market. Consider this sentence: "The stock market is high only in people's mind". It is a pun which suggests that stock market is high but only in thoughts of people or investors. It does not mean that stock market is performing better or sensex score is high. Here high would mean differently than when present alone. A tone of criticism, pun is intended here. For another example, "The stock market is high". Here it actually means stock market is performing well. High actually means high sccore. Therefore, embedding of the same word will be different in the two sentences because embedding will depend on the context of the sentence and the words surrounding them. One popular techniques to calculate these embeddings is through use of Tranformers. We will discuss how transformer works in detail in some other transformed day. But lets get back to Dense retrieval which is the topic in the table right now. 



