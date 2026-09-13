# To-Do List (Flask + SQLite + Docker)

Simple real-life To-Do List web app. Task add, complete (toggle), delete kora jay. SQLite dieie data save hoy.

## Project structure
```
myproject/
├── app.py
├── requirements.txt
├── Dockerfile
├── docker-compose.yml
├── .gitignore
├── templates/
│   └── index.html
└── static/
    └── style.css
```

## Run (Docker Compose)
```bash
docker compose up --build
```
Browser: http://localhost:5000

Stop:
```bash
docker compose down
```

## Run (plain Docker)
```bash
docker build -t todo-app:latest .
docker run -d -p 5000:5000 --name todo-app todo-app:latest
```
