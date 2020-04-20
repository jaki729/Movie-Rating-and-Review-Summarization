IEEE TRANSACTIONS ON SYSTEMS, MAN, AND CYBERNETICS—PART C: APPLICATIONS AND REVIEWS, VOL. 42, NO. 3, MAY 2012
# Movie-Rating-and-Review-Summarization

FEATURE EXTRACTION 
NATURAL LANGUAGE PROCESSING 
TEXT ANALYSIS
TEXT MINING

STUDY OUTPUT 
About the IMDB sentiment analysis problem for natural language processing and how to load it in Keras.
How to use word embedding in Keras for natural language problems?
How to develop and evaluate a multi-layer perception model for the IMDB problem?

The dataset is the Large Movie Review Dataset often referred to as the IMDB dataset.
LINK FOR DATASET
http://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz
REFERENCES
1==>https://keras.io/datasets/
2==>https://en.wikipedia.org/wiki/Word_embedding
3==>https://keras.io/layers/embeddings/
OUTPUT
Training data: 
(50000,)
(50000,)
Number of words: 
88585
Review length: 
Mean 234.76 words (172.911495)
Model: "sequential_1"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
embedding_1 (Embedding)      (None, 500, 32)           160000    
_________________________________________________________________
flatten_1 (Flatten)          (None, 16000)             0         
_________________________________________________________________
dense_1 (Dense)              (None, 250)               4000250   
_________________________________________________________________
dense_2 (Dense)              (None, 1)                 251       
=================================================================
Total params: 4,160,501
Trainable params: 4,160,501
Non-trainable params: 0
Train on 25000 samples, validate on 25000 samples
Epoch 1/2
 - 60s - loss: 0.4888 - accuracy: 0.7360 - val_loss: 0.2961 - val_accuracy: 0.8741
Epoch 2/2
 - 68s - loss: 0.1767 - accuracy: 0.9349 - val_loss: 0.3170 - val_accuracy: 0.8699
Accuracy: 86.99%
FOR GRAPH RUN IT ON JUPYTER NOTEBOOK




THE END.
