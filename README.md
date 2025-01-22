# Hapus Konten dari File Teks

Proyek ini adalah skrip Python sederhana yang digunakan untuk menghapus kalimat tertentu dari file teks berdasarkan kata kunci yang diberikan

## Fitur
- Membaca konten dari file teks (`.txt`).
- Mencari baris yang mengandung kata kunci tertentu.
- Menghapus kalimat yang mengandung kata kunci dari file teks.

## Persyaratan
- Python 3.6 atau lebih baru.

## Cara Menggunakan
1. Pull image proyek ini.
2. Pastikan Python sudah diinstal di sistem Anda.
3. Buat file teks dengan nama `daftar.txt` yang berisi data,
misalnya:
Halo, ini adalah contoh daftar.
Saya mendapatkan dana kaget dari teman saya.
Dana kaget senilai satu juta.
Yeyyy dapat dana kaget.
Selamat mencoba aplikasi ini.
SEMANGATTTT

##INSTAL & PULL IMAGE

1. Instal Docker
sudo apt update
sudo apt install docker.io
sudo systemctl start docker
sudo systemctl enable docker

2. Pull Image
docker pull kyranova/hapus-konten

3. Jalankan
docker run --rm -v /lokasi/daftar.txt:/app/daftar.txt kyranova/hapus-konten python /app/hapus_konten.py /app/daftar.txt "KATA KUNCI"

- Ubah `/lokasi/daftar.txt` dengan dimana `daftar.txt` yang kamu buat tadi.
- Ubah `KATA KUNCI` dengan kata kunci yang akan kamu hapus.

4. Lihat hasilnya
cat daftar.txt

5. Setelah dijalankan, file daftar.txt akan diperbarui dengan menghapus kalimat yang mengandung kata kunci tersebut.








naufaltunder27@gmail.com