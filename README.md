Inventory Management System
Sistem manajemen inventaris dengan frontend React/Next.js dan backend Node.js.

Teknologi yang Digunakan
Frontend

Next.js
React
Tailwind CSS
TypeScript

Backend

Node.js
Express
TypeScript
MongoDB/PostgreSQL (pilih salah satu)

Cara Instalasi
Prasyarat

Node.js (v14+)
npm atau yarn
Git

Langkah-langkah

Clone repository
bashgit clone https://github.com/username-anda/inv-management.git
cd inv-management

Setup Frontend
bashcd client
npm install

# atau

yarn install

Setup Backend
bashcd ../server
npm install

# atau

yarn install

Konfigurasi Environment

Salin .env.example menjadi .env di folder server
Atur variabel environment yang diperlukan

Cara Menjalankan Aplikasi
Development Mode

Jalankan Backend
bashcd server
npm run dev

# atau

yarn dev

Jalankan Frontend
bashcd client
npm run dev

# atau

yarn dev

Buka browser dan akses:

Frontend: http://localhost:3000
Backend API: http://localhost:8000/api

Production Mode

Build Frontend
bashcd client
npm run build

# atau

yarn build

Build Backend
bashcd server
npm run build

# atau

yarn build

Jalankan Aplikasi
bash# Di folder server
npm start

# atau

yarn start

Fitur Utama

Dashboard dengan statistik inventaris
Manajemen produk dan kategori
Pencatatan stok masuk dan keluar
Laporan inventaris
Manajemen pengguna

Kontribusi
Silakan buka issue atau submit pull request untuk kontribusi.
Lisensi
MIT
