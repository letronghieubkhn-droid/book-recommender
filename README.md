🧠 Build a Semantic Book Recommender 

🧩 Project Components
This tutorial is divided into five main components:
1. Text Data Cleaning
File: data-exploration.ipynb
Preprocess and clean raw text data to prepare it for embedding and analysis.

2. Semantic (Vector) Search and Database Construction
File: vector-search.ipynb
Build a vector database to perform semantic search, allowing users to find books based on natural language queries (e.g., "a story about revenge").

3. Text Classification (Zero-Shot Learning)
File: text-classification.ipynb
Classify books into “fiction” or “non-fiction” categories using LLM zero-shot classification, enabling users to filter books by type.

4.Sentiment Analysis
File: sentiment-analysis.ipynb
Use LLMs to analyze sentiment and emotional tone (e.g., joyful, suspenseful, sad), allowing books to be sorted by mood or atmosphere.

5.Web Application (Gradio Dashboard)
File: gradio-dashboard.py
Build an interactive Gradio interface for users to get book recommendations, visualize data, and explore results.

⚙️ Requirements
This project was developed using Python 3.11.
You’ll need to install the following dependencies before running the project:
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
A complete list of dependencies is provided in the requirements.txt file included in this repository.

🔑 Setup Instructions
1. Clone the repository
https://github.com/letronghieubkhn-droid/book-recommender.git

2. Install dependencies
pip install -r requirements.txt

3. Create a .env file in the root directory and add your OpenAI API key
OPENAI_API_KEY=your_api_key_here

4. Follow the course instructions
Use the provided notebooks to build, index, and query your vector database.

📊 Data Source
The dataset for this project is available on Kaggle.
Instructions for downloading and loading the data are provided in the tutorial and repository documentation.

🚀 Key Features
- End-to-end semantic search and recommendation system using LLMs
- Zero-shot classification — no manual labeling required
- Built-in sentiment and emotion analysis
- Interactive Gradio dashboard for book exploration
- Modular and well-documented Jupyter notebooks for each step