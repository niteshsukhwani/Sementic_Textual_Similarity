# Sementic_Textual_Similarity
### Task: Finding Semantic Textual Similarity Proposed Approach:
1. Encode both the sentence using Universal Sentence Encoder.
2. Find the Cosine Similarity between both the encoded vectors.

### Why ?

The Universal Sentence Encoder encodes text into high dimensional vectors. The pre-trained Universal Sentence Encoder is publicly available in Tensorflow-hub . It comes with two variations i.e. one trained with Transformer encoder and other trained with Deep Averaging Network (DAN). It gives an encoding vector of 512 dimensions. The main reason behind using this was that this model has crossed all the baseline scores in the domain of natural language processing tasks such as text classification, semantic textual similarity, clustering, etc. We have used cosine similarity for the measure of similarity between two embedded vector as it fulfills the two basic criteria 1. We want a score where 0 represents highly similar and 1 represents highly dissimilar. 2. In natural language tasks generally, it is good to practise to use cosine similarity.
