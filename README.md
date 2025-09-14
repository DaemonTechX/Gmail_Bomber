<h1 align="center"><code>GMAIL BOMBER</code></h1> <p align="center"> <img src="https://github.com/DaemonTechX/gmail_bomber/blob/main/gmail_bomb.png" width="590"><br><br>

**Gmail bomber adalah sebuah alat atau skrip yang dirancang untuk mengirim banyak email secara berulang-ulang ke satu alamat Gmail (atau beberapa alamat) dalam waktu singkat. Tujuannya biasanya untuk membanjiri kotak masuk penerima sehingga membuat email penting tertutup, mengganggu operasi, atau memaksa layanan menjadi tidak nyaman/terganggu.**

![Screenshot Dalam Tool](https://github.com/DaemonTechX/Gmail_Bomber/blob/main/Screenshot_20250914-112242.png)

# PERSYARATAN
- library requests
- Alamat Gmail (Sender)
- App Password Alamat Gmail

# CARA PAKAI
1. Clone Repository Ini & Install Kebutuhannya
2. Jalankan Scriptnya
3. Masukkan Alamat Gmail & App Password (Sender) Cukup 1× Saja Karena Otomatis Akan Disimpan Didalam File .config.json
4. Pilih Opsi 1 Untuk Memulai Bomb Gmail Target
5. Masukkan Alamat Gmail Target
6. Masukkan Isi Pesan
7. Masukkan Jumlah Pesan Yang Ingin Dikirim
8. Proses Pengiriman Pesan
9. Done

# TUTORIAL DAPATKAN APP PASSWORD
**https://youtu.be/ckfyTVgF1T4?si=xjL7TjEO5ZKWZY0v**

# INSTALASI UNTUK TERMUX
```bash
pkg update && pkg upgrade
pkg install python
pkg install python-pip
pkg install git
git clone https://github.com/DaemonTechX/Gmail_Bomber
cd Gmail_Bomber
pip install requests
python gmail_bomber.py
```
