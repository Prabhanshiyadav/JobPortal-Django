🧑‍💼 JobPortal Django Web Application

A full-featured Job Portal built using **Django**. It allows employers to post job listings and job seekers to view and apply for them. The platform is deployed live using **Render**.

---

## 🌐 Live Demo

🔗 **Live Site:** [https://edumanage-project.onrender.com/](https://jobportal-n5ym.onrender.com/)  
🔗 **GitHub Repository:** [https://github.com/Prabhanshiyadav/JobPortal-Django](https://github.com/Prabhanshiyadav/JobPortal-Django)

---

## 🚀 Features

- 📝 Post and manage job listings
- 🔍 Browse available jobs
- 👨‍💼 Admin dashboard to manage jobs
- 📅 Job details view page
- 🌐 Deployed on Render (free tier)

---

## 🛠️ Tech Stack

- **Backend**: Django
- **Frontend**: HTML, CSS (Django templates)
- **Database**: SQLite
- **Deployment**: Render
- **Web Server**: Gunicorn

---

## 📂 Project Structure

JobPortal/
├── jobs/ # Django app for job listings
├── JobPortal/ # Project settings and URLs
├── templates/ # HTML Templates
├── static/ # CSS, JS, etc.
├── manage.py
├── requirements.txt
├── Procfile
├── render.yaml (optional for deployment)





---

## ⚙️ Installation (Local Setup)

```bash
# 1. Clone the repo
git clone https://github.com/Prabhanshiyadav/JobPortal-Django.git
cd JobPortal-Django

# 2. Create virtual environment & activate
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run migrations
python manage.py migrate

# 5. Run the development server
python manage.py runserver


🔐 Admin Login
Access Django admin at:
https://edumanage-project.onrender.com/admin/

📃 License
This project is licensed under the MIT License.
Feel free to use and modify it for learning or portfolio purposes.

💡 Author
Made with ❤️ by Prabhanshi Yadav
