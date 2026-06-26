# 🤖 Smart Interview Assistant

An AI-powered interview preparation application built with **Streamlit**, **LangChain**, **RAG (Retrieval-Augmented Generation)**, **ChromaDB**, and **Groq LLM**. The application helps users practice technical interviews by analyzing resumes, extracting skills, generating interview questions, and evaluating answers with AI.

---

## 📌 Features

* 📄 Upload and analyze resume (PDF)
* 🛠 Extract technical skills from the resume
* 📚 Upload custom interview questions PDF
* 🤖 Generate interview questions using RAG
* ✍️ Submit interview answers
* 📊 AI-based answer evaluation
* 💡 Detailed feedback with strengths, weaknesses, and improvement suggestions
* 🎨 Interactive web interface built using Streamlit

---

## 🛠 Technologies Used

* Python
* Streamlit
* LangChain
* ChromaDB
* Hugging Face Embeddings
* Groq API
* PDFPlumber
* PyPDF
* Pandas

---

## 📂 Project Structure

```
Smart-Interview-Assistant/
│
├── app.py
├── evaluator.py
├── rag.py
├── resume_parser.py
├── skill_extractor.py
├── requirements.txt
├── Interview Questions.pdf
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/smart-interview-assistant.git
```

### 2. Navigate to the Project Folder

```bash
cd smart-interview-assistant
```

### 3. Create a Virtual Environment (Optional)

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Application

```bash
streamlit run app.py
```

The application will open automatically in your browser.

---

## 🚀 How It Works

1. Upload your resume in PDF format.
2. The application extracts text from the resume.
3. Technical skills are detected automatically.
4. Upload an Interview Questions PDF.
5. The RAG pipeline retrieves relevant content and generates interview questions.
6. Enter your answer.
7. The AI evaluates your response and provides detailed feedback.

---

## 👨‍💻 Developed By

**Sai Sushmitha**

---

## 📄 License

This project is developed for educational and learning purposes.
