# Language_detection_and_translation

A simple Flask web application that detects the language of a given text and translates it into a selected target language using **Google Translate** and **LangDetect**.

## 🚀 Features

- 🔍 Detects the language of input text using `langdetect`
- 🌐 Translates text into multiple languages using `googletrans`
- 🌍 Dropdown to choose from over 100+ supported languages
- 📱 Clean and responsive Bootstrap-based UI

## 🖥️ Demo

---

## 🛠️ Tech Stack

- Python 3.x
- Flask
- langdetect
- googletrans (v4.0.0-rc1)
- Bootstrap 4

---

## 🔧 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/Aditee01/lang-translate-app.git
cd lang-translate-app

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

pip install -r requirements.txt
pip install flask langdetect googletrans==4.0.0-rc1
python app.py
Visit http://127.0.0.1:5000 in your browser.

📂 Project Structure
├── app.py
├── templates/
│   └── index.html
└── README.md
