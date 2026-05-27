```markdown
# Hardening Challenge for Blue Team

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

Itu aja. Tinggal copy ke README.md, simpan, push. Beres.
