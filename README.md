# ⚡ AI Flashcard Generator

A full-stack web application designed to help students and researchers streamline their study workflows. This tool instantly transforms dense notes, articles, or research papers into high-quality, study-ready flashcards using AI. 

Instead of generating a fixed or forced number of cards, the application evaluates the density of the text to dynamically create the perfect amount of high-yield flashcards without filler.

## ✨ Features
* **Dynamic AI Generation:** Powered by Gemini 2.5 Flash with strict JSON formatting to guarantee structured card output.
* **Smart Density Processing:** Automatically determines the natural density of the material to generate an appropriate number of flashcards.
* **Interactive UI:** A clean, responsive interface featuring interactive card flipping for easy active recall study sessions.
* **Data Portability:** Built-in support to download generated cards instantly into Anki-compatible CSV/TSV formats.

## 🛠️ The Tech Stack
* **Frontend:** HTML5, CSS3, JavaScript (ES6+) — Hosted on **GitHub Pages**
* **Backend:** Node.js, Express.js — Deployed on **Render**
* **Database:** MongoDB Atlas
* **AI Model:** Google Gemini 2.5 Flash API (`@google/generative-ai`)

## 📂 Project Structure
```text
├── frontend/
│   └── index.html          # Clean UI with card flipping & export logic
└── backend/
    ├── index.js            # Node/Express API handling AI routes & CORS
    ├── package.json        # Project dependencies
    └── .env                # Secure environment variables (local only)
