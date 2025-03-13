# Backend Portal Berita dengan Fastify

## 📌 Deskripsi
Proyek ini merupakan backend untuk portal berita yang dikembangkan menggunakan **Fastify**, sebuah framework Node.js yang ringan dan cepat. Backend ini menyediakan RESTful API untuk mengelola berita, kategori, pengguna, dan fitur lainnya yang diperlukan dalam sebuah portal berita.

## 🚀 Teknologi yang Digunakan
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

- **Node.js** (Runtime JavaScript)
- **Fastify** (Web Framework)
- **PostgreSQL** (Database Utama)
- **Prisma ORM** (Manajemen Database)
- **Redis** (Caching dan Session Management)
- **JWT (JSON Web Token)** (Autentikasi)
- **Swagger** (Dokumentasi API)
- **Docker** (Containerization)

## 📂 Struktur Direktori
```
📦 backend-portal-berita
├── 📂 src
│   ├── 📂 controllers   # Handler untuk setiap endpoint
│   ├── 📂 models        # Model untuk database
│   ├── 📂 routes        # Definisi routing Fastify
│   ├── 📂 services      # Business logic
│   ├── 📂 middlewares   # Middleware untuk autentikasi dan lainnya
│   ├── app.js          # Inisialisasi Fastify app
├── 📜 .env.example      # Contoh konfigurasi environment
├── 📜 docker-compose.yml # Konfigurasi Docker
├── 📜 prisma.schema     # Skema database untuk Prisma
├── 📜 package.json      # Konfigurasi npm dan dependencies
├── 📜 README.md         # Dokumentasi proyek ini
```

## 🛠️ Instalasi dan Menjalankan Proyek
### 1️⃣ Clone Repository
```sh
git clone https://github.com/username/backend-portal-berita.git
cd backend-portal-berita
```

### 2️⃣ Instalasi Dependensi
```sh
npm install
```

### 3️⃣ Konfigurasi Environment
Salin file `.env.example` menjadi `.env`, lalu sesuaikan dengan konfigurasi yang dibutuhkan:
```sh
cp .env.example .env
```

### 4️⃣ Jalankan Database dengan Docker
```sh
docker-compose up -d
```

### 5️⃣ Jalankan Migrasi Database
```sh
npx prisma migrate dev
```

### 6️⃣ Menjalankan Server Fastify
```sh
npm run dev
```
Server akan berjalan di `http://localhost:3000`

## 🔑 Autentikasi
Gunakan **JWT** untuk mengakses endpoint yang memerlukan autentikasi. Token dapat diperoleh melalui endpoint `/auth/login` dengan mengirimkan email dan password yang valid.

## 📖 Dokumentasi API
Setelah server berjalan, dokumentasi API dapat diakses melalui **Swagger UI**:
```
http://localhost:3000/docs
```

## 📌 Fitur
✅ CRUD Berita
✅ Manajemen Kategori Berita
✅ Autentikasi dan Otorisasi JWT
✅ Caching dengan Redis
✅ Dokumentasi API dengan Swagger
✅ Dockerized Deployment

## 🤝 Kontribusi
Pull request selalu terbuka! Silakan fork repo ini dan buat PR untuk perbaikan atau fitur baru.

## 📜 Lisensi
Proyek ini menggunakan lisensi **MIT**.

---
Dikembangkan dengan ❤️ oleh tim Urbansiana.id

