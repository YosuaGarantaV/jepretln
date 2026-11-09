# Jepret: Toko Daring Perlengkapan Kamera dan Elektronik

Proyek kelompok: aplikasi web PHP berpola MVC tanpa framework, dengan halaman toko untuk pembeli dan panel admin untuk pengelola.

## Fitur

- Katalog delapan kategori produk: action cam, DSLR, mirrorless, lensa, drone, laptop, LED TV, dan aksesoris.
- Akun pengguna: registrasi, login, profil, edit profil, dan ganti password.
- Panel admin dengan 11 modul: produk, kategori, merek, kupon, lokasi, pembayaran, pesanan, pengguna, staf, FAQ, dan laporan kinerja.
- Halaman informasi: FAQ, syarat dan ketentuan, kebijakan privasi, kebijakan pengembalian, dan tentang kami.

## Teknologi

- PHP dengan PDO ke MySQL.
- Inti MVC: `App` (router), `Controller`, `Database`, dan `Flasher` di `app/Core/`.
- Tailwind CSS 4 dan komponen Flowbite.
- JavaScript untuk validasi registrasi, tampil/sembunyi password, dan sidebar admin.

## Tim dan kontribusi

Dikerjakan berempat: WirawanAri1405, Andri Laksono, Bedi002, dan Yosua Aldrin Garanta.

Bagian yang saya kerjakan:

- Halaman informasi pengguna: FAQ, syarat dan ketentuan, kebijakan privasi, kebijakan pengembalian, dan tentang kami (controller, view, CSS, dan JavaScript).
- Footer situs dan aset logo dalam tiga varian warna.
- Navbar dan sidebar panel admin, serta perbaikan alur login admin.

## Menjalankan dengan XAMPP

1. Salin folder ini ke `htdocs/jepretln`.
2. Buat database MySQL bernama `jepretln`. Skema database belum disertakan di repositori ini.
3. Sesuaikan koneksi di `app/config/config.php`.
4. Jalankan Apache dan MySQL, lalu buka `http://localhost/jepretln/public`.
5. CSS hasil build (`public/css/output.css`) sudah ada. Untuk mengubah gaya, jalankan `npm install` lalu `npm run dev`.
