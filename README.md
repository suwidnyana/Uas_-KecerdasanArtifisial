# Fuzzy Persediaan - Sistem Logika Fuzzy untuk Produksi


Aplikasi ini digunakan untuk melakukan perhitungan <b>Fuzzy Logic</b> 
    dalam menilai <b>Kualitas Layanan Mobile Banking</b> berdasarkan 
    rating pengguna, jumlah crash, dan jumlah keluhan.  
    <br><br>
    Sistem ini juga dilengkapi visualisasi grafik fungsi keanggotaan untuk
    memudahkan pengguna memahami bagaimana fuzzy bekerja.
---

## 🛠️ Persiapan Sebelum Menjalankan

Sebelum menjalankan proyek ini, pastikan kamu telah menginstal:

- **Python 3.x**  
  Unduh dari [python.org](https://www.python.org/downloads/) dan pastikan sudah ditambahkan ke PATH.
- **pip** (Python package installer)  
  Biasanya sudah terinstal bersama Python. Untuk memastikan, jalankan:



---

## 📦 Instalasi dan Setup

1. Clone repository:
```
git clone https://github.com/suwidnyana/Uas_-KecerdasanArtifisial
```

2. Buat dan aktifkan virtual environment:
- **Windows:**
  ```
  python -m venv env_fuzzy_flask
  .\env_fuzzy_flask\Scripts\activate
  ```
- **macOS/Linux:**
  ```
  python3 -m venv env_fuzzy_flask
  source env_fuzzy_flask/bin/activate
  ```

3. Install dependencies:
 ```
pip install -r requirements.txt
 ```
  ```
pip install flask numpy matplotlib scikit-fuzzy

 ```
---

## 🚀 Menjalankan Aplikasi

1. Set environment variable untuk Flask app:
- **Windows:**
  ```
  set FLASK_APP=app.py
  ```
- **macOS/Linux:**
  ```
  export FLASK_APP=app.py
  ```

2. Jalankan server Flask:
```
flask run
```


---

## 📂 Struktur Folder


```text
Uas-KecerdasanArtifisial/
├── app.py
├── static/
│   └── img/
│       └── fuzzy_graph.png
├── templates/
│   ├── index.html
│   ├── base.html
│   ├── grafik.html
│   └── about.html
└── README.md
```

---

## ⚙️ Catatan Penting

- Proyek ini menggunakan python versi 3.10
- 
- 

---
# 🚀 Project Contribution Guide

Branch utama untuk development adalah **dev**. Semua fitur baru harus dibuat melalui branch `dev` diajukan melalui Pull Request ke branch `main`.

---

# 📥 1. Clone Repository
```bash
git clone https://github.com/suwidnyana/Uas_-KecerdasanArtifisial
cd <Uas_-KecerdasanArtifisial>
```

---

# 🌱 2. Checkout ke Branch `dev`
```bash
git fetch origin
git checkout dev
```
Jika branch `dev` sudah ada di lokal:
```bash
git checkout -b dev origin/dev
```

---

---

# 🛠 3. Mulai Coding & Commit
```bash
git add .
git commit -m "Add login page feature"
```

---

# 🔄4. Update Branch Sebelum Push 


```bash
git pull origin dev
```


---

# ⬆ 5. Push Branch ke GitHub
Jika pertama kali push:
```bash
git push origin dev
```

Push selanjutnya:
```bash
git push
```

---

# 🔀 7. Buat Pull Request ke `dev`
Di GitHub:
- **Base**: `dev`
- **Compare**: branch fitur kamu

Setelah di-review dan disetujui, baru merge.

---

# ♻ 8. Sinkronisasi Setelah PR Selesai
Kembali ke dev dan update:
```bash
git checkout dev
git pull origin dev
```

---

# 🧩 Siklus Kerja
1. Mulai dari `dev`
2. Buat `feature/<fitur>`
3. Coding → Commit
4. Rebase dari `dev`
5. Push
6. PR → `dev`
7. Merge setelah approved
8. Update dev & ulangi

---

Jika kamu butuh **diagram workflow Git**, **template PR**, atau **rules branching**, bilang saja dan akan aku tambahkan.
