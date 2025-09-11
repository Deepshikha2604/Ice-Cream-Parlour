# IceCreamistry 🍦

A Django-based web application for managing and displaying products, handling user accounts, and showcasing interactive features.  
The project uses **Bootstrap** for styling and **JavaScript libraries** like Owl Carousel, Isotope, and Lightbox for a modern, engaging UI.


## 🚀 Features

- **Product Management** – Manage and display products (`products` app).
- **User Authentication & Profiles** – User registration, login, and profile management (`userApp` app).
- **Responsive UI** – Built with Bootstrap SCSS for mobile-friendly design.
- **Interactive UI Elements** – Carousels, galleries, and filtering.
- **Static Asset Management** – Organized CSS, JS, and media files.


## 📂 Project Structure

```

iceCreamistry/
│
├── manage.py
├── iceCreamistry/
│   ├── settings.py
│   ├── urls.py
│   └── ...
│
├── products/
│   ├── models.py
│   ├── views.py
│   └── ...
│
├── userApp/
│   ├── models.py
│   ├── views.py
│   └── ...
│
├── static/
│   ├── css/
│   ├── js/
│   ├── lib/
│   └── ...
│
├── templates/
│   ├── main.html
│   ├── navbar.html
│   └── ...
└── requirements.txt

````


## 🛠️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/iceCreamistry.git
cd iceCreamistry
````

### 2️⃣ Create & Activate Virtual Environment

```bash
# Windows
python -m venv myEnv
myEnv\Scripts\activate

# macOS/Linux
python -m venv myEnv
source myEnv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Apply Migrations

```bash
python manage.py migrate
```

### 5️⃣ Create Superuser (Optional)

```bash
python manage.py createsuperuser
```

### 6️⃣ Run Development Server

```bash
python manage.py runserver
```


## 📦 Static & Media Files

* **Static files**: Located in `static/`
* **Templates**: Located in `templates/`
* **Media uploads**: Configured in `settings.py` via `MEDIA_URL` and `MEDIA_ROOT`


## 🛡️ Security Note

Before uploading your code to GitHub:

* Add a `.env` file for sensitive settings like `SECRET_KEY` and database credentials.
* Update `.gitignore` to exclude:

  ```
  db.sqlite3
  .env
  __pycache__/
  *.pyc
  venv/
  staticfiles/
  media/
  ```
* Use packages like [`django-environ`](https://pypi.org/project/django-environ/) for environment variables.


## 📜 License

This project is licensed under the **MIT License**.


**👩‍💻 Developed by \[Deepshikha]**


