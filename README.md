# 🐾 Meowtes

**An anonymous public note posting application with AI integration for mood analysis and smart categorization.**

---

## 📜 Project Description

**Meowtes** is a platform for sharing anonymous notes, where users can express their thoughts freely. The application leverages AI to analyze moods and categorize topics smartly. Authentication is handled via Google OAuth, allowing users to manage notes privately or publicly. The app offers an engaging environment with features like reactions and categorization, enhancing user interactions and community engagement.

---

## 🚀 Features

| Feature                           | Description                                                                 |
|-----------------------------------|-----------------------------------------------------------------------------|
| **Authentication**                | Google OAuth only, supporting both authenticated and guest access.          |
| **Mood Analysis**                 | AI-driven mood analysis to detect and display the mood of notes.            |
| **Create Notes**                  | Users can create notes for public or private visibility.                    |
| **Update Notes**                  | Notes can be edited by their creators at any time.                          |
| **View Notes**                    | Supports note viewing for authenticated users and guests.                   |
| **Delete Notes**                  | Notes can be permanently removed by the creator.                            |
| **Private/Public Notes**          | Users can set notes as either public or private.                            |
| **Smart Categorization of Topics**| Automatic categorization of notes based on AI-analyzed topics.              |
| **Note Reactions**                | Express reactions on notes to engage with the community.                    |

---

## 🧰 Technology Stack

![alt text](https://github.com/genebit/meowtes/blob/master/assets/imgs/tech-stack.png?raw=true)

## 📂 Project Structure

```plaintext
meowtes
├── .git/                   # Git version control directory
├── app.api/                # Backend ASP.NET Core Web API repo.
├── app.web/                # Frontend React (Typescript) application repo.
├── assets/                 # Media files (e.g., dev logs, documentation images) excluded from Git.
└── .gitignore              # Git ignore configuration file.
```