# 🎵 Back-End-Development-Songs

## 🚀 Overview

This project implements a **Flask-based microservice** for managing songs.
It provides REST APIs to **retrieve, update, and delete song data**, along with a health check endpoint.

---

## 🛠️ Tech Stack

* Python 🐍
* Flask 🌐
* REST API architecture
* JSON

---

## ⚙️ Environment Setup

This project was initialized using the provided course template and configured successfully.

### 🧰 Setup Steps

1. Clone the repository:

```bash id="s1_clone"
git clone https://github.com/patilmanas915/Back-End-Development-Songs.git
cd Back-End-Development-Songs
```

2. Run the setup script:

```bash id="s2_setup"
bin/setup.sh
```

3. Activate the virtual environment:

```bash id="s3_venv"
source backend-songs-venv/bin/activate
```

---

### 🐍 Python Version

```text id="s4_python"
Python 3.9.x
```

---

### 📦 Virtual Environment

```text id="s5_env"
backend-songs-venv
```

✔ The setup script installs all required dependencies.
✔ The service runs successfully after environment setup.

---

## 📂 Features

* ✅ Health check endpoint (`/health`)
* ✅ Get song (`GET /song`)
* ✅ Update song (`PUT /song/<id>`)
* ✅ Delete song (`DELETE /song/<id>`)

---

## ▶️ How to Run

```bash id="s6_run"
pip install -r requirements.txt
python app.py
```

---

## 📡 API Examples

### Health Check

```bash id="s7_health"
curl http://localhost:5001/health
```

Response:

```json id="s8_health_out"
{"status":"OK"}
```

---

### Get Song

```bash id="s9_get"
curl http://localhost:5001/song
```

---

### Update Song

```bash id="s10_put"
curl -X PUT http://localhost:5001/song/1 \
-H "Content-Type: application/json" \
-d '{"title":"Updated Song"}'
```

---

### Delete Song

```bash id="s11_delete"
curl -X DELETE http://localhost:5001/song/1
```

---

## 📌 Repository

🔗 https://github.com/patilmanas915/Back-End-Development-Songs

---

## 👨‍💻 Author

**Manas Patil**
