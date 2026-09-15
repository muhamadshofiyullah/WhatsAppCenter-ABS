# 📋 Catatan Pembaruan (Changelog)

Di halaman ini Anda dapat melihat daftar perbaikan, peningkatan fitur, dan riwayat pembaruan dari aplikasi **WhatsApp Center**.

---

## 🌟 Versi 2.1.5.5 (15 September 2026)

Pembaruan kali ini berfokus pada **peningkatan kecepatan, kestabilan pengiriman pesan, dan kebebasan dari macet/freeze**.

### ✨ Apa yang Baru & Ditingkatkan?
- **Otomatis Tutup Pop-Up WhatsApp:**  
  Jika WhatsApp menampilkan jendela pop-up seperti *"Apa yang baru di WhatsApp Web"*, aplikasi sekarang dapat langsung menutupnya sendiri. Pengiriman dan pembacaan pesan tidak akan terhalang lagi.
- **Pesan Susulan Tidak Lagi Terlewat:**  
  Kini jika ada pelanggan yang mengirim pesan berturut-turut (misal pesan kedua masuk beberapa detik setelah pesan pertama), aplikasi dapat membaca pesan tersebut secara konsisten tanpa ada yang tertinggal.
- **Perbaikan Masalah Pesan Terkirim Dobel:**  
  Memperbaiki kendala di mana pesan balasan atau notifikasi terkadang terkirim 2 kali ke pelanggan saat sistem mencari nomor kontak.
- **Respon Baca Pesan Lebih Cepat & Enteng:**  
  Sistem pembacaan pesan baru kini jauh lebih efisien dan ringan, sehingga tidak membebani kerja prosesor (CPU) komputer Anda.
- **Bebas Kotak Pesan Error (Anti-Macet):**  
  Aplikasi tidak akan lagi memunculkan kotak pesan error kecil (*pop-up error*) yang biasanya membuat aplikasi terhenti sendiri saat ditinggal semalaman. Semua kendala teknis akan dicatat rapi di latar belakang ke file laporan (*log*).
- **Penghematan Ruang Hard Disk:**  
  Ukuran penyimpanan file sementara (*cache*) browser Chrome dibatasi secara otomatis agar hard disk atau SSD komputer Anda tidak cepat penuh.
- **Aman Membaca Karakter Tanda Petik:**  
  Pesan pelanggan yang berisi tanda petik satu (seperti kata *"Jum'at"*, *"Don't"*, atau simbol kutip lainnya) kini diproses dengan lancar tanpa menyebabkan error pada database server.

---

## 📦 Versi 2.1.5.4
- Pembaruan komponen penghubung browser Chrome untuk mendukung pembaruan WhatsApp Web terkini.
- Penyesuaian kestabilan pembacaan format waktu dan riwayat chat.
