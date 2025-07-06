# 🎓 Studora — Your Next Gen Preparation Coach 📚

**Studora** is a modern AI-powered study assistant that transforms YouTube lecture/tutorial videos into structured, downloadable study materials — all in one click. Built using **Streamlit**, **Python**, and **Google Gemini API**, Studora helps students instantly generate summaries, flashcards, revision plans, and extra resources from any educational video.

---

## ✨ Features

- 🔗 **YouTube to Notes**  
  Paste any public YouTube lecture/tutorial URL and get study material in seconds.

- 🎓 **Learning Level Personalization**  
  Choose from Beginner, Intermediate, or Advanced to tailor the output's complexity.

- 📝 **Smart Summarization**  
  Extracts meaningful points using Gemini AI with difficulty-specific tone.

- 🃏 **Auto Flashcard Generator**  
  Converts content into quick-revision Q&A flashcards.

- 📅 **5-Day Revision Plan**  
  AI-crafted schedules with topic focus, time estimates & sample questions.

- 🔗 **Extra Learning Resources**  
  Curated external videos/articles for deeper understanding.

- 📥 **Downloads in TXT & PDF**  
  Export any generated content for offline study.

- 📊 **Study Dashboard & History**  
  Auto-saves every session and displays a personalized dashboard.

- 💌 **Feedback Form**  
  Collects user insights via sidebar form.

---

## 🧑‍💻 Tech Stack

| Area              | Tools Used                          |
|-------------------|-------------------------------------|
| Frontend          | Streamlit                           |
| Backend           | Python 3.10+                        |
| AI Model          | Google Gemini (via `google-generativeai`) |
| Transcript Engine | `youtube-transcript-api`            |
| Styling & Export  | Custom HTML/CSS, FPDF               |
| Environment       | dotenv (`.env`) for API key storage |

---

## Getting Started

### 1. Clone the Repository

git clone https://github.com/yourusername/studora.git
cd studora

mathematica
Copy
Edit

### 2. Set Up Virtual Environment (Optional but recommended)

python -m venv venv

markdown
Copy
Edit

**For Windows:**

venv\Scripts\activate

markdown
Copy
Edit

**For macOS/Linux:**

source venv/bin/activate

shell
Copy
Edit

### 3. Install Dependencies

pip install -r requirements.txt

pgsql
Copy
Edit

### 4. Add Google Gemini API Key

Create a `.env` file in the project root directory and add the following line:

GOOGLE_API_KEY=your_gemini_api_key_here

shell
Copy
Edit

### 5. Run the App

streamlit run app.py

---

## Project Structure

studora/
│
├── app.py
├── mechanics.py
├── requirements.txt
├── .env
├── feedback.txt
├── visuals/
│ ├── main_interface.png
│ ├── summary_tab.png
│ ├── flashcards_tab.png
│ ├── revision_tab.png
│ ├── resources_tab.png
│ └── dashboard_history.png
├── README.md

---

## License

MIT License

## Acknowledgements

- Google Generative AI
- Streamlit
- YouTube Transcript API
