# 🤖 AI Smart Document Generator (LLM Powered)

An intelligent **Generative AI chatbot** that can automatically generate multiple types of documents such as **Grade Cards, Reports, and Invitation Cards** from user input or uploaded files.

The system uses **LLM models via Ollama and LangChain** to generate structured documents and allows users to export them as **PDF or image cards**.

---

# 🚀 Project Overview

This project is an AI-powered document generation system that enables users to:

• Generate **Student Grade Cards** from provided marks
• Create **Professional Reports** from structured data
• Generate **Invitation Cards** (Wedding, Birthday, Event)
• Upload **CSV / Excel files** for automated report creation
• Download results as **PDF documents or invitation images**

The system integrates **Large Language Models (LLMs)** with **LangChain workflows** to dynamically generate documents.

---

# 🧠 Key Features

✔ AI-powered document generation
✔ Chat-based user interaction
✔ Grade card generation from student data
✔ Wedding / event invitation generator
✔ File upload support (CSV / Excel)
✔ PDF export functionality
✔ Image-based invitation card creation
✔ Modular architecture for future expansion
---

# 🏗️ System Architecture

User Input (Chat / File Upload)
↓
Streamlit User Interface
↓
LangChain Controller
↓
LLM Engine (Ollama – Llama3)
↓
Document Generation Modules

• Grade Card Generator
• Invitation Card Generator
• Report Generator

↓
Output Formatting

• PDF Generator
• Image Invitation Card

↓
Final Downloadable Document

---

# ⚙️ Technologies Used

| Technology | Purpose                      |
| ---------- | ---------------------------- |
| Python     | Core programming language    |
| Streamlit  | Web interface for AI chatbot |
| LangChain  | LLM workflow management      |
| Ollama     | Local LLM runtime            |
| Llama3     | Large language model         |
| Pandas     | Data processing              |
| Pillow     | Image generation             |
| ReportLab  | PDF document generation      |

---

# 📁 Project Structure

```
ai-document-generator

│
├── app.py
├── llm_engine.py
├── grade_card.py
├── invitation_card.py
├── report_generator.py
│
├── utils
│   ├── file_parser.py
│   ├── pdf_generator.py
│   └── card_generator.py
│
└── data
```

---

# 🔧 Installation

### 1️⃣ Clone the repository

```
git clone https://github.com/yourusername/ai-document-generator.git
```

```
cd ai-document-generator
```

---

### 2️⃣ Install dependencies

```
pip install streamlit langchain langchain-community ollama pandas pillow reportlab
```

---

### 3️⃣ Install Ollama

Download from:

https://ollama.com

Pull the model:

```
ollama pull llama3
```

---

# ▶️ Run the Application

```
streamlit run app.py
```

Open browser:

```
http://localhost:8501
```

---

# 📊 Example Use Cases

### Example 1 — Grade Card Generation

Input

```
Name: Priya Singh
Math: 85
Science: 90
English: 88
```

Output

```
Student Grade Report

Total Marks: 263
Percentage: 87.6%

Priya Singh has demonstrated excellent academic performance.
```

---

### Example 2 — Wedding Invitation

Input

```
Event: Wedding
Bride: Anjali
Groom: Rahul
Date: 20 February
Venue: Kolkata
```

Output

Elegant wedding invitation message with a downloadable card image.

---

# 🔮 Future Improvements

• LangChain Agents for automatic document type detection
• RAG (Retrieval Augmented Generation) for document analysis
• Database integration for storing reports
• Multi-language document generation
• Advanced invitation card templates
• API deployment for web integration

---

# 📌 Resume Project Description

**AI Smart Document Generator using LLM**

Developed an AI-powered chatbot capable of generating grade cards, reports, and invitation cards from structured input or uploaded files. Integrated **LangChain with Ollama Llama3** for dynamic document generation and implemented **PDF export and image-based invitation card creation** using Python.

---

# 👩‍💻 Author

Priya Singh

MCA Student | AI & Data Science Enthusiast

Skills: Python • Machine Learning • Generative AI • Data Analysis

---

# ⭐ If you like this project

Please consider giving the repository a **star ⭐ on GitHub**.
