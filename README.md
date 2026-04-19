# 🎵 Back-End-Development-Songs

## 🚀 Overview

This project is a **Flask-based Songs microservice** that provides REST APIs to manage song data including create, read, update, and delete operations.

---

## 🛠️ Tech Stack

* Python 🐍
* Flask 🌐
* REST API
* JSON

---

## 📂 Features

* ✅ Health check endpoint (`/health`)
* ✅ Get song (`GET /song`)
* ✅ Update song (`PUT /song/<id>`)
* ✅ Delete song (`DELETE /song/<id>`)

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
python app.py
```

---

## 📡 API Examples

### Health Check

```bash
curl http://localhost:5001/health
```

Response:

```json
{"status":"OK"}
```

---

### Get Song

```bash
curl http://localhost:5001/song
```

---

### Update Song

```bash
curl -X PUT http://localhost:5001/song/1 -H "Content-Type: application/json" -d '{"title":"Updated Song"}'
```

---

### Delete Song

```bash
curl -X DELETE http://localhost:5001/song/1
```

---

## 📌 Repository

🔗 https://github.com/patilmanas915/Back-End-Development-Songs

---

## 👨‍💻 Author

Manas Patil
