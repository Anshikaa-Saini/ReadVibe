# 📚 ReadVibe – A Semantic Book Recommender
ReadVibe is an AI-powered book recommendation system that helps you discover books based on the vibe you're looking for — whether it's a specific mood, tone, or theme. Just describe the kind of story you're in the mood for, and ReadVibe will suggest books that match your preferences using semantic similarity and emotional cues.


---

## 🧠 Features
✅ Semantic search powered by Sentence Transformers

✅ Emotion-based filtering 

✅ Genre-based filtering using labeled book categories

✅ Gradio UI – clean, interactive, and beginner-friendly frontend

✅ Lightweight backend using CSV + TXT files (no external DBs)

✅ Modular codebase – easy to upgrade with APIs, vector DBs, or RAG-based pipelines

✅ Clean display – multi-author formatting & neatly truncated descriptions


---

## 🛠️ Tech Stack

- **Frontend/UI**: Gradio
- **Embeddings**: `sentence-transformers/all-MiniLM-L6-v2`
- **Vector Store**: ChromaDB
- **Language**: Python 3.11+
- **Libraries**: LangChain, Pandas, NumPy, Hugging Face, Chroma


---

## 💡 How It Works
Input: User enters a short story description.

Embedding: The input is converted into vector embeddings using a pretrained transformer model.

Semantic Search: ChromaDB retrieves the most relevant book descriptions based on similarity.

Filtering: Results can be narrowed by category (genre) and emotion (tone).

Output: Books are displayed with cover, title, author(s), and a short snippet.


---

## 📌 Use Cases
📖 Personalized book recommendations

💬 Emotion-aware literature discovery

🎓 Semantic retrieval engine for edtech or storytelling platforms

