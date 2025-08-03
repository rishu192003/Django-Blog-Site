# 📝 Django Blog Website

A simple, clean, and functional blog website built with Django. Users can read blog posts, view post details, and (if admin) create, update, or delete posts via the Django admin panel.

---

## 📌 Features

- View all blog posts  
- Individual blog post pages  
- Django admin panel for managing content  
- Responsive frontend using Bootstrap (or your preferred CSS framework)  
- User authentication *(optional, if implemented)*  

---

## 🔧 Tech Stack

- **Backend:** Python, Django  
- **Database:** SQLite (default)  
- **Frontend:** HTML, CSS, Bootstrap  
- **Others:** Django Admin, Django Templates  

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/django-blog.git
cd django-blog
2. Set Up a Virtual Environment (optional but recommended)
bash
Copy
Edit
python -m venv env
source env/bin/activate     # For Linux/macOS
env\Scripts\activate        # For Windows
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
4. Run Migrations
bash
Copy
Edit
python manage.py migrate
5. Create a Superuser (to access the admin panel)
bash
Copy
Edit
python manage.py createsuperuser
6. Start the Server
bash
Copy
Edit
python manage.py runserver
Visit http://127.0.0.1:8000/ to see the website in action.

📁 Project Structure
csharp
Copy
Edit
django-blog/
├── blog/               # Blog app
├── django_my_site/     # Project settings
├── my_site/            # Main
├── templates/          # HTML templates
├── static/             # Static files (CSS, JS)
├── staticfiles/        
├── uploads/            
├── db.sqlite3          # Default SQLite DB
├── manage.py           
└── requirements.txt    
🛠️ Admin Panel
You can manage posts easily at:

http://127.0.0.1:8000/admin/

Use the credentials from the superuser you created.

🌐 Deployment
Live demo: https://django-blog-site-1.onrender.com/

📷 Screenshots
![Blog Screenshot](uploads/posts/Screenshot%202025-08-03%20115551.png)

📄 License
This project is open-source and available under the MIT License.
