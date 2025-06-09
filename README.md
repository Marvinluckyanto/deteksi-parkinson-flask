# Aplikasi Web Deteksi Penyakit Parkinson

Aplikasi web ini dibangun menggunakan framework Flask (Python) untuk mendeteksi tingkat keparahan penyakit Parkinson berdasarkan gambar tulisan tangan (spiral atau gelombang). Aplikasi ini memanfaatkan model Machine Learning yang telah dilatih untuk mengklasifikasikan gambar ke dalam empat kategori: Sehat, Stadium Awal (Ringan), Stadium Menengah (Sedang), dan Stadium Lanjut (Berat).

## Fitur Utama
* **Halaman Informasi:** Menyediakan penjelasan lengkap mengenai penyakit Parkinson, gejala, penyebab, dan referensi medis.
* **Prediksi Berbasis Gambar:** Pengguna dapat mengunggah gambar tulisan tangan untuk mendapatkan prediksi real-time.
* **Klasifikasi Multi-Kelas:** Model dapat membedakan antara kondisi sehat dan tiga stadium keparahan Parkinson.
* **Antarmuka Pengguna Interaktif:** Desain yang bersih dan mudah digunakan, dilengkapi dengan indikator loading dan pesan anjuran yang relevan.

## Teknologi yang Digunakan
* **Backend:** Python, Flask
* **Frontend:** HTML, CSS, JavaScript
* **Machine Learning:** TensorFlow (Keras), Scikit-learn, Joblib, NumPy
* **Pengolahan Gambar:** OpenCV, Pillow

## Cara Menjalankan Proyek Secara Lokal

Berikut adalah panduan untuk menjalankan aplikasi ini di komputer Anda sendiri.

### 1. Prasyarat
* Python 3.10
* Git (untuk meng-clone repositori)

### 2. Langkah-langkah Instalasi

1.  **Clone repositori ini:**
    Buka terminal atau Command Prompt, lalu jalankan perintah berikut:
    ```bash
    git clone [https://github.com/NAMA_ANDA/NAMA_REPO_ANDA.git](https://github.com/NAMA_ANDA/NAMA_REPO_ANDA.git)
    ```
    *Ganti `NAMA_ANDA` dan `NAMA_REPO_ANDA` dengan milik Anda.*

2.  **Masuk ke direktori proyek:**
    ```bash
    cd nama-repo-anda
    ```

3.  **Buat dan aktifkan Virtual Environment:**
    ```bash
    # Buat venv
    python -m venv venv

    # Aktifkan venv (Windows)
    .\venv\Scripts\activate

    # Aktifkan venv (macOS/Linux)
    # source venv/bin/activate
    ```

4.  **Install semua library yang dibutuhkan:**
    Jalankan perintah di bawah ini di dalam terminal yang `venv`-nya sudah aktif. Perintah ini akan menginstal semua library dengan versi yang sudah dipastikan kompatibel.
    ```bash
    pip install Flask==2.2.2 gunicorn==2.0.1 joblib==1.2.0 scikit-learn==1.2.2 numpy==1.23.5 tensorflow==2.10.0 opencv-python==4.8.0.76 Pillow==9.5.0 Werkzeug==2.2.2 Jinja2==3.1.2 protobuf==3.19.6
    ```

5.  **Jalankan aplikasi:**
    Setelah instalasi selesai, jalankan server Flask dengan perintah:
    ```bash
    python app.py
    ```

6.  **Akses aplikasi:**
    Buka browser web Anda dan kunjungi alamat `http://127.0.0.1:5000`. Aplikasi sekarang seharusnya sudah berjalan.

## Struktur Folder Proyek
