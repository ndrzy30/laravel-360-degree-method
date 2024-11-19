# Laravel 360 Degree Method - Sistem Evaluasi Kinerja Karyawan 👥

[![Laravel](https://img.shields.io/badge/Laravel-10.0-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)](https://laravel.com)
[![PHP](https://img.shields.io/badge/PHP-8.1-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://php.net)
[![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)](https://mysql.com)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.0-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com)

## 📝 Deskripsi

Project Laravel yang menerapkan metode 360 derajat untuk evaluasi kinerja karyawan. Sistem ini memungkinkan penilaian komprehensif dari berbagai sudut pandang termasuk atasan, rekan kerja, bawahan, dan self-assessment.

## ✨ Fitur

- ✅ Authentication dan Authorization
- 👥 Manajemen Data Karyawan
- 📊 Penilaian 360 Derajat
- 📈 Dashboard Analisis Kinerja
- 📑 Manajemen Kriteria Penilaian
- 📋 Laporan Evaluasi
- 📱 Responsive Design

## 🛠️ Teknologi

- Laravel 10
- PHP 8.1
- MySQL
- Bootstrap 5
- JavaScript/jQuery
- Blade Template

## 📋 Persyaratan Sistem

- PHP >= 8.1
- Composer
- MySQL
- Node.js & NPM

## 🚀 Instalasi

1. Clone repository
```bash
git clone https://github.com/ndrzy30/laravel-360-degree-method.git
```

2. Install dependencies
```bash
composer install
npm install
```

3. Salin file .env.example ke .env
```bash
cp .env.example .env
```

4. Generate application key
```bash
php artisan key:generate
```

5. Setup database di file .env
```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel_360_degree
DB_USERNAME=root
DB_PASSWORD=
```

6. Jalankan migrasi dan seeder
```bash
php artisan migrate
php artisan db:seed
```

7. Jalankan server Laravel
```bash
php artisan serve
```

## 👨‍💻 Penggunaan

1. Akses sistem melalui `http://localhost:8000`
2. Login menggunakan credentials:
   - Admin: admin@example.com / password
   - Karyawan: user@example.com / password
3. Mulai melakukan evaluasi kinerja

## 📊 Metode 360 Derajat

Sistem mengimplementasikan penilaian dari berbagai perspektif:
- Penilaian Atasan (30%)
- Penilaian Rekan Kerja (30%)
- Penilaian Bawahan (20%)
- Self Assessment (20%)

## 🤝 Kontribusi

Kontribusi selalu welcome! Untuk berkontribusi:
1. Fork repository
2. Buat branch baru (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

## 📝 Lisensi

Distributed under the MIT License. See `LICENSE` for more information.

## 📫 Kontak

Project Link: [https://github.com/ndrzy30/laravel-360-degree-method](https://github.com/ndrzy30/laravel-360-degree-method)

[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/ndrzyy_99)
