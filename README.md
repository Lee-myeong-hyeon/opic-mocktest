# 🗣️ OPIc Mock Test

React 기반의 **OPIc 모의고사 웹 플랫폼**입니다.  
사용자의 배경 정보를 바탕으로 맞춤형 질문을 제공하고, 실제 시험처럼 녹음 → 제출 → 피드백의 흐름을 구성합니다.  
교육용 프로젝트로 기획되었으며, 확장성과 유지보수를 고려한 구조를 채택했습니다.

---

## 📁 프로젝트 폴더 구조

opic-mocktest/  
├── node_modules/ # 설치된 모든 외부 패키지 (Git에 포함되지 않음)  
├── public/ # 정적 파일 (HTML, favicon 등)  
│ └── index.html # React 앱이 주입되는 HTML 템플릿  
├── src/ # 소스 코드 디렉토리  
│ ├── App.jsx # 라우팅 및 레이아웃 정의  
│ ├── main.jsx # 앱 엔트리포인트 (Vite에서 사용됨)  
│ ├── apiClient.js # Axios 또는 fetch 기반 API 통신 모듈  
│ ├── routes.js # React Router 라우팅 정의  
│ ├── useAuth.js # 사용자 인증 관련 커스텀 훅  
│ ├── formatDate.js # 날짜 포맷 유틸 함수  
│ ├── sampleQuestions.json # OPIc 질문 샘플 데이터  
│ ├── Header.jsx # 상단 공통 헤더 컴포넌트  
│ └── Home.jsx # 홈 화면 컴포넌트  
├── .gitignore # Git에 포함하지 않을 파일/폴더 지정  
├── package.json # 프로젝트 메타 정보 및 의존성 목록  
├── package-lock.json # 의존성 정확한 버전 고정용 파일  
├── README.md # 프로젝트 설명 문서  

yaml  
Copy  
Edit  

---

## 🚀 실행 방법 (로컬 개발)

1. 저장소 클론  

```bash
git clone https://github.com/Lee-myeong-hyeon/opic-mocktest.git  
cd opic-mocktest  
의존성 설치  

bash  
Copy  
Edit  
npm install  
개발 서버 실행  

bash  
Copy  
Edit  
npm run dev  
브라우저에서 확인  
http://localhost:5173 로 접속

🧩 주요 기능  
OPIc 설문 기반 맞춤형 질문 시스템

React Router를 활용한 화면 구성

사용자 응답 녹음 및 제출 UI 설계 (녹음 기능은 추후 추가 예정)

질문 데이터(JSON) 기반 관리

향후 API 연동과 사용자 인증 구조까지 확장 가능

🛠 사용 기술  
React 18: 컴포넌트 기반 UI 구축

Vite: 빠른 번들링과 핫 리로딩 제공

JavaScript (ES6+): 주요 로직 처리

JSON: 데이터 관리 포맷

(예정) Web Audio API, Firebase

🗓️ 향후 계획  
🎤 녹음 기능 추가 (Web Audio API)

🧠 AI 기반 피드백 기능 (감정 분석, 정확도 평가 등)

💾 Firebase 연동 (데이터 저장 및 인증 기능)

📊 통계 페이지 (응답 히스토리 시각화)

👤 개발자 정보  
이명현 (Lee Myeong-hyeon)  
부산대학교 생명융합공학과 / 데이터사이언스 전공  
📧 Email: [본인의 이메일 입력]  
🔗 GitHub: https://github.com/Lee-myeong-hyeon  

이 프로젝트는 비영리 목적의 교육용 플랫폼입니다.
질문 및 협업 제안은 언제든지 환영합니다!

