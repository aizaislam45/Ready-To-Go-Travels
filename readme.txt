````markdown
# ✈️ RTG (Ready To Go) Travels

**RTG Travels** is an online travel booking website developed as part of the CS350 Web Engineering project. It allows users to explore destinations, book travel packages, and customize trips with ease. The platform ensures a professional, responsive experience with secure backend support.

## 🌍 Features

- User registration & authentication
- Book pre-defined or custom travel packages
- Explore travel info and team details
- Post and view reviews (FAQs)
- Responsive layout with Bootstrap 5.2.3

## 🧰 Tech Stack

- **Frontend:** HTML, CSS, Bootstrap 5.2.3
- **Backend:** PHP, Laravel 8/9
- **Database:** MySQL

## 🗄️ Database Tables

- `users`: Stores registered user details  
- `usertrips`: Tracks user reservations  
- `team`: Contains team member info  
- `reviews`: Holds FAQ-style posts  
- `assets`: Stores image metadata and paths

## ⚙️ How to Run

1. Download and install **XAMPP** (Apache: port 80, MySQL: port 3306)
2. Start Apache and MySQL via XAMPP
3. Install Laravel 8 or 9
4. Place the project folder (e.g., `new/`) in your preferred directory
5. Open terminal, navigate to project directory:
   ```bash
   cd path/to/new/
````

6. Open **phpMyAdmin**, create a new database
7. Run SQL from `sql.txt` (replace image paths as needed)
8. Run Laravel migration:

   ```bash
   php artisan migrate
   ```
9. Start the Laravel server:

   ```bash
   php artisan serve
   ```
10. Open your browser and go to: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

