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
2️⃣ Create & Activate Virtual Environment
python -m venv .venv
.\.venv\Scripts\activate

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Add Your API Key

Create a .env file in the project root:

GROQ_API_KEY=your_api_key_here


🔑 Get your API key from Groq Console

5️⃣ Run the App
streamlit run main.py


Your app will open at:

http://localhost:8501

💡 Example Workflow

Upload or paste your past LinkedIn posts.

The tool extracts topics and learns your writing style.

Select a topic, choose post length and tone.

Click Generate → get your AI-written post instantly.

🧑‍💻 Developer Info

👩‍💻 Swati Rajkumar Mishra
AI Agent Developer • Agentic AI Specialist • LangChain Expert

💼 Building real-world Agentic AI applications with LangChain, Groq, and Hugging Face

🎓 Pursuing BE in Computer Engineering, Mumbai University

🌐 Portfolio: swati-mishra-portfolio-glow.lovable.app

⚠️ License & Terms

This project is licensed under the MIT License.
Commercial use requires prior written consent from the author.
Attribution must be given in all copies or substantial portions of the software.

© 2025 Swati Rajkumar Mishra. All rights reserved.

🌟 Future Enhancements

Integrate LinkedIn API for auto-fetching posts.

Add voice-to-post generation using Whisper or Speech-to-Text.

Implement AI personality profiles for tone consistency.

⭐ If you like this project, don’t forget to star this repo and share it with your fellow creators!

Made with ❤️ by Swati
