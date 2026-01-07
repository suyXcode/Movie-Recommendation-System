# 🎬 End-to-End Movie Recommendation System

An end-to-end **Movie Recommendation System** built with **FastAPI**, **Scikit-learn**, and **Streamlit** that recommends movies based on user input using NLP and machine learning. The system fetches live movie metadata from **TMDB API** and serves predictions through a REST API and a web UI.

---

## 🚀 Features

- 🎥 Content-based movie recommendation  
- 🧠 NLP using TF-IDF Vectorization  
- ⚡ FastAPI backend for recommendations  
- 🌐 Streamlit frontend interface  
- 🔑 Live movie data from TMDB API  
- 🧪 Pre-trained ML model with persistence  
- 🔐 Environment variable support using `.env`  

---

## 🛠 Tech Stack

| Layer | Technology |
|------|------------|
| Backend API | FastAPI, Uvicorn |
| ML | Scikit-learn, NumPy, SciPy |
| NLP | TF-IDF |
| Frontend | Streamlit |
| Data | Pandas |
| External API | TMDB API |

---

## 📂 Project Structure

End-to-End Movie Recommendation System/
│
├── main.py # FastAPI backend
├── app.py # Streamlit frontend
├── model.pkl # Trained ML model
├── vectorizer.pkl # TF-IDF vectorizer
├── vectorizer.pkl # TF-IDF vectorizer
├── requirements.txt
└── README.md

---


---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository

```bash
git clone <repo-url>
cd End-to-End Movie Recommendation System
```
### 2️⃣ Create and activate virtual environment
```
py -3.11 -m venv .venv
.venv\Scripts\Activate.ps1
```

### 3️⃣ Install dependencies
```
pip install -r requirements.txt
```
### 4️⃣ Create .env file
```
Create a file named .env in the project root:

TMDB_API_KEY=your_tmdb_api_key_here
```
### 5️⃣ Run the FastAPI server
```
python -m uvicorn main:app --reload


Visit: http://127.0.0.1:8000
```

### 6️⃣ Run the Streamlit frontend
```
streamlit run app.py
```

---

## 🔑 How to Get TMDB API Key

- Go to https://www.themoviedb.org
- Create an account → Settings → API
- Generate an API key (v3 auth)

```
🧪 Example API Response
{
  "recommendations": [
    "Inception",
    "Interstellar",
    "The Matrix"
  ]
}
```

---

## ⚠️ Notes

- Make sure scikit-learn version matches the one used for training the model.
- Do not commit .env file to GitHub.
- Use Python 3.11 for best compatibility.

## 📌 Future Improvements

- Collaborative filtering support
- User authentication
- Recommendation history
- Cloud deployment


---


## 👨‍💻 Author

**Suyash Singh**

*GitHub: https://github.com/suyXcode*
*Portfolio: https://suyxcode.netlify.app*



