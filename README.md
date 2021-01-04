# :bulb: Sistem Pendukung Keputusan

Repository ini berisi projek aplikasi berbasis web yang menerapkan beberapa metode dalam SPK menggunakan bahasa pemrograman javascript. [Klik disini](...) untuk melihat demo aplikasi.

## :books: Prasyarat

Sebelum memulai, pastikan telah terinstall beberapa tools:
* Web browser.
* Text editor.

## :cd: Menginstall Aplikasi

Untuk menginstall aplikasi ini, ikuti langkah berikut:

```sh
# clone this repository
git clone ...

# change working directory
cd ...
```

## :open_file_folder: Struktur Projek

```text
├── css
	├── atlantis.min.css
	├── bootstrap.min.css
	└── custom.css
├── img
	├── bg-math.png
	├── icon.ico
	├── logo-secondary.png
	└── logo-white.png
├── js
	├── atlantis.min.js
	├── bootstrap.min.js
	├── fontawesome.min.js
	├── jquery.min.js
	├── listener.js
	├── popper.min.js
	└── solver.js.js
├── index.html
└── sw.js
```

>Note: file `sw.js` berisi service worker yang dapat diaktifkan di file `listener.js`.

## :computer: Menjalankan Aplikasi

Untuk menjalankan aplikasi ini, ada beberapa opsi yang dapat dilakukan:
* Menjalankan aplikasi menggunakan php server. Jalankan perintah `php -S localhost:8000` lalu buka [web browser](http://localhost:8000).
* Buka file `index.html` .
>Note: Menjalankan aplikasi hanya dengan membuka file `index.html` tidak dapat mengaktifkan service worker.

## :loudspeaker: Lisensi

Aplikasi ini dibawah lisensi [MIT License](...).
