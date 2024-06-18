# Embedding-Clustering
Clustering Documents with OpenAI embeddings, HDBSCAN, and UMAP -- Check the notebook.

OpenAI_API_KEY is needed, please add the key to the `.env` file:

```plaintext
OPENAI_API_KEY=<your-api-key>
```

## Installation

Please install the environment:

```sh
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

The data can be obtained from [Kaggle](https://www.kaggle.com/datasets/dylanjcastillo/news-headlines-2024?resource=download).

Thanks for the sharing from [DYLAN CASTILLO](https://dylancastillo.co/clustering-documents-with-openai-langchain-hdbscan/amp/).

Based on his code, I added the evaluation on the choice of parameters in HDBSCAN `min_samples and `min_cluster_size using methods such as `Silhouette-Score and `Davies-Bouldin Index, as well as visualizations.
