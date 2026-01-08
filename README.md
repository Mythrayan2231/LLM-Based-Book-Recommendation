📖 LLM Book Recommender

Intelligent, LLM-Powered Personalized Book Recommendation Engine

🧭 Overview

The LLM Book Recommender is an AI-driven recommendation system that leverages Large Language Models (LLMs) to deliver context-aware, personalized book suggestions.
By combining vector similarity search, zero-shot text classification, and sentiment analysis, the system understands user intent beyond keywords and provides highly relevant recommendations.

An interactive Gradio-based UI enables real-time exploration and seamless user interaction, making the system both powerful and accessible.

✨ Core Capabilities
📚 Intelligent Book Recommendations

Context-aware recommendations using semantic embeddings

Personalized results based on user input descriptions

🔍 Vector Similarity Search

High-performance semantic search using FAISS

Embedding-based retrieval for accurate matching

🎯 Zero-Shot Text Classification

Categorizes books without task-specific training

Dynamically adapts to unseen genres and topics

❤️ Sentiment-Aware Filtering

Analyzes emotional tone of book descriptions

Enhances recommendation relevance

🎨 Interactive User Interface

Clean, responsive Gradio dashboard

Real-time inference and result visualization

🛠️ Technology Stack
Programming & ML

Python – Core development language

LangChain – LLM orchestration and workflow management

Hugging Face Transformers – Pretrained LLMs

Vector Search & Data

FAISS – Scalable vector similarity search

Scikit-learn & Pandas – Data preprocessing and analysis

UI & Tooling

Gradio – Interactive ML application interface

GitHub – Version control and collaboration

🧠 System Architecture Highlights

Embedding-based semantic retrieval pipeline

Modular ML components for classification and sentiment analysis

LLM-driven inference with minimal task-specific training

Designed for extensibility and experimentation

🏗️ Installation & Setup
Prerequisites

Python 3.8+

pip package manager

Clone the Repository:

git clone https://github.com/Mythrayan2231/LLM-Based-Book-Recommendation.git
cd LLM-Based-Book-Recommendation

Install Dependencies
pip install -r requirements.txt

Run the Application
python gradio-dashboard.py

📖 How It Works

User enters book description or selects an option

Text is embedded via LLMs

FAISS performs semantic similarity search

Zero-shot classification assigns contextual labels

Sentiment analysis refines recommendations

Results render instantly in Gradio UI

📂 Project Structure
LLM-Based-Book-Recommendation/
│── models/                     # Pretrained & processed ML models
│── data/                       # Datasets and embeddings
│── main.py                     # Core LLM processing logic
│── gradio-dashboard.py         # Interactive Gradio UI
│── vector-search.ipynb         # Semantic similarity experiments
│── sentiment-analysis.ipynb    # Sentiment modeling
│── text-classification.ipynb   # Zero-shot classification
│── requirements.txt            # Python dependencies
└── README.md                   # Project documentation

🌱 Future Enhancements

User profile-based personalized recommendations

Hybrid collaborative + content filtering

Cloud deployment with scalable inference

User feedback loop for quality improvement

🤝 Contributors

LLM pipeline design, model integration, and application development by Mythrayan NP

🏆 Why Recruiters Love This Project

Demonstrates practical LLM application

Covers vector search & NLP fundamentals

Showcases zero-shot learning & sentiment modeling

Includes production-style interactive UI
