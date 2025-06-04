# **Hospital Management System** (Django + SQL)  

_A web-based Hospital Management System built with Django and a SQL database. The system allows users to view hospital services, contact information, and includes login and signup functionality._  

## 🌟 Overview  
The **Hospital Management System** is a responsive web application designed using **Django** with **SQL** backend. It provides:  
✅ User authentication (Login/Signup)  
✅ Static pages: Home, Services, Contact, About  
✅ Modular Django template system  
✅ Integration with SQL database (SQLite by default)  

## 🔥 Features  
- 📂 **Responsive UI** – Built with Bootstrap for cross-device compatibility  
- 🔒 **User Authentication** – Secure Login and Signup system  
- 📄 **Static Pages** – Home, Services, Contact, About pages  
- 🗂️ **Modular Templates** – Efficient Django template management  
- 💾 **Database Integration** – SQLite as default; easily configurable to MySQL/PostgreSQL  

## ⚙️ Tech Stack  
- **Backend:** Django (Python)  
- **Database:** SQLite (default), configurable to MySQL/PostgreSQL  
- **Frontend:** HTML, CSS, Bootstrap  
- **Other:** Django Templates, Static files management  

## 📌 Installation  
Follow these steps to install and run the project:

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/sarmad259/DBMS-PROJECT.git
   cd DBMS-PROJECT

2. **Extract the Project Folder (if zipped):**
     unzip Project.zip
     cd Project  # or the extracted folder name

3. **Set up a virtual environment and activate it:**   
     python -m venv venv
     source venv/bin/activate    # On Windows: venv\Scripts\activate
 
4. **Install dependencies:**
     pip install -r requirements.txt

5. **Run migrations:**
     python manage.py makemigrations
     python manage.py migrate

6. **Create a superuser (optional for admin panel):**
     python manage.py createsuperuser

7. **Run the development server:**
     python manage.py runserver

8. **Open your browser and visit:**
      http://127.0.0.1:8000/


**📌 Notes:**
Default database is SQLite. You can change it in settings.py for MySQL or PostgreSQL.

Admin interface is accessible via /admin after creating a superuser.

Static files are managed with Django’s {% static %} tag.

**🤝 Contributors:**
Ubaid Ur Rehman - Creator & Project Lead
Sarmad259 – Creator & Developer



   
