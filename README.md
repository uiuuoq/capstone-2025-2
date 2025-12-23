<hr>

<h1 align="center">AI 기반 자연어 검색 · 분석 시스템</h1>

<p align="center">
  <b>자연어 질의를 구조화하여 데이터 검색 · 분석 · 인사이트를 제공하는 AI 시스템</b>
</p>

https://github.com/user-attachments/assets/e29b7518-4bbe-41e2-a7e6-c652d6f191d5

<hr>

## 🔍 Preview

<p align="center">
  <img src="https://github.com/user-attachments/assets/8564448e-8712-45be-b6c6-f3c77fed60d2"/>
</p>

---

## 🛠 Tech Stack

### Backend
- **Python 3.11**
- **FastAPI**
- **LangChain 0.3.x**
- **Anthropic Claude (Haiku / Sonnet / Opus)**
- **KURE Embedding**
- **PostgreSQL**

### Frontend
- **React**
- **HTML / CSS / JavaScript**
  
---

## 📦 Installation

```bash
git clone https://github.com/uiuuoq/capstone-2025-2.git
cd capsone-2025-2
pip install -r requirements.txt
```

## 🪄 Run

```
#프론트엔드 실행
npm run dev
```

## 🔐 Environment Variables

```
ANTHROPIC_API_KEY=sk-ant-api03-xxx
OPENAI_API_KEY=your_openai_api_key

DB_HOST=localhost
DB_PORT=your_port
DB_NAME=your_DB
DB_USER=postgres
DB_PASSWORD=your_password
```
## 📁 Frontend Structure

```
📂 Frontend
┣ 📜 .gitignore
┣ 📜 README.md
┃
┣ 📂 public
┃ ┣ 📜 index.html
┃ ┣ 📜 favicon.ico
┃ ┗ ...
┃
┗ 📂 src
  ┣ 📜 App.js
  ┣ 📜 index.js
  ┗ ...
```

## 🚀 Key Features

- **자연어 쿼리 파싱**: 사용자의 자연어 검색어를 구조화된 필터 조건으로 자동 변환
- **하이브리드 검색**: 필터 기반 검색과 벡터 유사도 검색의 조합
- **AI 분석 기반 보고서 제시**: 추출 데이터 관련 보고서 프로토타입 제공
- **결과 기반 공통 특성 추출**: 결과 기반 공통점 자동 분석 및 추출 
- **패널 시각화의 구조화**: 간소화된 패널 선 제시 후 구체적 패널 선택 제공

## 🤖 LLM Models

- **claude-3-5-haiku**: 데이터 기반 json 파일 문장 1차 가공
- **claude-sonnet-4-5**: 인사이트 생성, 문장 2차 가공
- **claude-3-opus**: 인사이트 기반 보고서 생성

## 📜 License
이 프로젝트는 한성대학교 기업연계 SW캡스톤디자인 수업에서 진행되었습니다.
