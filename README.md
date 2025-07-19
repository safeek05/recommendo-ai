# Recommendo AI 🎯

Personalized content recommendation system using **Gemini AI**, **Gmail**, and **n8n automation**.

---

## 🚀 Overview

Recommendo AI is an intelligent automation system that delivers personalized content suggestions (like movies, books, and music) based on the user's **mood, genre, and type** — straight to their WhatsApp (or email). It integrates Gemini AI's power with n8n workflows to create an end-to-end smart recommendation pipeline.

---

## 📸 Demo

▶️ [Watch Demo Video](YOUR_VIDEO_LINK_HERE)

---

## 🛠️ Tech Stack

- 🧠 Gemini AI (Google AI)
- 📧 Gmail (as messaging output)
- 🧩 n8n (workflow automation)
- 📝 Forms (user input)
- 🧰 GitHub (code and workflow export)

---

## 🔁 How It Works

1. User fills out a form selecting:
   - Type: Movie / Book / Music
   - Mood: Happy, Sad, Chill, Motivated
   - Genre: e.g., Romance, Thriller, Sci-fi

2. The data goes to **n8n** via webhook.

3. n8n triggers **Gemini AI** to generate personalized content suggestions.

4. The response is formatted with:
   - IMDb Ratings
   - YouTube Trailer links
   - Spotify/Bookstore links (optional)

5. Final message is sent to the user via **Gmail**.

---

## 🧪 Example Output

Given the user is feeling happy and desires a Pop movie in English,
while avoiding past suggestions from "user@gmail.com," I
recommend the following:

**"Pitch Perfect"** - [Amazon Prime Video]
**Why:** This musical comedy celebrates female empowerment and the joy
of acapella, guaranteed to boost your mood with its catchy songs,
witty humor, and feel-good story.
**Link:** https://www.primevideo.com/detail/0JSJ75K97X46B4Q3Y8A51V0QW1/ref=atv_sr_def_c_unkc_1_1_1?sr=1-1&qid=1716911123


---

## 📂 Files Included

- `.n8n.json` — Exported automation workflow
- `README.md` — This file
- `.gitignore` — Best practices for Node & n8n projects
- `LICENSE` — MIT license

---

## ✅ Features

- Fully automated workflow
- Gemini AI-generated recommendations
- N8N handles logic and delivery
- Clean and readable message formatting

---

## 📌 Requirements

- n8n account (self-hosted or cloud)
- Google account (for Gmail & Forms)
- Gemini API access via Make.com or direct key

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Contributors

- **Safeek Ahamed** ([@safeek05](https://github.com/safeek05)) – Idea, automation, and integration

---

## 💡 Next Steps

- Add WhatsApp Cloud API support
- Add dynamic Spotify/Goodreads integrations
- Add trailers and IMDb ratings 

