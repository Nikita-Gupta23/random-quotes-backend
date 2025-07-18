 # 🧠 Random Quotes Machine — Backend API(Django REST API)

This is the **Django REST API** backend for the Random Quotes Machine project. It serves motivational quotes to a React frontend via a simple REST endpoint.

 🌐 Live API: [random-quotes-backend2.onrender.com/api/quotes/random/](https://random-quotes-backend2.onrender.com/api/quotes/random/)

## ⚙️ Tech Stack

- 🐍 Django
- 🔌 Django REST Framework (DRF)
- 🔧 Gunicorn (for production)
- 🌍 Hosted on [Render](https://render.com)

---

#### 🚀 API Overview

| Method | Route                            | Description            |
|--------|----------------------------------|------------------------|
| GET    | `/api/quotes/random/`            | Returns a random quote |

#### 🧾 Example Response

```json
{
  "id": 5,
  "text": "The only way to do great work is to love what you do.",
  "author": "Steve Jobs"
}
```
#### 🛠️ Setup Instructions

- git clone https://github.com/Nikita-Gupta23/random-quotes-backend.git
- cd random-quotes-backend

#### Create and activate virtual environment
- python -m venv venv
- venv\Scripts\activate #On MAC:source venv/bin/activate 

#### Install dependencies
- pip install -r requirements.txt

#### Migrate and run
- python manage.py makemigrations
- python manage.py migrate
- python manage.py runserver

#### ⚠️ CORS Configuration
- Make sure to allow your frontend domain in settings.py:
- CORS_ALLOWED_ORIGINS = [
    "https://random-quotes-frontend.vercel.app",
    "http://localhost:3000"
]
---
### 🧠 Author
Made with 💜 by Nikita Gupta


