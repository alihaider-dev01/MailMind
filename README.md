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

## 📂 Project Structure

