# ✈️ RTG (Ready To Go) Travels

**RTG Travels** is a professional online travel booking website designed as a CS350 Web Engineering project. It provides users with detailed destination info, top-rated travel packages, and the ability to book or customize trips—all in one responsive and user-friendly platform.

## 🌍 Features

- User registration & authentication
- Book pre-made travel packages or customize your own
- View team and package details
- Submit and view reviews (FAQs)
- Fully responsive layout (Bootstrap 5.2.3)
- Admin panel to manage assets and content

## 🧰 Tech Stack

- **Frontend:** HTML, CSS, Bootstrap 5.2.3
- **Backend:** PHP, Laravel (v8 or v9)
- **Database:** MySQL

## 🗄️ Database Tables

| Table Name | Purpose |
|------------|---------|
| `users` | Stores registered user details |
| `usertrips` | Tracks reservations for display |
| `team` | Holds team member info shown on site |
| `reviews` | Stores FAQ-style posts by users |
| `assets` | Contains image metadata and locations |

## ⚙️ How to Run

1. **Install XAMPP** (ensure Apache uses port 80, MySQL uses 3306)
2. Start **Apache** and **MySQL** via XAMPP control panel
3. Install **Laravel 8 or 9**
4. Place the project folder (e.g., `new/`) in your web root (e.g., `htdocs/`)
5. Open terminal and navigate to the project directory:
   ```bash
   cd path/to/new/
Import the database:

Open phpMyAdmin (localhost/phpmyadmin)

Create a new database

Paste and run the SQL from sql.txt (📌 Update local image paths if needed)

Run Laravel migration:

bash
Copy
Edit
php artisan migrate
Start the Laravel development server:

bash
Copy
Edit
php artisan serve
Open http://127.0.0.1:8000/ in your browser to use the app
