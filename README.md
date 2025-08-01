# 🌿 Sistem Rekomendasi Tanaman – Metode SAW (CI 4)

Aplikasi web berbasis CodeIgniter 4 yang menggunakan metode **Simple Additive Weighting (SAW)** untuk merekomendasikan jenis tanaman berdasarkan kriteria tertentu. Cocok untuk pertanian, perkebunan, atau kebutuhan agribisnis lokal.

## 🔍 Fitur Utama
- Input data alternatif (jenis tanaman)
- Input data kriteria & bobot
- Perhitungan otomatis menggunakan metode SAW
- Hasil rekomendasi dengan nilai tertinggi
- Dashboard sederhana dan mudah digunakan

## 🛠️ Tech Stack
- **Backend:** PHP 8+, CodeIgniter 4
- **Database:** MySQL / MariaDB
- **Library Tambahan:** Bootstrap, jQuery (opsional)

## 📦 Cara Instalasi

1. **Clone repositori**
   ```bash
   git clone https://github.com/RizalRio/plant-recommendation-saw-ci4.git
   cd plant-recommendation-saw-ci4
Install dependensi

bash
Salin
Edit
composer install
Copy .env & konfigurasi

bash
Salin
Edit
cp env .env
php spark key:generate
# Edit database di .env
Migrasi database (jika tersedia)

bash
Salin
Edit
php spark migrate
Jalankan local server

bash
Salin
Edit
php spark serve
📸 Screenshot / Preview
(Tambahkan tampilan rekomendasi & input form jika ada)

⚙️ Metode SAW
SAW atau Simple Additive Weighting adalah metode penjumlahan terbobot dari kriteria yang telah dinormalisasi, menghasilkan skor akhir untuk tiap alternatif tanaman. Proses:

Normalisasi matriks

Bobot dikalikan

Penjumlahan total nilai tiap alternatif

🎯 Tujuan Proyek
Project ini bertujuan untuk membantu pengguna memilih tanaman terbaik berdasarkan preferensi kriteria, serta sebagai pembelajaran penerapan metode pengambilan keputusan berbasis SAW dalam pengembangan web modern.

Made with ☕ by RizalRio
💡 Feel free to fork and customize!
