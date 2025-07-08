🎵 Music Streaming Web App
A full-stack music streaming web application built using Django.  
Users can register, log in, view and play uploaded songs, and search songs in real time using JavaScript.

This project was completed as part of a certified internship under EY GDS & AICTE.

---

## 🌟 Features

- User Registration & Login (Django Auth)
- Upload and Play Songs (MP3)
- Styled UI with Bootstrap
- JavaScript-powered Live Song Search
- REST API for song listing (`/api/songs/`)
- Admin Panel to manage songs
- Fully functional local setup

---

## 🛠️ Tech Stack

| Layer         | Technology                       |
|---------------|----------------------------------|
| Language      | Python 3                         |
| Backend       | Django                           |
| Frontend      | HTML, CSS, Bootstrap             |
| JavaScript    | Vanilla JS (for live search)     |
| REST API      | Django REST Framework (DRF)      |
| Database      | SQLite (default)                 |

---

## 🔌 REST API Example 

**Endpoint:**  
`http://127.0.0.1:8000/api/songs/`

**Response:**
```json
[
  {
    "id": 1,
    "title": "Sample Song",
    "file": "/media/songs/sample.mp3"
  }
]

]![API_JSON_Screenshot](https://github.com/user-attachments/assets/0e3ac820-e400-4cb9-b8d2-f6e8ed991188)
![Homepage_Screenshot](https://github.com/user-attachments/assets/84b94ed3-f1c4-430f-b5a3-2905a06402c8)
![Loginpage_Screenshot](https://github.com/user-attachments/assets/2c0ecffb-2385-4668-8c46-ac67d436bdbd)
