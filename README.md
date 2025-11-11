# 🧠 Semantic Book Recommender

A compact tutorial and example project that walks through building an end-to-end semantic book recommender using embeddings, vector search, zero-shot classification, sentiment analysis, and a Gradio dashboard.

## Project components

This tutorial is divided into five main components (files included in this repository):

1. Text Data Cleaning — `data-exploration.ipynb`
   - Preprocess and clean raw text data to prepare it for embedding and analysis.
2. Semantic (Vector) Search and Database Construction — `vector-search.ipynb`
   - Build a vector database to perform semantic search (e.g., query: "a story about revenge").
3. Text Classification (Zero-Shot Learning) — `text-classification.ipynb`
   - Classify books into `fiction` or `non-fiction` using LLM zero-shot classification.
4. Sentiment Analysis — `sentiment-analysis.ipynb`
   - Analyze sentiment and emotional tone (joyful, suspenseful, sad) with LLMs.
5. Web Application (Gradio Dashboard) — `gradio-dashboard.py`
   - Interactive interface for recommendations, visualization, and exploration.

## Requirements

Tested with Python 3.11. Install dependencies from the bundled file:

```powershell
pip install -r requirements.txt
```

Common dependencies include:

- kagglehub
- pandas
- matplotlib
- seaborn
- python-dotenv
- langchain-community
- langchain-opencv
- langchain-chroma
- transformers
- gradio
- notebook
- ipywidgets

## Setup

1. Clone the repository:

```powershell
git clone https://github.com/letronghieubkhn-droid/book-recommender.git
cd book-recommender\llm-semantic-book-recommender
```

2. Create and populate a `.env` file in the project root with your OpenAI key:

```
OPENAI_API_KEY=your_api_key_here
```

3. Install Python dependencies (see Requirements section):

```powershell
pip install -r requirements.txt
```

4. Follow the notebooks in order: start with `data-exploration.ipynb`, then `vector-search.ipynb`, `text-classification.ipynb`, `sentiment-analysis.ipynb`. The `gradio-dashboard.py` script provides a simple web UI.

## Data

The dataset used in this tutorial is available on Kaggle. See the notebooks for instructions on how to download and load the dataset.

## How to run the Gradio dashboard (quick)

After preparing data and embeddings, run the dashboard:

```powershell
python gradio-dashboard.py
```

Open the provided local URL in your browser to interact with the recommender.

## Key features

- End-to-end semantic search and recommendation using embeddings
- Zero-shot classification (no manual labels required)
- Sentiment and emotion analysis
- Interactive Gradio dashboard for exploration
- Modular notebooks for each step of the pipeline



