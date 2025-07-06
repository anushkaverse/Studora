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

## 🚀 Getting Started

### 🔧 1. Clone the Repository

``bash
git clone https://github.com/anushkaverse/studora.git
cd studora

📦 2. Create a Virtual Environment (Recommended)
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

📥 3. Install Required Libraries
bash
Copy
Edit
pip install -r requirements.txt

🔑 4. Add Your Gemini API Key
Create a .env file in the root folder:

ini
Copy
Edit
GOOGLE_API_KEY=your_gemini_api_key_here
You can get your API key from Google AI Studio.

▶️ 5. Run the App
bash
Copy
Edit
streamlit run app.py
The app will launch in your default browser at http://localhost:8501.


🗂️ Project Structure

├── app.py                # Main Streamlit interface
├── mechanics.py          # Transcript extraction & Gemini logic
├── requirements.txt      # Project dependencies
├── .env                  # Your Gemini API key
├── visuals/              # 💡 Screenshots & app previews
├── README.md


🤝 Contributing
Pull requests are welcome! If you'd like to suggest a feature or fix a bug, please open an issue first.

📄 License
This project is licensed under the MIT License. Feel free to use, modify, and share it for educational or personal purposes.

🌐 Live Demo (optional)
If deployed via Streamlit Community Cloud:

🔗 studora.streamlit.app

🙌 Acknowledgements
Google Generative AI (Gemini)

Streamlit

YouTube Transcript API
