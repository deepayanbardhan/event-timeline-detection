# Event Timeline Detection


# Description
This project aims to understand cause and effect relation between a pair of sentences. \
For example: 1. The ball hit his head.
             2. He started crying in pain.
             
In the above pair of sentences, sentence 2 makes sense only if sentence 1 has occurred. So the correct order of these events coccurring woud be - ball hitting his head followed by him crying in pain.

# Motivation
Achieving this task can be useful to create chatbots that can understand link between events, proving beneficial in answering questions by accessing knowledge base.

## Execution Instructions

●	Before executing:
- Download GoogleNews-vectors-negative300.bin.gz model for word2vec
- Download en_core_web_sm model for SpaCy
- In the second cell of word2vec_final.ipynb notebook, enter correct filepath for GoogleNews-vectors-negative300.bin.gz
- After installing spacy using pip install spacy on Anaconda prompt, download the corpus by the command python -m download spacy en_core_web_sm
- Ensure that the data set files are in the same folder as the jupyter notebook files.

●	To execute a file:
- Run jupyter notebook.
- Load the .ipynb file into jupyter
- Click on Run button  once the kernel is ready.


# Advantage
I have used a variation of doc2vec technique to create word embedding techniques which takes into consideration the occurrence of the pair of sentences in the entire document under consideration. The traditional word2vec and SpaCy word embedding techniques consider the pair of sentences as stand-alone. So, using the inverse document frequency, I am able to associate words closer to one another while also discarding stop words or words that are extremely common and not associated to the particular sentence. 
