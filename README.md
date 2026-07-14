# 안녕하세요, 백엔드 개발자를 지향하는 jaebeombag638-cyber입니다 👋

데이터를 다루는 안정적인 서버와 API를 설계하고 구현하는 데 관심이 많습니다.
FastAPI 기반 백엔드부터 AI 모델을 활용한 서비스까지 폭넓게 프로젝트를 진행하고 있습니다.

## 🛠 Tech Stacks

**💻 Frontend**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**⚙️ Backend & Database**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-4B8BBE?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/🤗_Transformers-FFD21E?style=flat-square)

**🐳 DevOps & Cloud**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Red Hat](https://img.shields.io/badge/Red_Hat-EE0000?style=flat-square&logo=redhat&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

**🎨 Tools**

![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

## 📌 프로젝트

### [hyEOnjuNg0-0/buildback](https://github.com/hyEOnjuNg0-0/buildback) 🔒 Private
- Frontend: TypeScript, React, Vite, Tailwind CSS
- Backend: FastAPI, SQLAlchemy, Alembic, PostgreSQL(pgvector), Redis
- IBM watsonx.ai 기반 LLM/임베딩 검색, Google OAuth 소셜 로그인, 프로모션·알림 기능

### [korean-legal-ner](https://github.com/jaebeombag638-cyber/korean-legal-ner)
AI Hub 판결문 데이터로 KLUE-BERT를 파인튜닝한 한국어 법률 개인정보 익명화 NER
- HuggingFace Transformers + PyTorch 기반 모델 학습
- seqeval을 활용한 entity-level F1 평가

### [IBM-Redhat-6th-midterm-team-project](https://github.com/jaebeombag638-cyber/IBM-Redhat-6th-midterm-team-project)
모의주식 게임 — 팀 협업으로 진행한 프로젝트, FastAPI + SQLAlchemy AsyncSession 기반 매수/매도 트랜잭션 로직 담당
- 매수 시 현금 잔액, 매도 시 보유 수량을 사전 검증하고 조건 미충족 시 예외를 반환
- 매수/매도 시점의 평균 매입가(평단가)를 재계산하고, 평가손익·수익률을 함께 갱신
- 전량 매도 시 잔고 레코드를 삭제하고, 부분 매도 시 매입가를 비례 차감하는 방식으로 처리
- 거래 생성 → 잔고 갱신 → 유저 현금/자산 평가금액 갱신까지 이어지는 일련의 작업을 하나의 트랜잭션으로 묶어 처리하고, 예외 발생 시 rollback으로 데이터 정합성을 보장

## 📊 GitHub 통계

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=jaebeombag638-cyber&show_icons=true&theme=default)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=jaebeombag638-cyber&layout=compact)

## 📫 연락처

- Email: jaebeombag638@gmail.com
