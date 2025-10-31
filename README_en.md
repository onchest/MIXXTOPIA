# 🎶 MIXXTOPIA

> "The Next-Generation Community & AI Creation Platform for NMIXX Fandom"

## 🌐 Introduction
MIXXTOPIA is an integrated platform designed for NMIXX's fandom, 'NSWER.' It provides essential features like **Community / Real-time Information / AI-powered Mixx Pop Generation / Global Fan Map / Data Trends**.

---

## 🧩 Key Features
* 🧠 **AI Mix Studio**: AI automatically generates songs in the NMIXX style.
* 💬 **Fan Talk**: A real-time community chat for NSWERS.
* 📅 **Real-time Schedule Auto-Update**: Integrates official schedules, content releases, and social media feeds.
* 🎨 **Fan Art, Voting, & Quiz Categories**.
* 🌍 **Global Fan Map**: Visualizes the support map of NSWERS worldwide.
* 📈 **NMIXX Trend Data Analysis**.

---

## 🏗️ Tech Stack
| Category | Technology |
| :--- | :--- |
| Frontend | React + Vite, TypeScript, TailwindCSS |
| Backend | FastAPI (or Express) |
| Database | PostgreSQL |
| AI | Python + HuggingFace + PyTorch |
| Infra | Docker, GitHub Actions, AWS EC2/S3 |
| Etc | OpenAI API, YouTube API, Spotify API |

---

## 📊 System Architecture
![Architecture](docs/architecture.png)

---

## ⚙️ Installation & Running
```bash
git clone https://github.com/yourname/mixxtopia.git
cd mixxtopia

# Backend
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

# Frontend
cd ../frontend
npm install
npm run dev