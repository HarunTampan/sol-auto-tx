# Solana Auto Transaction Script
Script ini menggunakan Node.js untuk mengirim transaksi otomatis di jaringan Solana (Solana Devnet).

# Persiapan Awal
Pastikan Anda sudah memiliki Node.js terinstal di komputer Anda. Jika belum, Anda dapat mengunduhnya dari nodejs.org.

# Langkah-langkah untuk Menjalankan Script
1. Clone Repositori:

Clone repositori ini ke komputer Anda dengan menjalankan perintah berikut di terminal:

```
git clone https://github.com/HarunTampan/sol-auto-tx.git
cd sol-auto-tx
```


2. Instal Dependensi:

Instal dependensi yang dibutuhkan dengan perintah:

```
npm install
```

3. Setel Environment Variables:

Buat file .env di direktori ini dan tambahkan seed phrases atau private keys untuk akun Solana Anda:


```
SEED_PHRASES=["your seed phrase 1", "your seed phrase 2"]
PRIVATE_KEYS=["your private key 1", "your private key 2"]
```
Gantilah your seed phrase 1, your seed phrase 2, your private key 1, your private key 2 dengan seed phrase dan private keys yang sesuai. Pastikan untuk tidak membagikan file .env ini secara publik.


4. Jalankan Script:

Jalankan script untuk memulai pengiriman transaksi otomatis:

```
node auto_tx.js
```
Script ini akan mengirim sejumlah kecil SOL (Solana) ke beberapa alamat acak yang dibuat.

Catatan Penting:
Pastikan saldo SOL mencukupi di akun yang digunakan untuk pengiriman.
Sesuaikan `DEVNET_URL` di `index.js` dengan URL jaringan Solana yang Anda inginkan.

# Kontak
- [Email](dkipas08@gmail.com)
- [Twitter](https://x.com/AirdropIdn25)
- [Telegram](https://t.me/FxcTe)
