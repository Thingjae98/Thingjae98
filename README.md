# 안녕하세요, 저는 원명재입니다 👋

> **"기획부터 배포까지, 실제로 쓰이는 것을 만드는 개발자"**

현재 운영 중인 서비스 2개를 포함해 총 7개의 프로젝트를 직접 기획·개발·배포한 풀스택 개발자입니다.  
React/Next.js 프론트엔드와 FastAPI 백엔드를 모두 다루며, AI API 연동과 데이터 분석 경험을 보유하고 있습니다.

---

## 🛠 기술 스택

**Frontend**  
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend & Data**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**Database & Infra**  
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

**AI 연동**  
![Google Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-000000?style=flat-square&logo=openai&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-FF6B35?style=flat-square&logo=data:image/png;base64,&logoColor=white)

---

## 🚀 주요 프로젝트

### 🏫 Tommy App — 학생 관리 및 리포트 자동화 시스템
> **실제 코딩학원에서 매일 운영 중인 서비스**

코딩학원 선생님들이 학생 출결, 진도, 학부모 상담을 효율적으로 관리할 수 있도록 직접 기획·개발한 웹 앱입니다.

- **실사용 중** — 현재 여러 선생님이 매일 사용하는 프로덕션 서비스
- **AI 3종 연동** — Gemini / OpenRouter(DeepSeek) / Groq 상황별 선택적 호출
- **4단계 권한 시스템** — superadmin / admin / pay_editor / teacher RBAC 구현
- **실시간 DB 동기화** — Supabase 기반 다중 사용자 동시 접속 충돌 방어 (선택적 Merge 로직)
- **v1→v3 트러블슈팅** — 504 타임아웃, 데이터 유실 등 실제 운영 문제를 직접 해결하며 버전업

`React 18` `Vite` `Supabase` `Gemini API` `Groq API` `SheetJS`

---

### 📈 CalculateChart — 한국 주식 기술적 분석기
> **배포 중: [calculatechart.vercel.app](https://calculatechart.vercel.app)**

KRX 전 종목을 기술적 분석으로 자동 점수화하고 AI 주가 예측까지 제공하는 풀스택 주식 분석 웹 앱입니다.

- **프론트/백엔드 완전 분리** — React 19 + TypeScript(Vercel) / FastAPI + Python(Render)
- **기술적 분석 직접 구현** — RSI, MACD, 볼린저 밴드, 이동평균 정배열 등 7개 지표 자체 구현
- **KRX 전 종목 스코어링** — pykrx 기반 실시간 데이터 수집 후 Top 10 추천
- **AI 주가 예측** — 단기 모멘텀 + 장기 SMA 평균 회귀 기반 미래 캔들 생성

`FastAPI` `Python` `React 19` `TypeScript` `pandas` `numpy` `scipy` `pykrx`

---

### 📚 KidCanvas (bookmaker) — 아이 그림 작품집 제작 에디터
> **외부 API 2종 연동 풀스택 웹 앱**

부모가 아이의 그림을 업로드하면 AI가 미술관 큐레이터 스타일의 해설을 자동 생성하고, 하드커버 포토북으로 제작·배송하는 서비스입니다.

- **Gemini Vision 연동** — 이미지 분석 기반 26페이지 작품 해설 일괄 자동 생성
- **SweetBook API 연동** — Idempotency-Key, 지수 백오프 재시도, HMAC-SHA256 Webhook 검증
- **3-Layer 방어 아키텍처** — 유령 템플릿 차단, 카테고리 스코프 검증, 전송 게이트키핑

`Next.js 14` `React` `Tailwind CSS` `Gemini Vision API` `SweetBook API` `sharp`

---

## 📊 데이터 분석 프로젝트

| 프로젝트 | 주제 | 기술 |
|---|---|---|
| [covid_data](https://github.com/Thingjae98/covid_data) | COVID-19 데이터 분석 및 시각화 | Python, Pandas, Matplotlib |
| [ev_analysis](https://github.com/Thingjae98/ev_analysis) | 전기차 시장 데이터 분석 | Python, Pandas, Seaborn |
| [bike_data](https://github.com/Thingjae98/bike_data) | 자전거 이용 패턴 분석 | Python, Jupyter Notebook |

---

## 📬 연락처

- **GitHub**: [github.com/Thingjae98](https://github.com/Thingjae98)
- **Email**: *mj98531@gmail.com*
- **Blog/Notion**: *(선택 사항)*

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Thingjae98&show_icons=true&theme=default&hide_border=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Thingjae98&layout=compact&theme=default&hide_border=true" height="150"/>
</p>
