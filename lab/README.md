Folder named "lab" contains a notebook which:
1. Using synchronic word embedding: compares word2vec to LSA vectors in solving the analogy task
2. Using diachronic embeddings: proposing and evaluating methods for measuring degree of semantic change

Note that `exercise` folder in the repository (one level of folder organization higher) contains the notebook to generate LSA vectors/vocabulary

For reproducing experiments, the steps would be:
1. run notebook in `exercise/` folder first to generate LSA vectors (or use LSA vectors already stored under `lab/data`)
2. download required word2vec embeddings (into `data` folder), or diachronic embeddings
3. run `lab.ipynb`

