# Clustering
Clustering Documents with OpenAI embeddings, HDBSCAN and UMAP -- Check notebook

OpenAI_API_KEY is needed, please add the key to .env file

OPENAI_API_KEY=<your-api-key>

Please install the environment:

python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

The data can be obtained from \ref{https://www.kaggle.com/datasets/dylanjcastillo/news-headlines-2024?resource=download}{Kaggle}

Thanks for the sharing from \ref{https://dylancastillo.co/clustering-documents-with-openai-langchain-hdbscan/amp/}{DYLAN CASTILLO}
Based on his code, I added the evaluation on the choice of parameters in HDBSCAN min_samples and min_cluster_size using method Silhouette Score and Davies-Bouldin Index as well as visualizations. # Embedding-Clustering
# Embedding-Clustering
