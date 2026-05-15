# Story Share App

A Progressive Web App (PWA) berbasis Single Page Application (SPA) yang dibuat sebagai submission proyek akhir kelas Belajar Pengembangan Web Intermediate Dicoding.

Aplikasi ini merupakan lanjutan dari aplikasi sebelumnya yang memungkinkan pengguna untuk membagikan cerita, melihat story pengguna lain pada peta interaktif, menyimpan story favorit menggunakan IndexedDB, serta mendukung fitur Push Notification dan akses offline menggunakan teknologi PWA.

## Features

* Single Page Application (SPA)
* Menampilkan daftar story dari API
* Menambahkan story baru
* Menampilkan marker lokasi pada peta
* Push Notification
* Progressive Web App (PWA)
* Installable Web App
* Offline Support
* Menyimpan story favorit menggunakan IndexedDB
* Responsive UI
* Accessibility support
* Favorite Story Management

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6+)
* Webpack
* IndexedDB
* Service Worker
* Web Push Notification
* Web App Manifest
* REST API
* Leaflet.js

## Main Features

### Story Feed

Pengguna dapat melihat daftar story dari API lengkap dengan gambar, deskripsi, tanggal upload, dan lokasi.

### Add Story

Pengguna dapat menambahkan story baru beserta gambar dan lokasi.

### Push Notification

Aplikasi mendukung push notification yang dapat diaktifkan maupun dinonaktifkan oleh pengguna.

### Favorite Story

Story favorit dapat disimpan secara lokal menggunakan IndexedDB dan tetap dapat diakses meskipun offline.

### Offline Mode

Aplikasi tetap dapat diakses saat offline menggunakan cache dari service worker.

## Progressive Web App (PWA)

Project ini telah menerapkan konsep Progressive Web App dengan fitur:

* Installable App
* Offline Access
* Service Worker
* Web App Manifest
* Push Notification
* Dynamic Caching

## IndexedDB Implementation

IndexedDB digunakan untuk:

* Menyimpan story favorit
* Menampilkan data favorit
* Menghapus data favorit

## How to Run the Project

### Menjalankan Secara Lokal

1. Clone repository

```bash id="u7l5s4"
git clone <repository-url>
```

2. Masuk ke folder project

```bash id="p5y63v"
cd Dicoding-Projeckt-Akhir-Intermediate-
```

3. Install dependencies

```bash id="b25u2o"
npm install
```

4. Jalankan development server

```bash id="k9d7lf"
npm run start-dev
```

## Learning Outcome

Melalui project ini, saya mempelajari:

* Pengembangan Progressive Web App (PWA)
* Implementasi Service Worker
* Push Notification API
* Penggunaan IndexedDB
* Offline caching strategy
* Single Page Application (SPA)
* Integrasi REST API
* Pengelolaan asynchronous JavaScript
* Web accessibility
* Deployment aplikasi web modern

## Author

Created by Rurin Haliza during Dicoding Front-End Back-End Web Development.
