## Quiz Generator Using AI

A fun, interactive quiz generator that uses **OpenAI’s GPT API** to instantly create multiple-choice quizzes based on any topic, difficulty, and language you choose.

This project blends AI, web design, and playful UX — complete with animations, music, and cheeky score screens.

---

### Features

* Choose your **language, topic, difficulty**, and number of questions
* Live **loading screen** with random coding facts while the quiz generates
* Clean **multiple-choice interface** with progress tracking
* Dynamic **results page** with custom messages, confetti, and gifs based on your score
* **Built-in audio player** with a set of upbeat tracks to keep it engaging

---

### Tech Stack

* **Next.js 13.4** (App Router)
* **Tailwind CSS**
* **OpenAI GPT API**
* **Framer Motion** (animations)
* **React Confetti**
* **React Loader Spinner**
* **React Simple Typewriter**
* **React Icons**

---

### How It Works

1. The user enters quiz settings (topic, difficulty, etc.).
2. A **custom GPT prompt** is generated and sent to the API.
3. The AI returns a structured JSON of questions, answers, and explanations.
4. The app displays a fully functional quiz with smooth transitions and feedback.

---

### Getting Started

```bash
git clone https://github.com/Meghanath1435/Quiz-Generator-Using-AI.git
cd Quiz-Generator-Using-AI
npm install
npm run dev
```

Create a `.env.local` file with your OpenAI key:

```bash
OPENAI_API_KEY=your_api_key_here
```

Then visit:

```
http://localhost:3000
```

---

###  Why I Built This

I wanted to combine AI’s creative generation power with an engaging, gamified experience. It’s part of my learning journey with **Next.js**, **APIs**, and **frontend interaction design**.

