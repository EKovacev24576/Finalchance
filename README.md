# UMD Scheduler

Smart schedule builder for UMD student athletes and advisors.

## Features
- Scrape Testudo courses
- Avoid class conflicts with athletic availability
- Calendar + list view
- Save/retrieve schedule folders
- Export to PDF

## How to Run

### Backend
```bash
cd backend
cp .env.example .env
pip install -r requirements.txt
python db/init_db.py
flask run
```

### Frontend
```bash
cd frontend
cp .env.example .env
npm install
npm start
```
