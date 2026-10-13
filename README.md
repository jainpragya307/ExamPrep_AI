# ExamPrep AI 🎓

**ExamPrep AI** is an AI-powered exam preparation web application built using Python and Streamlit. It helps students prepare for exams by generating answers from uploaded study materials, creating MCQ quizzes, and tracking their learning progress.

## 🚀 Features

* **User Authentication:** Students can register and log in to their accounts.
* **PDF Upload:** Upload study notes, syllabus documents, and previous-year question papers in PDF format.
* **AI-Powered Question Answering:** Ask questions and generate answers using Google Gemini AI.
* **Flexible Answer Length:** Generate answers suitable for 2, 4, 7, or 10 marks.
* **MCQ Quiz Generator:** Generate multiple-choice quizzes for exam practice.
* **Quiz Scores:** View quiz results and correct answers.
* **Chat History:** Save and revisit previous question-and-answer conversations.
* **Quiz History:** Track previous quiz attempts and scores.
* **Beyond-Syllabus Learning:** Use Generative AI to explore topics and generate answers beyond the information available in uploaded study materials.

## 🛠️ Technologies Used

* **Python** — Application programming
* **Streamlit** — Web application interface
* **Google Gemini API** — AI-powered answer and quiz generation
* **PyMuPDF (fitz)** — PDF text extraction
* **SQLite** — Local database storage
* **bcrypt** — Password hashing

## 📂 Project Structure

```text
ExamPrep_AI/
├── app1.py
├── requirements.txt
├── database/
│   └── examprep_ai.sql
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/jainpragya307/ExamPrep_AI.git
cd ExamPrep_AI
```

### 2. Install the required packages

```bash
pip install -r requirements.txt
```

### 3. Configure the Gemini API key

Create a `.streamlit/secrets.toml` file in the project directory and add your Gemini API configuration:

```toml
[gemini]
model = "YOUR_SUPPORTED_GEMINI_MODEL"
```

Replace the placeholders with your actual API key and a model name supported by your Gemini API account.

**Important:** Never upload your API key or `secrets.toml` file to GitHub.

### 4. Run the application

```bash
streamlit run app1.py
```

The application will open in your browser.

## 📖 How to Use

1. Register for an account or log in.
2. Upload a PDF containing study material or exam questions.
3. Ask a question related to your exam preparation.
4. Select the desired answer length.
5. Read the AI-generated answer.
6. Generate MCQ quizzes to test your knowledge.
7. Review your quiz scores and saved history.

## 🌟 Beyond-Syllabus Topic

The main beyond-syllabus technology used in this project is **Generative Artificial Intelligence (Generative AI)** through the Google Gemini API.

The PDS syllabus covers Python programming, data science, statistics, data preparation, and basic machine learning. This project extends those concepts by integrating a generative AI model to produce answers and practice quizzes dynamically.

## 🎯 Project Objective

The objective of ExamPrep AI is to make exam preparation easier, more interactive, and more accessible by combining Python programming with Generative AI. It helps students practice questions, understand concepts, and organize their exam preparation in one application.

## 🔮 Future Enhancements

* Support for additional document formats.
* Improved answer citations and source references.
* More quiz customization options.
* Additional progress reports and learning analytics.
* Enhanced AI response reliability and error handling.

## 👩‍💻 Author

**Pragya Jain**

Developed as a Python for Data Science academic project.

## 📄 License

This project is intended for educational and learning purposes.
