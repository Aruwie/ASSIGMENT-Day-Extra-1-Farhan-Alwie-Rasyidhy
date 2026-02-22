ACCESSIBILITY COMPARISON – BAD UI vs GOOD UI


BAD UI:

- Menggunakan <div> untuk struktur tanpa makna semantik.

- Judul “Login Page” hanya berupa teks dalam <div>, bukan heading (<h1>, <h2>, dll).

- Struktur tidak memiliki Jarak membuat susah dibaca dan gampang salah tekan

- Tidak menggunakan <label> untuk input.

- Menggunakan placeholder sebagai pengganti label.

- Placeholder akan hilang saat pengguna mengetik.

- Menggunakan <div> dengan atribut onclick sebagai tombol.

- Tidak dapat diakses dengan keyboard (tidak bisa ditekan dengan Enter/Space secara default).

- Tidak memiliki peran (role) yang jelas.

- Gambar tidak memiliki atribut alt.


GOOD UI:

- Menggunakan struktur semantik seperti <header>, <main>, dan <form>.

- Judul halaman menggunakan heading (<h1>, <h2>, <h3>) secara terstruktur.

- Struktur memiliki Jarak agar lebih mudah dipahami dan tidak akan salah tekan.

- Setiap input memiliki <label> yang terhubung dengan atribut for dan id.

- Placeholder hanya sebagai bantuan tambahan, bukan pengganti label.

- Menggunakan atribut required untuk validasi dasar.

- Menggunakan elemen <button>.

- Secara otomatis mendukung navigasi keyboard.

- Sudah memiliki behavior dan aksesibilitas bawaan browser.

- Gambar memiliki atribut alt yang deskriptif: "Foto profil pengguna".

- Informasi gambar dapat dipahami oleh pengguna tunanetra.



