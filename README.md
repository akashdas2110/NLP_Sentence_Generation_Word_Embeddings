2>Generate Sentences and Word Embeddings : Using 4-Gram Model, POS Tagging and COALS Algorithm
     Sept 2023 - Nov 2023
      
     Main objective is to generate sentences using probabilistic model and 
     word embeddings based on WIKI_DUMP english corpus.
a)	Verify Zipf’s Law and Heaps Law on the cleaned corpus.
b)	Build a 4-Gram Model to find the next word using the probability distribution. Then used POS Tagging to generate sentences of length 10 for a given random start word. Avoid using the, in, a, or an as the starting word.
c)	Implement COALS algorithm to create co-occurrence matrix.Here the semantic similarity between two words is given by the correlation of their vectors.Then generate five similar words for each given input word.Matrix heat map used to display the similarity of words along with the cosine distance score.
