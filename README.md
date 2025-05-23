🧠 Sentiment Mining with Transformers & Pinecone

Analyze hotel reviews using semantic search powered by Transformers and Pinecone.

🔧 What It Does
- Converts hotel reviews into vector embeddings.
- Stores them in Pinecone with sentiment and timestamps as metadata.
- Lets you semantically search and filter reviews (e.g., by hotel, date).
- Visualizes customer sentiment by topic (room size, food, AC, etc.).

 🛠 Tech Stack
- Python, Sentence-Transformers, Pinecone
- Pandas, Matplotlib
- Google Colab (recommended)

🚀 How to Use
1. Set up Pinecone:
   ```python
   from pinecone import Pinecone
   pc = Pinecone(api_key="YOUR_API_KEY")


cleanup: 
pc.delete_index("your-index-name")


for the full project making journey,
twitter: https://x.com/geetangii/status/1925565284263567614
