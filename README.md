# 📚 Library Management System (Laravel + Blade + Livewire)

A Library Management System built with **Laravel, Blade, and Livewire**.  
This system allows admins and librarians to manage books, borrowing, reservations, and reports efficiently, while providing students with easy access to book search and reservation features.  

---

## 🚀 Features

### 👩‍💻 For Admin & Librarian
- ✅ Dashboard with key statistics (total books, borrowed, overdue, reservations, users)
- ✅ Book management (add, edit, delete, search)
- ✅ Borrowing & returning system
- ✅ Reservation approval/decline
- ✅ User management (students, librarians, admins)
- ✅ Reports & activity logs

### 🎓 For Students
- 🔍 Search books by title, author, category
- 📖 Reserve available books
- 📦 View borrowed books & due dates
- ⏰ Overdue reminders

---

## 🛠️ Tech Stack
- **Backend:** Laravel 10
- **Frontend:** Blade + Livewire + Tailwind CSS
- **Database:** MySQL / MariaDB
- **Authentication:** Laravel Breeze or Jetstream (optional)

---

## 📂 Project Structure
```

app/
├── Http/
│   ├── Controllers/
│   ├── Livewire/
│   └── Middleware/
├── Models/
database/
├── migrations/
├── seeders/
resources/
├── views/
└── components/
routes/
├── web.php
└── api.php

````

---

## ⚙️ Installation

### 1️⃣ Clone Repository
```bash
git clone https://github.com/Ahyan3/library-management-system-laravel.git
cd library-management-system-laravel
````

### 2️⃣ Install Dependencies

```bash
composer install
npm install && npm run dev
```

### 3️⃣ Setup Environment

Copy `.env.example` and update database credentials:

```bash
cp .env.example .env
php artisan key:generate
```

### 4️⃣ Run Migrations & Seeders

```bash
php artisan migrate --seed
```

### 5️⃣ Start Development Server

```bash
php artisan serve
```

Visit 👉 `http://127.0.0.1:8000`

---

## 📸 Screenshots

### 📊 Dashboard

![Dashboard Screenshot](screenshots/dashboard.png)

### 📚 Book Management

![Book Management](screenshots/books.png)

### 📦 Borrow & Reservation

![Borrowing System](screenshots/borrow.png)

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

---

## 📝 License

This project is open-source and available under the **MIT License**.
