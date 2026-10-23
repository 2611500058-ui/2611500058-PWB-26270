P5 - JavaScript Dasar, DOM, Event, dan Validasi Sisi Klien
Deskripsi:Dokumentasi pengembangan halaman profil mahasiswa pada P5. Di tahap ini halaman yang tadinya hanya HTML dan CSS ditambah JavaScript, lalu dilatih cara memilih elemen, membaca isi formulir, mengubah teks, mengatur class, dan menangani event klik pada tombol navigasi.

Dokumentasi pengembangan halaman web pada P5, meliputi JavaScript, DOM, event listener, interaksi
navigasi, dan validasi formulir sisi klien.

Fitur dan Pengembangan
hubungkan JS ekesternal: menghubungkan index.html dengan script.js eksternal menggunakan <script.js"></script> dan verifikasi via console
Tambah id pada menu navigasi: elemen <ul> menu diberi id="navMenu". Sebelumnya document.getElementById("navMenu") hasilnya null karena id-nya belum ada.
Memilih elemen: latihan getElementById(), querySelector(), dan querySelectorAll().
Membaca nilai formulir: latihan membaca isi kolom nama, email, dan semester dengan .value.
Mengubah teks: latihan mengubah dan menghapus teks pada elemen formFeedback dengan textContent.
Mengatur class: latihan classList.contains() dan classList.toggle() pada elemen navMenu

Pengujian
verifikasi koneksi JS: membuka console didevtoals munculpesan "script.js berhasil dijalankan."

getElementById navMenu: ketik document.getElementById("navMenu"); awalnya hasilnya null karena menu belum punya id, setelah id ditambah di index.html muncul <ul id="navMenu">.

querySelector radio button: ketik document.querySelector('input[name="jenis_pesan"]:checked'); hasilnya null kalau belum ada yang dipilih, kalau sudah memilih muncul elemen <input> radio yang dipilih.

querySelectorAll checkbox: ketik document.querySelectorAll('input[name="minat"]:checked'); hasilnya NodeList kalau belum ada yang dicentang, kalau sudah dicentang muncul NodeList berisi checkbox yang dicentang (jumlahnya sesuai yang dicentang).

value formulir: ketik document.getElementById("nama").value; (sama untuk email dan semester), hasilnya '' kalau masih kosong, setelah diisi muncul 'Anggi kharisma', '2611500058@mahasiswa.atamaluhur.ac.id', dan '1' (semester berupa teks, bukan angka).

textContent formFeedback: ketik document.getElementById("formFeedback").textContent = "Pesan pengujian DOM."; lalu textContent = ""; hasilnya teks "Pesan pengujian DOM." muncul di halaman, lalu hilang setelah diisi string kosong.

classList navMenu: ketik navMenu.classList.contains("nav-open"); lalu navMenu.classList.toggle("nav-open"); hasil toggle pertama true artinya class nav-open ditambah, tampilan menunya berubah, lalu halaman di-refresh biar balik seperti awal.

Riwayat Pengembangan
Catat perkembangan melalui commit Git yang bermakna.
[Pesan commit]: ["Hubungkan JavaScript eksternal ke HTML"]
[Pesan commit]: [Ringkasan perubahan dan hasil pengujiannya.]
[Pesan commit]: ["menggabungkan perubahan dari GitHub dan menambahkan id navMenu pada navigasi"]
[Pesan commit]: ["menguji querySelector dan querySelectorAll untuk memilih radio button dan checkbox"]
[Pesan commit]: ["mendokumentasikan hasil uji value, textContent, dan classList"]
