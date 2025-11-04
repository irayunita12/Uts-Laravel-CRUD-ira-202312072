# 📌 Projek UTS PBF (Pemrograman Berbasis Framework)

Dokumentasi ini dibuat untuk memenuhi tugas mata kuliah **Pemrograman Berbasis Framework (PBF)**.  
Project ini berisi aplikasi berbasis web dengan fitur CRUD dan beberapa fitur tambahan seperti export PDF/Excel.

---

## 👩‍💻 **Identitas Penyusun**
| Keterangan        | Isi                             |
|-------------------|----------------------------------|
| Nama              | IRAYUNITA                       |
| NIM               | 202312072                       |
| Kelas             | TI Pagi                  |
| Mata Kuliah       | Pemrograman Berbasis Framework  |
| Dosen Pengampu    | Fiky Anggara,S.Kom,M.Kom|

---

## 📖 **Deskripsi Singkat Proyek**
Aplikasi ini dibuat menggunakan **PHP Laravel Framework** dan bertujuan untuk melakukan:
- Pengelolaan data (CRUD – Create, Read, Update, Delete).
- Export data ke **PDF** dan **Excel**.
- Tampilan UI responsif dan mudah digunakan.

---

## ⚙️ **Teknologi yang Digunakan**
- **Laravel** (PHP Framework)
- **MySQL / phpMyAdmin**
- **Bootstrap / Tailwind CSS**
- **XAMPP / Apache**
- **Git & GitHub (Version Control)**

---

## 🚀 **Cara Menjalankan Proyek di Lokal (Localhost)**

```bash
# 1. Clone repository ini:
git clone https://github.com/irayunita12/Uts-Laravel-CRUD-ira-202312072.git

# 2. Masuk ke folder project:
cd projek-uts-pbf

# 3. Install dependency Laravel:
composer install

# 4. Copy file .env
cp .env.example .env

# 5. Atur koneksi database di file .env
DB_DATABASE=cd_crud
DB_USERNAME=root
DB_PASSWORD=

# 6. Generate key Laravel:
php artisan key:generate

# 7. Migrasi database + seeder (jika ada)
php artisan migrate --seed

# 8. Jalankan server:
php artisan serve
```

---

## ✅ **Fitur-Fitur Aplikasi**
- ✅ Login (opsional jika ada)
- ✅ CRUD (Tambah, Edit, Hapus, Detail Data)
- ✅ Export **PDF**
- ✅ Export **Excel**
- ✅ Pencarian & Pagination Data
- ✅ Tampilan responsif (Bootstrap/Tailwind)

---

## 🗂️ **Struktur Folder Utama Laravel**
```
projek-uts-pbf/
│
├── app/          # Controller, Model, dll.
├── resources/    # Views (Blade Template)
├── routes/       # web.php (Routing)
├── public/       # File frontend
└── database/     # Migrations dan Seeder
```

---

## 📷 **Screenshot Tampilan (Opsional)**
Kamu bisa tambahkan gambar seperti:
```
/screenshots/login-page.png
/screenshots/dashboard.png
/screenshots/data-crud.png
```

---

## 📌 **Lisensi**
Project ini dibuat untuk keperluan akademik dan pembelajaran.

---

## 💬 **Kontak**
- 📧 Email: Irayunita2023@gmail.com 
- 💻 GitHub: https://github.com/irayunita12

---

