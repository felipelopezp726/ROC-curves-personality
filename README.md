# ROC-curves-personality

This repository contains the ROC curves the binary classification systems implemented in the paper named "Evaluation of different word embeddings to create personality models in Spanish."

To see the ROC curves, just open the file 

The Figure shows the ROC curves for the binary classification systems where the performance for each of the 5 traits is visually compared, taking into account the features considered in this work. From this figure, we can observe a general behavior: the best performance with respect to the area under the curve (AUC) is generally obtained with the word embeddings obtained by BERT, since in 4 of the 5 traits it has the highest AUC value. Following BERT, the BETO model provides some of the best performances, and after it, the fusion of Word2Vec and GloVe, both of dimension 100 and dimension 300 (see ROC curves for the openness to experience and conscientiousness traits). 
