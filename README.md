# 🧠 LinkedIn Post Generator (GenAI Project)

> An intelligent AI-powered tool that learns your unique **LinkedIn writing style** and helps you craft new posts like a pro influencer.

Built with 💙 using **Streamlit**, **LangChain**, and **Groq API** — this project leverages few-shot learning and prompt engineering to generate authentic, human-like LinkedIn posts that sound *just like you*.

---

## ✨ Features

✅ **Style Analysis** – Analyzes your past LinkedIn posts to understand tone, structure, and content style.  
✅ **Smart Topic Detection** – Automatically identifies trending or recurring topics in your posts.  
✅ **Customizable Generation** – Choose **topic**, **length**, and **language** for your new post.  
✅ **Few-Shot Learning** – Uses your old posts to fine-tune the LLM’s response and maintain consistency.  
✅ **Clean Streamlit UI** – Simple, interactive interface for influencers, creators, and professionals.

---

## 🧩 Tech Stack

| Layer | Technologies Used |
|:------|:------------------|
| 💻 Frontend | Streamlit |
| 🧠 LLM Framework | LangChain |
| ⚙️ Backend Model | Groq API |
| 🧾 Environment Handling | Python-dotenv |
| 📊 Data Processing | Pandas |
| 🧮 Language | Python 3.10 |

---

## 🏗️ Architecture Overview

<img src="resources/architecture.jpg" width="700"/>

1. **Stage 1 – Post Analysis**  
   The system collects past LinkedIn posts, extracts attributes like *topic*, *language*, and *length* using NLP.

2. **Stage 2 – Post Generation**  
   Uses the extracted attributes + few-shot learning from previous posts to guide the LLM for realistic post generation.

---

## 🖼️ Screenshots

Here’s a preview of the UI and the app in action:

<img width="1920" height="1200" alt="Screenshot (16)" src="https://github.com/user-attachments/assets/0d00993a-400f-4c09-acd8-d985243bf23a" />
<img width="1920" height="1200" alt="Screenshot (17)" src="https://github.com/user-attachments/assets/49628456-c59c-4c75-877c-3730664e07a1" />
  

*The interactive Streamlit UI allows you to select topic, length, and language, then generate AI posts in your unique style.*

---

## ⚙️ Setup & Installation

### 1️⃣ Clone this repository
```bash
git clone https://github.com/<your-username>/project-genai-post-generator.git
cd project-genai-post-generator
