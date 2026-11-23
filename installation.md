# Installation

StudyShare uses only open-source components and runs on any operating system.

## With Docker
```bash
git clone https://github.com/[team]/studyshare.git
cd studyshare
docker compose up
```
Open http://localhost:8000.

## Manual setup
1. Install Python 3.11+ and PostgreSQL.
2. `pip install -r requirements.txt`
3. Configure the database in `.env`.
4. `python manage.py runserver`

## Platform independence
No proprietary service is required. GitHub is used only for hosting; the repository can be moved to GitLab or a self-hosted Git server. All data can be exported as JSON/CSV.
