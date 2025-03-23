# Chat App (FastAPI + Vanilla JS)

이 프로젝트는 **FastAPI**와 **Vanilla JavaScript (HTML, CSS, JS)** 를 사용하여 만든 간단한 채팅 웹 애플리케이션입니다.

## 📌 기능
- **회원가입 및 로그인** (JWT 인증 사용)
- **연결(Contact) 추가 기능** (요청 및 수락)
- **실시간 채팅** (WebSocket 기반)

## 🛠 기술 스택
- **백엔드**: FastAPI, SQLAlchemy, Pydantic, WebSockets
- **프론트엔드**: HTML, CSS, JavaScript (Vanilla JS)
- **데이터베이스**: SQLite (개발 환경)

## 🚀 실행 방법
### 1. 백엔드 실행
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

### 2. 프론트엔드 실행
그냥 `index.html` 파일을 브라우저에서 열면 됩니다.

## 📌 API 문서
FastAPI의 자동 문서를 사용하여 API 엔드포인트를 확인할 수 있습니다:
- **Swagger UI**: `http://localhost:8000/docs`
- **Redoc**: `http://localhost:8000/redoc`
