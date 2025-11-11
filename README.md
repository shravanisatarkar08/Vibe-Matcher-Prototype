# Vibe-Matcher-Prototype

Vibe Matcher is a prototype recommendation system that matches products to a user's natural-language "vibe" query. Product descriptions are converted into **vector embeddings** using **SentenceTransformers**, and product-query similarity is used for recommendations.

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

1. **Clone the repository:**
   ```bash
   git clone https://github.com/shravanisatarkar08/Vibe-Matcher-Prototype.git
   cd Vibe-Matcher-Prototype
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the notebook to run:**
   - In Jupyter:
     ```bash
     jupyter notebook Vibe_Matcher.ipynb
     ```
   - Or open `Vibe_Matcher.ipynb` directly in Google Colab.

---

**Notes:**
- The prototype uses local embeddings for fast experimentation.
- For production use, you can integrate OpenAI embeddings or connect to a vector database.
- The codebase is lightweight, reproducible, and easy to extend.

## Author
Shravani Satarkar — B.Tech CSE (AIML), GH Raisoni College of Engineering
