This project was the final research project for USC CS 544 - Natural Language Processing. The project explored if document embeddings from the IMDB sentiment dataset, created using Doc2Vec, would have natural clusters in a high-dimension feature space around sentiment poles. 

The results were negative, indicating that document vectors were not capturing sentiment similarity. 

Future work can explore if other dimensions are more salient in the embedding and clustering process, such as movie categories or movie topic. Furthermore, it is possible that the nature of the Doc2Vec algorithm, which involves averaging word vectors, may fail to capture the semantic relation between words, "smoothing out" the natural clustering of individal word vectors when applied at the document scale. 
