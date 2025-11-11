# Vibe-Matcher-Prototype


Vibe Matcher is a prototype recommendation system that matches products to a user's natural-language "vibe" query. Product descriptions are converted into **vector embeddings** using **SentenceTransformers**, and **cosine similarity** identifies the top-3 matches. The system handles low-similarity queries and includes visualizations. It can be extended with **OpenAI embeddings** or a **vector database** for production deployment.

## Features
- Converts product descriptions into vector embeddings.
- Computes similarity with user queries.
- Returns top-3 recommended products with scores.
- Handles low-similarity queries with fallback messages.
- Includes plots for similarity visualization.
- Logs latency metrics for evaluation.

## Files
- `Vibe_Matcher.ipynb` — Main Colab notebook with implementation, test queries, and plots.
- `requirements.txt` — Python dependencies for easy setup.
- `assets/` — Optional folder for screenshots of outputs or plots.

## Setup
1. Clone the repository:
```bash
git clone https://github.com/yourusername/Vibe-Matcher-Prototype.git
Navigate to the folder:

bash
Copy code
cd Vibe-Matcher-Prototype
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Open the notebook in Colab or Jupyter to run:

bash
Copy code
jupyter notebook Vibe_Matcher.ipynb
Notes
Local embeddings are used for fast experimentation.

OpenAI embeddings or a vector database can be integrated for production.

Lightweight, reproducible, and easy to extend.

#Author
Shravani Satarkar — B.Tech CSE (AIML), GH Raisoni College of Engineering
