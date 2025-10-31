# 🎶 MIXXTOPIA
> "엔믹스 팬덤을 위한 차세대 커뮤니티 & AI 창작 플랫폼"

## 🌐 소개
MIXXTOPIA는 엔믹스(NMIXX) 팬덤 ‘엔써’를 위한 커뮤니티 웹 사이트로,  
**커뮤니티 / 실시간 정보 / AI 기반 믹스팝 생성 / 글로벌 팬 지도 / 데이터 트렌드** 등의 기능을 제공합니다.

---

## 🧩 주요 기능
- 🧠 **AI Mix Studio** : AI가 엔믹스 스타일의 노래를 자동 생성
- 💬 **Fan Talk** : 엔써들이 실시간으로 대화 가능한 팬 커뮤니티
- 📅 **실시간 일정 자동 업데이트** : 공식 일정, 콘텐츠, SNS 연동
- 🎨 **팬아트, 투표, 퀴즈 카테고리**
- 🌍 **Global Fan Map** : 전 세계 엔써 응원 지도 시각화
- 📈 **NMIXX 트렌드 데이터 분석**

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
