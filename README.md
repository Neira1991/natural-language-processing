# natural-language-processing
My works for "Natural Language Processing" Coursera course.
I am not really good at Python neither at ML, would be really happy to discuss my results with others :)

## Week1
Predict tag of Stackoverflow with linear model. (multi-tag)
Used GridSearch CV for optimisation on tfidf model.

F1-score weighted :0.654025  

## Week2
Named entity recognition with LSTMs.
No tweaks and optimisation.  

Train set quality:  
precision:  76.68%; recall:  77.86%; F1:  77.26

Validation set quality:  
precision:  47.95%; recall:  32.59%; F1:  38.80

Test set quality:  
precision:  51.64%; recall:  36.42%; F1:  42.72

## Week3
Find duplicate questions by their embedding in word2vec.
Google embeddings :
DCG@   1: 0.320 | Hits@   1: 0.320  
DCG@   5: 0.387 | Hits@   5: 0.448  
DCG@  10: 0.404 | Hits@  10: 0.500  
DCG@ 100: 0.438 | Hits@ 100: 0.669  
DCG@ 500: 0.460 | Hits@ 500: 0.844  
DCG@1000: 0.477 | Hits@1000: 1.000  

Starspace embeddings made with training set :
DCG@   1: 0.516 | Hits@   1: 0.516  
DCG@   5: 0.614 | Hits@   5: 0.699  
DCG@  10: 0.633 | Hits@  10: 0.757  
DCG@ 100: 0.664 | Hits@ 100: 0.906  
DCG@ 500: 0.674 | Hits@ 500: 0.981  
DCG@1000: 0.676 | Hits@1000: 1.000  

## Week4
Seq2Seq model, encoder-decoder to learn to addition and substraction.
Model could be used for other tasks.

Dataset size =200000 (2 * originally given size)
No tweaks.

Epoch: 10, MAE: 8.472910, Invalid numbers: 10155/200,000

## Week5
TODO
