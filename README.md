# Solana Auto Transaction Script
Script ini menggunakan Node.js untuk mengirim transaksi otomatis di jaringan Solana (Solana Devnet).

# Persiapan Awal
Pastikan Anda sudah memiliki Node.js terinstal di komputer Anda. Jika belum, Anda dapat mengunduhnya dari nodejs.org.

# Langkah-langkah untuk Menjalankan Script
1. Clone Repositori:

Clone repositori ini ke komputer Anda dengan menjalankan perintah berikut di terminal:

```git clone git@github.com:username/sol-auto-tx.git
cd sol-auto-tx```

2. Instal Dependensi:

Instal dependensi yang dibutuhkan dengan perintah:

bash
Copy code
npm install
Setel Environment Variables:

Buat file .env di direktori ini dan tambahkan seed phrases atau private keys untuk akun Solana Anda:

plaintext
Copy code
SEED_PHRASES=["your seed phrase 1", "your seed phrase 2"]
PRIVATE_KEYS=["your private key 1", "your private key 2"]
Gantilah your seed phrase 1, your seed phrase 2, your private key 1, your private key 2 dengan seed phrase dan private keys yang sesuai. Pastikan untuk tidak membagikan file .env ini secara publik.

Jalankan Script:

Jalankan script untuk memulai pengiriman transaksi otomatis:

bash
Copy code
node index.js
Script ini akan mengirim sejumlah kecil SOL (Solana) ke beberapa alamat acak yang dibuat.

Catatan Penting:

Pastikan Anda memiliki saldo SOL yang cukup di akun yang digunakan untuk pengiriman.
Sesuaikan DEVNET_URL di index.js dengan URL jaringan Solana yang Anda inginkan.
