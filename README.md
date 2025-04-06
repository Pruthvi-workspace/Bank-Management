
## 🔥 Project Description

This is a feature-rich Online Banking System built using the Django Web Framework. It simulates real-world banking operations with support for account creation, transactions, interest calculation, transaction limits, and a sleek UI styled with Tailwind CSS. Celery is used for scheduling monthly interest calculations efficiently.

---

## 🚀 Features

- Create & manage bank accounts (Savings & Current)
- Deposit and Withdraw funds
- Transaction report with date-range filtering
- Balance tracking after each transaction
- Scheduled monthly interest calculation using Celery
- Redis-backed asynchronous task management
- Min/Max transaction restrictions
- Modern and responsive UI using Tailwind CSS

---

## 🧰 Tech Stack & Tools

<p align="left"> 
  <a href="https://www.djangoproject.com/" target="_blank"> <img src="https://img.icons8.com/color/48/000000/django.png" width="40"/> </a>
  <a href="https://www.python.org/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40"/> </a>
  <a href="https://redis.io/" target="_blank"> <img src="https://img.icons8.com/ios-filled/50/redis.png" width="40"/> </a>
  <a href="https://tailwindcss.com/" target="_blank"> <img src="https://img.icons8.com/color/48/000000/tailwindcss.png" width="40"/> </a>
  <a href="https://www.mysql.com/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" width="40"/> </a>
  <a href="https://www.postgresql.org/" target="_blank"> <img src="https://img.icons8.com/color/48/000000/postgreesql.png" width="40"/> </a>
</p>

---

## 📦 Requirements

```
Python >= 3.7  
Redis Server  
celery==4.4.7  
Django==3.2  
django-celery-beat==2.0.0  
python-dateutil==2.8.1  
redis==3.5.3  
```

---

## 🛠️ Project Setup Instructions

### 🔄 Install Redis Server

Follow the [Redis Quick Start](https://redis.io/topics/quickstart)

```bash
redis-server
```

### 💻 Project Installation Steps

```bash
# Clone the repository
git clone https://github.com/pruthviraj416/banking-system.git
cd banking-system

# Create & activate virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Create admin user
python manage.py createsuperuser

# Run development server
python manage.py runserver
```

### ⚙️ Running Celery Workers

Open a separate terminal:

```bash
# Start Celery worker
celery -A banking_system worker -l info

# Start Celery beat scheduler
celery -A banking_system beat -l info
```

---

## 📸 Screenshots

<img src="https://i.imgur.com/FvgmEJL.png" width="100%"/>
<br/>
<img src="https://i.imgur.com/aWzj44Y.png" width="100%"/>

---

## 📁 Project Structure

```
banking-system/
│
├── banking_system/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── accounts/
│   ├── migrations/
│   ├── models.py
│   ├── views.py
│   ├── tasks.py
│   └── urls.py
│
├── static/
│   └── tailwind/
│
├── templates/
│   └── banking/
│
├── manage.py
└── requirements.txt
```

---


---

## 👤 Author Info

<h2 align="center">Hi 👋, I'm Pruthviraj Shinde</h2>
<h4 align="center">🚀 A passionate developer building tools that matter.</h4>

- 🔭 I’m currently working on: <strong>AI-powered Complaint Management System</strong>  
- 🌱 I’m currently learning: <strong>React, Advanced JS, and Backend Scalability</strong>  
- 📫 Reach me at: <strong>psshinde418@gmail.com</strong>

---

## 🌐 Connect with Me

<p align="left">
  <a href="mailto:psshinde418@gmail.com"><img src="https://img.icons8.com/fluency/48/gmail.png" width="40"/></a>
  <a href="https://github.com/pruthviraj416"><img src="https://img.icons8.com/ios-glyphs/60/github.png" width="40"/></a>
</p>

---

## 🛠 Languages & Tools

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" width="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" width="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" width="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" width="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" width="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original-wordmark.svg" width="40"/>
</p>
```

