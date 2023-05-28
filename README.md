# TitleSimilarityMeLi
Project of title cosine similarity between products in MeLi

## Word/PDF analysis of Case Selected 
- I included both formats to be able to visualize in repo 

## Exploration with multiple analysis 
#### (fixed examples, only to explore, not to be run again):
- Tf-Idf and Cosine similarity
- Word Embeddings (word2vec) and Cosine similarity 
  - Plot titles proximity (of title embedding) in 2D with PCA, TSNE, (with colors both from KMeans and original Categories)

## Implementation with selected analysis 
#### (meant to be run multiple times as a train/test solution, to get new examples):
- Selected Algorithm: Word Embeddings and Cosine similarity (due to simplicity of implementation, more robust algorithm and fastness/smaller cosine matrix)
- Selected Plot: 2D with PCA and TSNE (only original Categories, for better understanding)

## Pickles:
- Historical products for comparison and to minimaze computation time
- PCA for plot purposes, explain model importance and way of working to line of business 

#### Observations: word embeddings are downloaded from web, since the file is too heavy to upload to git repo
