# Event Timeline Detection

[!Python 3.7](https://img.shields.io/badge/Python-3.7-blue.svg)

# Description
This project aims to understand cause and effect relation between a pair of sentences. 
For example: 1. The ball hit his head. 
             2. He started crying in pain.
             
In the above pair of sentences, sentence 2 makes sense only if sentence 1 has occurred. So the correct order of these events coccurring woud be - ball hitting the head followed by crying in pain.

## Execution Instructions

●	Before executing:
○	Download GoogleNews-vectors-negative300.bin.gz model for word2vec
○	Download en_core_web_sm model for SpaCy
○	In the second cell of word2vec_final.ipynb notebook, enter correct filepath for GoogleNews-vectors-negative300.bin.gz
○	After installing spacy using pip install spacy on Anaconda prompt, download the corpus by the command python -m download spacy en_core_web_sm
○	Ensure that the data set files are in the same folder as the jupyter notebook files.

●	To execute a file:
○	Run jupyter notebook.
○	Load the .ipynb file into jupyter
○	Click on Run button  once the kernel is ready.


