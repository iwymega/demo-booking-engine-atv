# Daftar Fitur Aplikasi Pemesanan ATV (AdventurePro)

Berdasarkan struktur pada file `index.html`, berikut adalah daftar lengkap fitur-fitur yang terdapat pada aplikasi pemesanan ATV ini:

## 1. Alur Pemesanan 5 Langkah (Multi-step Booking Flow)

### Langkah 1: Pemilihan Paket (Paket)
- Pilihan paket aktivitas (contoh: *Mud Volcano Thrill* dan *Waterfall Cave Descent*).
- Menampilkan detail paket, rating, ulasan, durasi, harga coret, dan harga dasar.

### Langkah 2: Konfigurasi Berkendara & Tambahan (Kustom)
- **Pemilihan gaya berkendara**: *Single Ride* (1 motor, 1 orang) atau *Tandem Ride* (1 motor, 2 orang dengan biaya tambahan).
- **Jumlah Unit**: Penyesuaian jumlah unit ATV (kuota rombongan) dengan tombol interaktif plus/minus.
- **Layanan Tambahan (Add-ons)**: Pilihan opsional seperti Sewa GoPro, Baju Pelindung & Sepatu Boots, dan Makan Siang Prasmanan.

### Langkah 3: Pemilihan Jadwal (Jadwal)
- **Kalender**: Pemilihan tanggal kegiatan (menggunakan date picker standar).
- **Sesi Operasional**: Pemilihan sesi waktu (Terdapat 5 sesi dari pagi hingga malam dengan status ketersediaan dinamis seperti "Tersedia" atau "Sisa 2 Slot").

### Langkah 4: Informasi Tamu & Checkout (Detail)
- **Formulir Data Diri**: Input Nama Lengkap, Nomor WhatsApp, dan Alamat Email.
- **Sistem Kupon**: Input untuk kode promo/kupon dengan tombol terapkan.
- **Metode Pembayaran**: Pilihan antara QRIS/E-Wallet dan Virtual Account.

### Langkah 5: Tiket Elektronik (Sukses)
- Halaman konfirmasi berhasil.
- **E-Ticket (Digital Pass)**: Pembuatan tiket digital yang menampilkan detail pesanan (ID tiket, tanggal, sesi, nama tamu, unit) dan kode QR simulasi.
- **Cetak Tiket**: Tombol "Simpan PDF" untuk memanggil fungsi *print* pada browser.

## 2. Fitur Antarmuka & Navigasi

- **Navigasi Sticky Bawah (Footer Harga Real-time)**: Menampilkan ringkasan pesanan, total pembayaran yang terupdate secara otomatis berdasarkan setiap pilihan user, tag diskon, dan tombol navigasi utama (Lanjut/Bayar).
- **Navigasi Sticky Atas (Step Tracker)**: Bar penanda langkah untuk berpindah secara cepat antar proses pemesanan.
- **Mode Tema (Dark/Light Mode)**: Tombol *switcher* (ikon bulan/matahari) untuk mengubah tema tampilan antarmuka ke mode gelap atau mode terang.

## 3. Panel Admin Tersembunyi (Operator Hub)

Terdapat dasbor khusus yang dapat diakses melalui tombol rahasia ("Admin") pada header:
- **Metrik Langsung (Live Metrics)**: Menampilkan ringkasan pendapatan hari ini dan jumlah *booking* aktif.
- **Penyesuaian Harga (Pricing Overrides)**: Pengaturan untuk mengubah harga dasar paket secara *real-time* dari halaman admin.
- **Validator Tiket (QR Scanner)**: Simulasi pemindai tiket QR untuk digunakan di lapangan saat tamu datang.
