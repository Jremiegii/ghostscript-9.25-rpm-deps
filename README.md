# Ghostscript 9.25 Dependency Installer

Repository ini bertujuan untuk mempermudah proses instalasi **Ghostscript versi 9.25**, khususnya dalam menangani masalah dependency yang seringkali menyebabkan instalasi gagal, terutama pada sistem berbasis Linux.

## 📌 Latar Belakang

Jika Anda mengalami kegagalan saat menginstal dependency Ghostscript versi 9.25, maka alternatif yang dapat Anda lakukan adalah dengan melakukan instalasi dependency yang diperlukan secara manual. Namun, hal ini tentu memerlukan banyak waktu untuk menemukan dan menginstal dependency tersebut satu per satu.

Oleh karena itu, repository ini hadir dengan tujuan untuk membantu Anda menemukan dan menginstal dependency yang dibutuhkan oleh Ghostscript versi 9.25 secara lebih mudah dan cepat.

## ⚠️ Masalah Umum

- Gagal instalasi karena dependency tidak ditemukan.
- Ketergantungan pada versi library tertentu.
- Instalasi manual memakan waktu dan kompleks.

## ✅ Solusi dari Repository Ini

Repository ini menyediakan:

- Daftar lengkap dependency yang dibutuhkan oleh Ghostscript 9.25.
- Paket `.rpm` untuk distro berbasis RHEL/CentOS/Fedora beserta panduan penggunaannya.
- Mempermudah proses instalasi dengan satu perintah `yum` atau `dnf`.

## 📥 Cara Instalasi

### Untuk CentOS/RHEL/Fedora (otomatis)

```bash
git clone https://github.com/Jremiegii/ghostscript-9.25-rpm-deps.git
cd ghostscript-9.25-rpm-deps
sudo yum localinstall rpm/*.rpm
```