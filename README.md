
Script to test Blue Team skills in system hardening (Ubuntu 22.04). Still an early version, may have many bugs. Hope you enjoy and keep supporting.

### Usage Guide (for beginners)

#### 1. Clone or download this repo
git clone https://github.com/Zuan-Hard/Hardening-Challenge.git
cd Hardening-Challenge

text

#### 2. Give execute permission
chmod +x hardening

text

#### 3. (Optional) Move to /usr/local/bin so it can be called from anywhere
sudo mv hardening /usr/local/bin/

text
Then just type: `sudo hardening`

#### 4. If not moved, run directly from the folder
sudo ./hardening --help

text

### Available Commands

- `sudo hardening --help` : Help
- `sudo hardening --setup` : Setup environment (required first time)
- `sudo hardening --questions` : View questions
- `sudo hardening --score` : Automatic scoring
- `sudo hardening --reset` : Reset setup flag

### Full Example
sudo hardening --setup
sudo hardening --questions

do hardening
sudo hardening --score

text

### Notes

- Only run in a VM/lab, not on a production server.
- Setup requires internet connection (~200MB download).
- Timer starts when the script is first called.
- Scoring only says "SUCCESS" or "NOT SECURE" (no details).# Hardening Challenge for Blue Team

Script buat nguji skill Blue Team dalam hardening sistem (Ubuntu 22.04). Masih versi awal, mungkin banyak bug. Semoga suka dan support terus.

## Tutorial Pemakaian (khusus pemula)

### 1. Clone atau download repo ini
```
git clone https://github.com/Zuan-Hard/Hardening-Challenge.git
cd Hardening-Challenge
```

### 2. Kasih izin eksekusi
```
chmod +x hardening
```

### 3. (Opsional) Pindah ke /usr/local/bin biar bisa dipanggil dari mana saja
```
sudo mv hardening /usr/local/bin/
```
Setelah itu, lo cukup ketik: `sudo hardening`

### 4. Jika tidak dipindahkan, jalankan langsung dari folder
```
sudo ./hardening --help
```

## Perintah yang tersedia

- `sudo hardening --help` : Bantuan
- `sudo hardening --setup` : Setup environment (wajib pertama kali)
- `sudo hardening --questions` : Lihat soal
- `sudo hardening --score` : Scoring otomatis
- `sudo hardening --reset` : Reset flag setup

## Contoh alur lengkap

```
sudo hardening --setup
sudo hardening --questions
# lakukan hardening
sudo hardening --score
```

## Catatan

- Hanya jalankan di VM/lab, bukan server produksi.
- Setup butuh koneksi internet (~200MB download).
- Timer berjalan sejak script dipanggil.
- Scoring hanya bilang "BERHASIL" atau "KURANG AMAN" (tanpa detail).
```
