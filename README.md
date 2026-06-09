# KasWarga - Digitalisasi Iuran Perumahan Terpercaya

KasWarga adalah solusi *Software as a Service* (SaaS) manajemen properti mikro yang dirancang untuk mengatasi krisis transparansi dan inefisiensi pengumpulan Iuran Pemeliharaan Lingkungan (IPL) di tingkat RT/RW.

Proyek ini dibangun sebagai pemenuhan tugas mata kuliah **Web Client Development (WCD01)**.

## 🎯 Fokus Masalah
1. **Beban Administratif:** Pengurus RT/RW menghabiskan banyak waktu mencocokkan mutasi rekening secara manual melalui *spreadsheet*.
2. **Kebocoran Dana Tunai:** Pembayaran tunai melalui pihak ketiga (keamanan) rentan tidak tercatat secara *real-time*.
3. **Kesenjangan Demografi:** Warga senior (lansia) kesulitan jika dipaksa mengunduh aplikasi baru atau mengingat kata sandi untuk sekadar membayar iuran.

## 🚀 Konsep Solusi
KasWarga menggunakan pendekatan antarmuka ala perbankan (terinspirasi dari BCA) untuk menanamkan rasa aman. Sistem ini beroperasi penuh di peramban (web) dengan arsitektur *Mobile-First*, memungkinkan akses instan tanpa instalasi.

### Fitur Utama (MVP)
* **Pencarian Tagihan Tanpa Login:** Warga cukup mencari nama komplek dan memasukkan nomor kavling untuk melihat tagihan, meniru pengalaman membayar tagihan listrik.
* **Integrasi QRIS Dinamis:** (Dalam Pengembangan) Memastikan nominal pembayaran presisi hingga ke digit terakhir untuk memudahkan rekonsiliasi pengurus.
* **Dasbor Pengurus (Role-Based):** Area tertutup untuk bendahara memantau arus kas masuk/keluar dan menandai status hunian (dispensasi/kosong).
* **Transparansi Kas:** Tampilan ringkasan kas yang bisa diakses warga sebagai bentuk akuntabilitas kepengurusan.

## 🛠️ Tech Stack (Rencana Eksekusi)
* **Desain & UI/UX:** Figma
* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **Database/Backend (BaaS):** Supabase / Firebase (Tahap integrasi)

---
*Proyek ini dikembangkan secara bertahap (Learning by Doing) dari kerangka visual hingga deployment produksi.*
