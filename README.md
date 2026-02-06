# ⚡ QuickChat

An AI-powered chat assistant built from scratch to learn and practice **React**, **Vite**, and **API integration**. QuickChat uses Google's **Gemini 2.5 Flash** model to deliver fast, conversational AI responses with a clean, responsive UI.

> 🚀 This is a personal learning project — not a clone. I built this to understand and apply core frontend concepts hands-on.

---

## ✨ Features

- **AI Chat** — Real-time conversational AI powered by the Gemini 2.5 Flash API
- **Conversation History** — Previous prompts are saved in the sidebar for quick access
- **Conversation Context** — The AI remembers the full conversation thread for contextual replies
- **Typing Effect** — Responses render word-by-word for a natural chat feel
- **Markdown Rendering** — Bold, italic, headings, and line breaks are formatted in responses
- **Responsive Design** — Mobile-friendly layout with a collapsible sidebar and overlay menu
- **New Chat** — Start a fresh conversation with one click

---

## 🛠️ Tech Stack

| Layer        | Technology                                                    |
|------------- |---------------------------------------------------------------|
| Frontend     | React 19, JSX                                                 |
| Build Tool   | Vite 7                                                        |
| AI Model     | Google Gemini 2.5 Flash (`@google/genai`)                     |
| State Mgmt   | React Context API + `useState`                                |
| Linting      | ESLint 9                                                      |

---

## 📁 Project Structure

```
QuickChat/
├── public/
├── src/
│   ├── assets/          # Icons and static images
│   ├── components/
│   │   ├── Main/        # Main chat area (input, cards, results)
│   │   └── Sidebar/     # Collapsible sidebar with chat history
│   ├── config/
│   │   └── gemini.js    # Gemini API client & chat logic
│   ├── context/
│   │   └── context.jsx  # Global state via React Context
│   ├── App.jsx          # Root component
│   ├── main.jsx         # Entry point
│   └── index.css        # Global styles
├── index.html
├── vite.config.js
└── package.json
```

---

## 🚀 Getting Started

### Prerequisites

- **Node.js** (v18+)
- A **Google Gemini API key** — [Get one here](https://aistudio.google.com/app/apikey)

### Setup

1. **Clone the repo**
   ```bash
   git clone https://github.com/suryapratapsingh/QuickChat.git
   cd QuickChat
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Create a `.env` file** in the project root
   ```
   VITE_GEMINI_API_KEY=your_api_key_here
   ```

4. **Start the dev server**
   ```bash
   npm run dev
   ```

5. Open **http://localhost:5173** in your browser.

---

## 📸 Screenshots

> _Add screenshots of the app here once ready!_

---

## 🧠 What I Learned

- Setting up a React project from scratch with **Vite**
- Managing global state with **React Context API** across components
- Integrating a third-party AI API (**Google Gemini**) and handling async requests
- Building multi-turn conversations by maintaining **conversation history** and passing it as context to the API
- Creating a **responsive sidebar** with mobile overlay support
- Implementing a **word-by-word typing animation** using `setTimeout`
- Parsing **Markdown to HTML** with regex for rich text rendering
- Handling **environment variables** securely with `import.meta.env`
- Structuring a React project with clean **component separation** (Sidebar, Main, Context, Config)

---

## 🔮 Future Improvements

- [ ] Persist chat history with `localStorage` or a database
- [ ] Add dark/light theme toggle
- [ ] Support image uploads via the gallery icon
- [ ] Voice input using the Web Speech API
- [ ] Stream responses instead of waiting for the full reply
- [ ] Deploy to Vercel / Netlify

---

## 📄 License

This project is open source and available for learning purposes.

---

<p align="center">Built with ☕ and curiosity by <b>Surya Pratap Singh</b></p>
