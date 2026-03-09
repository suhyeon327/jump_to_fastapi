# FastAPI Study Project (Jump to FastAPI)
FastAPI 공부를 위해 Jump to FastAPI 책을 따라 만든 프로젝트입니다.

Backend는 FastAPI, Frontend는 Svelte를 사용합니다.

## Tech Stack
### Backend
- Python 3.10
- FastAPI
- SQLAlchemy
- Uvicorn
- Alembic

### Frontend
- Svelte
- Node.js
- Vite

## 프로젝트 구조
```
jump_to_fastapi
│
├─ frontend
│  ├─ src
│  └─ public
│
├─ migrations
│
├─ main.py
├─ database.py
├─ models.py
├─ requirements.txt
├─ README.md
```

## Backend 실행 방법 (FastAPI)
```
# 가상환경 생성
py -3.10 -m venv jump_to_fastapi

# 가상환경 실행(Windows)
jump_to_fastapi\Scripts\activate

# 패키지 설치
pip install -r requirements.txt

# 서버 실행
uvicorn main:app --reload
```

## API Documentation
FastAPI에서 제공하는 Swagger UI
```
`http://127.0.0.1:8000/docs`
```

## Frontend 실행 방법(Svelte)
```
# frontend 폴더로 이동
cd frontend

# 패키지 설치
npm install

# 개발 서버 실행
npm run dev
```

## Reference
- https://wikidocs.net/book/8531
- https://github.com/pahkey/fastapi-book
