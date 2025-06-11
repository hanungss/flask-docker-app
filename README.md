
# Flask Docker App

Proyek ini adalah contoh sederhana aplikasi web menggunakan Flask (Python) yang dijalankan di dalam container Docker. Aplikasi ini menampilkan halaman HTML dengan CSS dan gambar statis.

---

## 🚀 Fitur

- Web server ringan berbasis Flask
- Menampilkan halaman HTML dengan gaya CSS
- Dibungkus dengan Docker, jadi mudah dijalankan di mana saja

---

## 📁 Struktur Folder

```
flask-docker-app/
├── app.py                  # File utama aplikasi Flask
├── requirements.txt        # Dependensi Python
├── Dockerfile              # Konfigurasi build Docker
├── templates/
│   └── index.html          # Template HTML utama
└── static/
    ├── css/
    │   └── style.css       # File CSS
    └── img/
        └── logo.png        # Gambar statis
```

---

## 🛠️ Cara Menjalankan

### 1. Clone repository ini

```bash
git clone https://github.com/hanungss/flask-docker-app.git
cd flask-docker-app
```

### 2. Build Docker image

```bash
docker build -t flask-docker-app .
```

### 3. Jalankan container

```bash
docker run -p 5000:5000 flask-docker-app
```

### 4. Akses di browser

Buka [http://localhost:5000](http://localhost:5000)

---

## 🧪 Cek Gambar & Style

Pastikan file `static/img/logo.png` ada. Jika belum ada, bisa:
- Tambahkan manual
- Gunakan gambar placeholder
- Atau hapus tag `<img>` dari HTML

---

## 📄 Lisensi

Proyek ini bebas digunakan untuk belajar atau keperluan pribadi.

---

## 🤝 Kontribusi

Pull request dipersilakan. Untuk perubahan besar, mohon buka issue terlebih dahulu.
