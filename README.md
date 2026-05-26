# 🚀 Laravel Blade Auth + AdminSB2 Starter

Project Laravel menggunakan **Blade Template**, **Laravel Authentication**, dan integrasi template **AdminSB2** untuk membuat dashboard admin modern dan responsive.

---

## ✨ Fitur Utama

- ✅ Laravel Blade Template
- 🔐 Authentication Laravel (Login, Register, Logout)
- 🎨 Integrasi Template AdminSB2
- 📊 Dashboard Admin Responsive
- ⚡ Vite Asset Build
- 🗂️ Struktur project rapi dan mudah dikembangkan

---

## 🛠️ Teknologi

- PHP 8+
- Laravel 12
- Blade Template Engine
- Bootstrap 5
- AdminSB2
- Vite

---

## 📦 Instalasi Project

### 1. Clone Repository

```bash
git clone https://github.com/Roouuff/webberita.git
```

### 2. Masuk Folder Project

```bash
cd webberita
```

### 3. Install Dependency

```bash
composer install
npm install
```

### 4. Copy File Environment

```bash
cp .env.example .env
```

> Untuk pengguna Windows CMD bisa menggunakan:

```bash
copy .env.example .env
```

### 5. Generate Application Key

```bash
php artisan key:generate
```

### 6. Konfigurasi Database

Edit file `.env`

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nama_database
DB_USERNAME=root
DB_PASSWORD=
```

### 7. Jalankan Migration

```bash
php artisan migrate
```

### 8. Jalankan Server

```bash
php artisan serve
npm run dev
```

Akses project di browser:

```txt
http://127.0.0.1:8000
```

---

## 🔐 Authentication Laravel

Fitur authentication yang tersedia:

- Login
- Register
- Logout
- Session Authentication

Referensi implementasi authentication Laravel:

- Tutorial Laravel Auth  
  https://sites.google.com/unhasy.ac.id/edwinhap/laravel-auth/praktikum-auth-laravel

---

## 🎨 Integrasi AdminSB2

Template dashboard menggunakan:

- Sidebar Navigation
- Navbar Admin
- Dashboard Cards
- Responsive Layout
- Bootstrap Components

Official Website AdminSB2:

- https://startbootstrap.com/theme/sb-admin-2

---

## 📁 Struktur Folder Penting

```txt
resources/views/
├── auth/
├── dashboard/
├── layouts/
└── components/

public/
├── css/
├── js/
└── vendor/
```

---

## 📸 Tampilan

Fitur halaman yang tersedia:

- Login Page
- Register Page
- Dashboard Admin
- Sidebar Navigation

---

## 🚀 Upload ke GitHub

### Inisialisasi Git

```bash
git init
git add .
git commit -m "Initial commit"
```

### Hubungkan ke Repository GitHub

```bash
git remote add origin https://github.com/Roouuff/webberita.git
git branch -M main
git push -u origin main
```

---

## 👨‍💻 Developer

Project dibuat menggunakan Laravel Blade dan AdminSB2 untuk kebutuhan pembelajaran dan pengembangan aplikasi web admin dashboard.

---

## 📌 Repository

https://github.com/Roouuff/webberita