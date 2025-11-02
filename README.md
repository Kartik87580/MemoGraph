# 🧠 **MemoGraph**

### *Think. Connect. Remember.*

**MemoGraph** is a **memory-aware AI chatbot** built with **LangGraph**, **LangChain**, and **Google Gemini**, featuring a clean **Streamlit** interface and persistent chat memory for seamless conversations.

---

## 🚀 **Features**

* 💬 Real-time Gemini-powered responses
* 🧩 Graph-based conversational workflow
* 💾 Save & reload past conversations
* ⚡ Smooth and fast Streamlit UI

---

## 🧠 **Tech Stack**

| Component      | Technology                               |
| -------------- | ---------------------------------------- |
| **Frontend**   | Streamlit                                |
| **LLM**        | Google Gemini (`langchain-google-genai`) |
| **Frameworks** | LangGraph, LangChain                     |
| **Storage**    | Local JSON files                         |

---

## ⚙️ **Setup Instructions**

1. **Clone the repository**

   ```bash
   git clone https://github.com/Kartik87580/MemoGraph
   cd MemoGraph
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Set your Gemini API key**

   ```bash
   export GOOGLE_API_KEY="your_api_key"
   ```

4. **Run the Streamlit app**

   ```bash
   streamlit run app.py
   ```

---

## 📁 **Project Structure**

```
MemoGraph/
├── app.py              # Streamlit main app
├── graph.py            # LangGraph workflow logic
├── llm_utils.py        # Gemini model setup
├── memory_manager.py   # Chat memory management
├── requirements.txt    # Dependencies
└── data/
    └── conversations/  # Saved chat logs
```

---

## 💬 **How It Works**

1. Start chatting in Streamlit.
2. The app builds a LangGraph state pipeline with Gemini responses.
3. Each message is stored locally and can be reloaded anytime.

---

## ✨ **Author**

**Kartik Jambucha**


---

> 🧠 *MemoGraph — Conversations that remember.*

---
