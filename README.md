# Toxic-Comment

This notebook presents a baseline model for Kaggle's recently completed Toxic Comment Classification Challenge. 
The challenge was to build a multi-headed model that’s capable of detecting different types of of toxicity like threats, obscenity, insults, and identity-based hate in comments dataset from Wikipedia’s talk page edits.

I have used pretrained GloVe word vctors. I have tried to implement the idea of attention mechanism present in the paper https://www.cs.cmu.edu/~diyiy/docs/naacl16.pdf. The basic idea is, not all words contribute equally to the representation of the sentence meaning. Hence, the authors of this papers introduced attention mechanism to extract such words that are important to the meaning of the sentence and aggregate the representation of those informative words to form a sentence vector. The LB score for this model was 0.9840. I trained model only for 3 epochs. No text cleaning or special preprocessing was done.
