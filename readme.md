# 프로젝트 클론
git clone https://github.com/your-username/your-repo.git

# 가상환경 생성 및 활성화
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 의존성 설치
pip install -r requirements.txt

# 데이터베이스 마이그레이션
python manage.py migrate

# 개발 서버 실행
python manage.py runserver
```

## 프로젝트 구조

```
realty/
├── manage.py
├── requirements.txt
├── settings.py
├── urls.py
├── apps/
│   ├── core/
│   ├── listings/
│   └── users/
├── frontend/
│   ├── src/
│   └── public/
└── data/
