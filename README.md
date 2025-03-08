# Setup dengan PyPy

Ikuti langkah-langkah berikut:

## 1. Unduh dan Ekstrak PyPy
Silakan unduh PyPy dari situs:

[PyPy Download](https://www.pypy.org/)

Setelah diunduh, ekstrak file yang telah diunduh ke lokasimu.

## 2. Buat Virtual Environment
Buka terminal dan jalankan perintah berikut dengan menyesuaikan path ke direktori PyPy yang telah diekstrak:

```sh
/<path-ke-pypy>/bin/python -m venv venv
```

Gantilah `<path-ke-pypy>` dengan lokasi tempat kamu mengekstrak PyPy, misalnya:

```sh
~/pypy3.11-v7.3.19-macos_arm64/bin/python -m venv venv
```

Setelah perintah ini dijalankan, folder `venv` akan dibuat di direktori kerja saat ini.

## 3. Aktifkan Virtual Environment
Aktifkan virtual environment dengan menjalankan perintah berikut:

```sh
source venv/bin/activate
```

## 4. Instalasi Dependensi
Setelah virtual environment aktif, instal semua dependensi dengan perintah berikut:

```sh
pip install -r requirements.txt
```

## 5. Jalankan Aplikasi
Terakhir, jalankan aplikasi dengan perintah berikut:

```sh
python app.py
```
