# ROC-curves-personality

This repository contains the ROC curves the binary classification systems implemented in the paper named "Evaluation of different word embeddings to create personality models in Spanish."

To see the ROC curves, just open the file "ROC_curves.pdf".

From this figure, we can observe a general behavior: the best performance with respect to the area under the curve (AUC) is generally obtained with BERT's word embeddings, since, in 4 of the five traits, it has the highest AUC value. Following BERT, the BETO model provides some of the best performances, and after it, the fusion of Word2Vec and GloVe, both of dimension 100 and dimension 300 (see ROC curves for the openness to experience and conscientiousness traits).
