# 📝 Text Summarizer (T5 + FastAPI)

A web-based Text Summarization application built using the T5 Transformer model. This project allows users to input long text and generate concise summaries through a FastAPI backend and a simple, responsive frontend interface.

---

## 🚀 Features

- 🔹 Text summarization using T5 Transformer
- 🔹 FastAPI backend for efficient API handling
- 🔹 Clean and user-friendly frontend UI
- 🔹 Handles long text inputs (up to 512 tokens)
- 🔹 Easy to extend and deploy

---

## 🧠 Model Details

- Model: T5 (Text-to-Text Transfer Transformer)
- Framework: HuggingFace Transformers
- Backend: PyTorch
- The model is fine-tuned for text summarization tasks

---

## 🛠️ Tech Stack

- Python
- FastAPI
- HuggingFace Transformers
- PyTorch
- HTML, CSS, JavaScript

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

git clone https://github.com/your-username/text-summarizer.git  
cd text-summarizer

---

### 2️⃣ Create Virtual Environment (Recommended)

# Windows
python -m venv venv
venv\Scripts\activate

# Mac/Linux
python3 -m venv venv
source venv/bin/activate

---

### 3️⃣ Install Dependencies

pip install -r requirements.txt
---

### 5️⃣ Run the Application

uvicorn app:app --reload

---

### 6️⃣ Open in Browser

http://127.0.0.1:8000

---

### 7️⃣ Test API (Optional)

http://127.0.0.1:8000/docs
