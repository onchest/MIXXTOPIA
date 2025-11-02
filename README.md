# *MIXXTOPIA*
> The web service that provide community & creative AI for NMIXX fandom

## Introduction
**MIXXTOPIA** is community web site for NMIXX's fandom 'NSWER',
it provides functions such as **community / real-time information / AI-based MIXX POP creation / data trend**

---

## 🧩 주요 기능
- 🧠 **MIXX Studio** : AI automatically generates songs in the NMIXX style
- 💬 **Fan Talk** : Chatting service for NSWERS
- 📅 **Real-time Schedule Auto-Update** : Integrates official schedules, content releases, and social media feeds.
- 🎨 **Fan Art, Gallery, & Quiz Categories**
- 🌍 **Fan Map** : Visualizes the support map of NSWERS(Only KOREA or Worldwide)
- 📈 **NMIXX Trend Data Analysis**
- 🎶 **

---

## 🏗️ 기술 스택
| 분류 | 기술 |
|------|------|
| Frontend | React + Vite, TypeScript, TailwindCSS |
| Backend | FastAPI (or Express) |
| Database | PostgreSQL |
| AI | Python + HuggingFace + PyTorch |
| Infra | Docker, GitHub Actions, AWS EC2/S3 |
| Etc | OpenAI API, YouTube API, Spotify API |

---

## 📊 시스템 아키텍처
![Architecture](docs/architecture.png)

---

## ⚙️ 설치 및 실행
```bash
git clone https://github.com/yourname/mixxtopia.git
cd mixxtopia

# 백엔드
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

# 프론트엔드
cd ../frontend
npm install
npm run dev
