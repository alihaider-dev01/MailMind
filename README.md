# 📬 MailMind — Ask AI Anything, Get Answers in Your Inbox

> A simple and smart web tool that lets users ask any question and get AI-generated answers delivered directly to their email.

---

## 🌐 Live Demo

🔗 [View Live Site](https://alihaider-dev01.github.io/MailMind/)

---

## 📌 What This Project Does

- Users enter their **email** and **question** into a simple form
- The backend uses **Gemini AI (by Google)** to generate a smart answer
- The answer is automatically emailed to the user using **GmailApp**
- No login or signup needed

---

## 🚀 Features

- ✅ AI-Powered Replies
- ✅ Instant email delivery
- ✅ Google Apps Script backend
- ✅ Clean and responsive UI
- ✅ 100% free and client-side only

---

## 🧠 Background / How I Built It

I first created a **basic version using Google Forms**, with only two fields:  
- **Email**  
- **Question**

That form was connected to a **Google Sheet + Apps Script**, which:
- Took the question
- Called Gemini API
- Sent the response back to the user's Gmail

➡️ [Here is the original Google Form version](https://docs.google.com/forms/d/e/1FAIpQLSdOEQJNYlfounbOlJX-Su3MUC9nBAKpQnVZA-DiU0p9XVThmA/viewform?usp=dialog)

Later, I improved the UI by turning it into a clean **standalone web app**, hosted with **GitHub Pages**, without relying on Google Forms.

---

## 🧰 Tech Stack Used

| Part       | Tech |
|------------|------|
| Frontend   | HTML, CSS |
| Backend    | Google Apps Script |
| AI Engine  | Gemini (Google) |
| Email API  | GmailApp |
| Hosting    | GitHub Pages |
| No Server  | Everything runs serverlessly |

---

## 📈 Why It Matters

MailMind isn't just a fun AI tool — it's a practical solution with real-world use cases across industries.

💼 For Companies:
- Can be used as a **lightweight customer support system** — users ask questions, and smart AI-generated replies are sent directly to their inbox.
- Great for **small businesses or startups** that want an automated assistant without building a full backend or chatbot.
- Easily extendable for **FAQs, lead generation, feedback collection, or auto onboarding replies**.

🎓 For Students & Educators:
- Perfect for students who need **quick, AI-generated answers** on technical or academic topics.
- Teachers or institutions can integrate this with forms to answer **repeated student queries automatically**, saving time.

🧠 For AI Enthusiasts / Developers:
- Demonstrates how to integrate **AI + automation + email workflows** without a traditional server.
- Shows a full-stack mini AI product with clean UX, serverless architecture, and real utility.

🚀 Why It Stands Out:
- Works completely serverlessly — **no login, no backend hosting costs**
- Uses **Google Apps Script** smartly to handle everything from AI call to email delivery
- Fast, clean, and deployable anywhere with **zero infrastructure overhead**

MailMind proves that powerful AI services don’t need to be bulky or expensive — they just need to be smart, simple, and user-focused.


