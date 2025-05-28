```markdown
# Face Recognition Platform with Real-Time AI Q&A

This is a full-stack AI-powered face recognition platform built for the **Katomaran AI Hackathon**. It enables users to register faces via webcam, recognize them in real-time, and ask queries related to registration using a chat interface powered by a RAG (Retrieval-Augmented Generation) engine.

---

## 🚀 Features

- 📷 **Face Registration**: Capture face via webcam and store with metadata
- 🧠 **Real-Time Face Recognition**: Detect and recognize multiple faces live
- 💬 **RAG-based Chat Interface**: Ask queries like “Who was the last person registered?”

---

## 🧰 Tech Stack

| Module             | Tech Stack                        |
|--------------------|-----------------------------------|
| Frontend           | React.js                          |
| Backend (API)      | Python (`Flask` or similar)       |
| Face Recognition   | Python (`face_recognition`, `OpenCV`) |
| RAG Engine         | Python (`LangChain`, `FAISS`, `OpenAI API`) |
| Communication      | WebSockets                        |
| Database           | Any (e.g., SQLite, MongoDB)       |
| LLM                | OpenAI ChatGPT                    |

---

## 📁 Folder Structure

```

Face\_reconization-02/
├── frontend/              # React app
├── backend/               # Python backend + RAG engine
├── face\_recognition/      # Face registration & recognition logic
├── database/              # DB initialization and schema
├── logs/                  # Logs for events and errors
├── requirements.txt       # Python dependencies
└── architecture.png       # Architecture diagram

````

---

## ⚙️ Setup Instructions

### 1. Install Frontend Dependencies

```bash
cd frontend
npm install
````

### 2. Install Backend Dependencies

```bash
cd ../
pip install -r requirements.txt
```

### 3. Run the Backend

```bash
cd backend
python app.py
```

### 4. Run the Frontend (in a new terminal)

```bash
cd frontend
npm run dev
```

---

## 🔍 Example Queries

Use the chat interface to ask:

* "Who was the last person registered?"
* "At what time was Karthik registered?"
* "How many people are currently registered?"

---

## 🧠 Architecture

![Architecture](architecture.png)

---

## 🎥 Demo Video

👉 [Watch Demo on Google Drive](https://drive.google.com/file/d/1C6bfajfGbDTtLInquNSDhLvqsBDHrVD1/view?usp=sharing)

---

## 📌 Assumptions

* Python backend is structured using `Flask` (or similar)
* SQLite is used for quick local DB setup
* OpenAI API key is required and managed securely
* LangChain is used to manage vector DB (FAISS) and RAG logic

---

## 📜 Logs

* Logs are stored in the `logs/` folder
* Includes registration and recognition events with timestamps

---

## 📢 Notes

* Good UI/UX is considered and React is used for dynamic interaction
* Modular code structure to allow easy scaling and debugging
* Developed and tested on a local laptop, performance may vary based on hardware

---

## 📌 Submission Info

This project is a part of a hackathon run by [https://katomaran.com](https://katomaran.com)

---

```

Let me know if you want this saved as a `.md` file or if you'd like me to embed the architecture diagram or help generate it.
```
