# Pertemuan-03: HTML Form dan CSS Dasar (Tugas section#contact)

Dokumentasi Capaian Pembelajaran Pertemuan-03  
Mata Kuliah: **Pemrograman Web Dasar**  
Nama Mahasiswa: **Anggi Kharisma**  
NIM: **2611500058**  
Kelompok: **TI1J**  
Tahun Ajaran: **2026/2027 Gasal**  

---

## 🎯 Capaian Pembelajaran & Dokumentasi Tugas Pertemuan 3

Pada pertemuan ketiga, dilakukan pembelajaran elemen formulir HTML serta penataan gaya (*styling*) CSS dasar untuk menyelesaikan tugas pada modul:

### 1. Materi Pokok:
* **HTML Form Elements:**
  * Tag `<form>`, atribut `action`, `method`, `autocomplete`.
  * Elemen `<input>` (type text, email), `<textarea>`, serta tombol `<button>` (submit dan reset).
  * Penggunaan elemen `<label>` yang membungkus teks `<span>` dan elemen input demi aksesibilitas dan kemudahan penataan layout.

* **CSS Dasar & Groups Selector:**
  * Penerapan Flexbox (`display: flex`) untuk menyelaraskan label dan input secara rapi.
  * *Group Selector* antara `#about strong` dan `#contact label > span` untuk menjaga konsistensi lebar kolom label (`min-width: 180px`, teks rata kanan, padding).
  * Penataan gaya input dan textarea agar responsif (`flex: 1`, border tipis, padding, transisi halus pada saat focus).

* **Interaksi Tombol (Micro-interaction):**
  * Efek visual saat kursor mengarah ke tombol (`:hover`) menggunakan `transform: translateY(-1px)` dan bayangan (`box-shadow`).

* **Desain Responsif (Mobile Friendly):**
  * Penggunaan media query `@media (max-width: 600px)` untuk mengubah arah flexbox dari horizontal menjadi vertikal (`flex-direction: column`) saat dibuka di layar smartphone/ponsel.

---
*Hasil implementasi tugas dapat diuji langsung pada [`index.html`](./index.html)*
