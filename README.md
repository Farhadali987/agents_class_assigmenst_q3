# 🎓 Career Mentor Agent

> An AI-powered multi-agent system that helps you plan your career, improve skills, and discover relevant job opportunities — built with the OpenAI Agents SDK and Streamlit.

---

## 🚀 Features

- 🤖 **Career Guidance** — Personalized advice based on your interests and goals
- 🧠 **Skill Gap Analysis** — Detect what skills you need to reach your goals
- 💼 **Job Recommendations** — Find relevant job opportunities using live tools
- 🌐 **Multi-Agent System** — Uses `CareerAgent`, `SkillAgent`, and `JobAgent` to collaborate

---

## 🛠️ Tech Stack

- 🧠 OpenAI Agents SDK
- 🌐 Streamlit (for UI)
- 🐍 Python 3.11+
- 🔌 Custom Tooling (e.g., job search APIs, skill matchers)

---

## 🧑‍💼 Agents Overview

| Agent Name     | Role                                                              |
|----------------|-------------------------------------------------------------------|
| `CareerAgent`  | Handles overall career planning and communicates with other agents|
| `SkillAgent`   | Analyzes current skills and recommends learning resources         |
| `JobAgent`     | Searches for jobs based on user input and profile                 |

---

## 💡 Sample Input

```txt
I am a fresh computer science graduate. Suggest me a career path and what skills to learn.




✅ Output
"Based on your background, here are a few career paths you can pursue: Frontend Developer, Data Analyst, AI Engineer... To get started with AI, consider learning Python, NumPy, Pandas, and basic ML concepts..."

📦 Setup Instructions
bash
Copy
Edit
git clone https://github.com/YourUsername/CareerMentorAgent.git
cd CareerMentorAgent
pip install -r requirements.txt
uv run main.py
📁 Folder Structure
css
Copy
Edit
CareerMentorAgent/
│
├── agents/
│   ├── career_agent.py
│   ├── skill_agent.py
│   ├── job_agent.py
│
├── tools/
│   ├── skill_tool.py
│   ├── job_search_tool.py
│
├── main.py
└── README.md
🙋‍♂️ Author
Created with ❤️ by Farhad Ali Laghari
📞 0324-8834244
🌐 https://github.com/Farhadali98

📜 License
This project is licensed under the MIT License.
