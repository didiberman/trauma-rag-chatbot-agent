# 🧠 Trauma-Informed RAG Chatbot

This project is a **Retrieval-Augmented Generation (RAG)** chatbot that answers trauma-related questions grounded in texts from Gabor Maté, Thomas Hübl, and other somatic/psychological wisdom sources. It uses `LangChain` to retrieve relevant passages and generate insightful, emotionally aware responses using a local or cloud-based LLM.

---

## 🔍 What It Does

- Loads and chunks trauma-related text files
- Embeds them using `OpenAIEmbeddings` (or local alternatives)
- Stores embeddings in `ChromaDB` (or FAISS)
- Retrieves the most relevant chunks for each user query
- Uses an LLM (e.g., GPT-3.5 / Claude / Mistral / Ollama) to answer questions with reference to the source material

---

## 🧰 Tech Stack

- 🧠 **LangChain** – Orchestration of retrieval + generation
- 🗂️ **ChromaDB** – Local vector database for embedding search
- 🔠 **OpenAI / Ollama** – LLM for generating responses
- 📚 **Markdown/Text/PDF loaders** – for your personal trauma text sources
- 🧪 **Streamlit** *(optional)* – UI for easy interaction

---

## 🚀 How to Run

1. **Clone the repo**  
```bash
git clone https://github.com/yourusername/trauma-rag-chatbot.git
cd trauma-rag-chatbot
```

2. **Install dependencies**  
```bash
pip install -r requirements.txt
```

3. **Set your `.env` file**  
```
OPENAI_API_KEY=your-key
```

4. **Run the app**  
```bash
python app.py
```

Or if using Streamlit:
```bash
streamlit run app.py
```

---

## 💬 Example Q&A

**Q**: Why do I feel disconnected from my body after trauma?  
**A**: Based on Thomas Hübl's work, trauma often interrupts the nervous system’s ability to stay present. Disconnection from the body is a protective adaptation to unbearable sensations.

---

## 🧠 Skills Demonstrated

- LangChain chains and retrieval techniques
- Embedding + chunking strategies
- Building a local RAG pipeline (MVP)
- Clean, modular code for real-world use
- Deployable RAG chatbot structure

---

## 📂 Project Structure

```
trauma-rag-chatbot/
├── data/                 # Source texts (e.g., Gabor Maté excerpts)
├── app.py                # Main chatbot logic
├── requirements.txt
├── .env                  # API keys
└── README.md             # This file
```

---

## 📌 Future Enhancements

- Switch to **local LLM** via Ollama or Hugging Face
- Add **feedback logging** and analytics
- Integrate **summarization** and **content clustering**
- Add frontend to embed on personal site

---

## 👤 Author

**Didi Berman** – AI & Automation Engineer | Trauma-Informed Tech Creator  
Helping people build humane tools with AI & nervous system awareness  
[🌐 didiberman.com](https://didiberman.com) · [💻 GitHub](https://github.com/didiberman)

---

## 🔖 Keywords

`rag` `langchain` `trauma` `gabor mate` `ai chatbot` `embeddings` `mental health` `chroma` `fastapi` `streamlit` `mlops` `openai` `ollama`
