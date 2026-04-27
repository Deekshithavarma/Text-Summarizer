# 📝 Text Summarizer (T5 + FastAPI)

A web-based Text Summarization application built using the T5 Transformer model. This project allows users to input long text and generate concise summaries through a FastAPI backend and a simple, responsive frontend interface.

---

## 🚀 Features

- Text summarization using T5 Transformer  
- FastAPI backend for efficient API handling  
- Clean and user-friendly frontend UI  
- Handles long text inputs (up to 512 tokens)  
- Easy to extend and deploy  

---

## 🧠 Model Details

- Model: T5 (Text-to-Text Transfer Transformer)  
- Framework: HuggingFace Transformers  
- Backend: PyTorch  
- Fine-tuned for text summarization tasks  

---

## 🛠️ Tech Stack

- Python  
- FastAPI  
- HuggingFace Transformers  
- PyTorch  
- HTML, CSS, JavaScript  


---

## ⚙️ Installation & Setup

### 1. Clone the Repository

git clone https://github.com/your-username/text-summarizer.git  
cd text-summarizer  

---

### 2. Create Virtual Environment (Recommended)

**Windows**

python -m venv venv  
venv\Scripts\activate  

**Mac/Linux**

python3 -m venv venv  
source venv/bin/activate  

---

### 3. Install Dependencies

pip install -r requirements.txt  

---

## 🧠 Model Setup (Required)

⚠️ The trained model is not included in this repository due to file size limitations.

To use this application, you need to generate the model by running the training notebook.

---

### Steps to Generate the Model

1. Open the notebook:  
   `text_summarizer.ipynb`

2. Run all cells (preferably in Google Colab)

3. Save the model:

model.save_pretrained("./saved_summary_model")  
tokenizer.save_pretrained("./saved_summary_model")  

---

### Expected Folder Structure

saved_summary_model/
├── config.json  
├── model.safetensors  
├── tokenizer.json  
├── tokenizer_config.json  

---

### Place the Model

text-summarizer/
├── app.py  
├── saved_summary_model/  

---

## ▶️ Run the Application

uvicorn app:app --reload  

---

## 🌐 Open in Browser

http://127.0.0.1:8000  

---

## 🙌 Acknowledgements

- HuggingFace Transformers  
- T5 Model by Google Research  
- FastAPI  

---

## 📧 Contact

Feel free to reach out for suggestions or improvements!
