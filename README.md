# 🏠 SpaceMatch UI – AI-Powered Property Search

This is the **frontend interface** for the SpaceMatch prototype, built using only a single HTML file with embedded CSS and JavaScript.

> Developed as part of the Founding Engineer technical challenge at **SpaceMatch**.

---

## 🚀 Live Demo

👉 [Launch the App](https://jatinchandani.github.io/space-match-ui)  

---

## 🔍 Features

- 💬 Chat-style property discovery
- 🎯 Natural language query support
- 🏷️ Real-time property cards with amenities
- 📊 Dynamic API status loading
- ⚡ Example queries for quick testing

---

## ⚙️ Stack & Deployment

| Layer     | Tech            |
|-----------|-----------------|
| Frontend  | HTML + CSS + JS |
| Hosting   | GitHub Pages    |
| Backend   | FastAPI (on Render) |
| API URL   | `https://space-match-api.onrender.com/chat` |

---

## 🧪 Test Queries

Try one of the following in the chat bar:

- `2 BHK apartment in Mumbai under ₹30000`
- `Pet-friendly flat with parking in Bangalore`
- `Furnished studio in Pune with gym`
- `Luxury 3 BHK in Delhi under ₹50000`

---

## 🛠 How to Run Locally

# 1. Clone the repo
git clone https://github.com/Jatinchandani/space-match-ui.git
cd space-match-ui

# 2. Open index.html in your browser
start index.html   # On Windows
open index.html    # On macOS

> 💡 No build tools or frameworks needed.

---

## 📡 Backend Dependency

Make sure your FastAPI backend is deployed and accessible at:

https://space-match-api.onrender.com/chat

This frontend expects the `/chat` endpoint to accept POST requests with:

{
  "message": "1 BHK in Pune under ₹20000",
  "max_results": 5
}

## 🙋‍♂️ Author

* **Jatin Chandani**
* GitHub: [@Jatinchandani](https://github.com/Jatinchandani)
* Email: [jatinchandani18@gmail.com](mailto:jatinchandani18@gmail.com)
