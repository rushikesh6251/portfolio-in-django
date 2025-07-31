# 👨‍💻 Rushikesh – Django Tailwind Blog | Developer Portfolio & Blog  

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

## 🚀 Introduction  
Hi, I’m **Rushikesh**, an aspiring **Cloud & DevOps Engineer** passionate about building scalable applications.  

This project – **Django Tailwind Blog** – is my **developer portfolio and blogging platform**, designed with **Django** and **Tailwind CSS**. It features a modern, responsive layout and includes:  
- 💼 Portfolio showcase  
- ✍️ Developer blog  
- 📂 Categories & projects  
- 🛠️ Admin dashboard  
- ❌ Custom error pages  

![Preview](https://user-images.githubusercontent.com/106135144/227858936-d4cbcb44-9ff4-4729-b0f0-6ede931b99e0.png)

---

## 📑 Table of Contents  
- [Introduction](#-introduction)  
- [Installation](#-installation)  
- [Technologies Used](#-technologies-used)  
- [Features](#-features)  
- [Pages](#-pages)  
- [Screenshots](#-website-screenshots)  
- [Deployment](#-deployment)  
- [About Me](#-about-me)

---

## ⚙️ Installation  

\`\`\`bash
# Clone repository
git clone https://github.com/rushikesh6251/portfolio-in-django.git

# Navigate to project
cd django-tailwind-blog

# Create virtual environment
python -m venv env
source env/bin/activate  # Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Install Tailwind
pip install django-tailwind

# Add 'tailwind' in settings.py
python manage.py tailwind init

# Migrate database
python manage.py migrate

# Run server
python manage.py runserver
\`\`\`

---

## 🛠️ Technologies Used  

- **Frontend:** HTML, CSS, JavaScript, Tailwind CSS  
- **Backend:** Python, Django  
- **Database:** SQLite / PostgreSQL  
- **Key Modules:** Django, django-tailwind, whitenoise, psycopg2, django-tinymce  

---

## 🌟 Features  

✔️ Modern responsive design  
✔️ Admin panel for blog & portfolio management  
✔️ Contact form integration  
✔️ SEO-friendly URLs  
✔️ Custom 404 pages  

---

## 📄 Pages  

- **Home** → Landing page  
- **About** → Personal profile  
- **Contact** → Direct message form  
- **Blog** → Post listings  
- **Blog Post** → Individual articles  
- **Projects** → Portfolio showcase  
- **Categories** → Post filters  
- **404 Pages** → Custom error handling  

---

## 🖼️ Website Screenshots  

| About | Contact | Blog | Projects |
|-------|---------|------|----------|
| ![about](https://user-images.githubusercontent.com/106135144/218676693-b433a723-0569-4a5a-91e2-d2330659233d.png) | ![contact](https://user-images.githubusercontent.com/106135144/218676709-3924f790-32db-46f3-a1b5-bf1907506751.png) | ![blog](https://user-images.githubusercontent.com/106135144/218676733-bc2313e9-9721-4f4b-9fd8-ab7cfa939221.png) | ![projects](https://user-images.githubusercontent.com/106135144/218676756-3770e70e-149b-48ae-af50-44d1ee43aed6.png) |

### 🔑 Admin Panel  
![admin](https://user-images.githubusercontent.com/106135144/218730427-1aad64b4-65ff-44e4-babf-840d200919fa.png)

---

## ☁️ Deployment  

1. Set up a Python-compatible server (Heroku, AWS, VPS)  
2. Clone & install dependencies  
3. Configure PostgreSQL in \`settings.py\`  
4. Collect static files:  
\`\`\`bash
python manage.py collectstatic
\`\`\`  
5. Run with **Gunicorn/uWSGI** for production  

---

## 👨‍🎓 About Me  

- 🎓 MCA Student | AWS Certified Cloud Practitioner  
- ☁️ Cloud & DevOps Enthusiast  
- 🚀 Learning **AWS**, **DevOps**, and **Site Reliability Engineering**  
- 🛠️ Building projects with **Django**, **Flask**, **CI/CD pipelines (Jenkins, SonarQube, Nexus)**  
