# Lab2web
<img width="1920" height="1080" alt="Screenshot (29)" src="https://github.com/user-attachments/assets/fdd0b602-3f43-4452-844b-622258a77a51" />

1. Tampilan Awal (Tanpa CSS)
Pada tahap ini, halaman HTML hanya menampilkan teks dengan gaya default browser. Heading (h1) tampil besar, paragraf rata kiri, dan link berwarna biru dengan garis bawah.
 Artinya: belum ada CSS yang diterapkan.

<img width="1920" height="1080" alt="Screenshot (30)" src="https://github.com/user-attachments/assets/59945a3a-67ee-464a-8d53-360471dbee53" />

2. Struktur HTML Dasar
File HTML sudah berisi heading (h1), paragraf (p), dan link (a), tetapi tampilannya masih polos.
Tujuan: memastikan struktur HTML benar sebelum diberi styling.

<img width="1920" height="1080" alt="Screenshot (31)" src="https://github.com/user-attachments/assets/714aafd4-d8f3-4c7e-86f6-7f061e027556" />

3. Internal CSS

CSS mulai ditambahkan dengan tag (style) di dalam file HTML.
Perubahan yang terlihat:

Heading berubah warna dan posisi.

Ada garis horizontal.

Paragraf menggunakan warna teks yang berbeda.

Artinya: Internal CSS berhasil bekerja, memodifikasi elemen langsung dari file HTML.


<img width="1920" height="1080" alt="Screenshot (33)" src="https://github.com/user-attachments/assets/363f2490-62cc-4678-92be-4cbda481b08b" />

4. Eksternal CSS
Selanjutnya, file CSS eksternal dihubungkan dengan HTML menggunakan:
<img width="709" height="88" alt="Screenshot 2025-09-30 002935" src="https://github.com/user-attachments/assets/e782c308-0faf-4b0f-872c-ea1b335940fc" />
Perubahan yang terlihat:

Navigation bar hijau muncul di bagian atas.

Heading berada di tengah.

Paragraf lebih rapi dan warnanya berbeda.
 Artinya: CSS eksternal lebih fleksibel karena dipisahkan dari HTML, sehingga mudah dipelihara.

<img width="1920" height="1080" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/f3de6502-dfc5-4b3f-b22d-b4132b2aa6a5" />


5. Tampilan Akhir (Eksternal CSS + Styling Lanjutan)

Tampilan akhir sudah lebih menarik:

Background berwarna biru/teal pada bagian hero.

Heading putih besar dengan teks terpusat.

Paragraf dengan opacity sehingga lebih lembut.

Tombol/link merah dengan styling seperti button.

Layout lebih rapi dan terstruktur.
 Artinya: penggunaan kombinasi selector elemen, class, dan ID berhasil.
Prioritas CSS juga bisa diuji:

Inline CSS ) Internal CSS ) Eksternal CSS.

Selector ID lebih kuat daripada Class, sedangkan Class lebih kuat daripada selector elemen.

<img width="1920" height="1080" alt="Screenshot (35)" src="https://github.com/user-attachments/assets/b9451a6f-2a2d-4e2d-81b7-175889744c7e" />

6. Kesimpulan

Dari eksperimen ini:

CSS bisa ditulis dalam tiga cara: inline, internal, eksternal.

Selector h1 {...} berlaku untuk semua elemen (h1), sedangkan #intro h1 {...} hanya berlaku untuk (h1) yang berada di dalam elemen dengan ID intro.

Jika ada konflik styling: inline ) internal ) eksternal.

Jika sebuah elemen memiliki ID dan Class, maka deklarasi dengan ID akan ditampilkan karena lebih spesifik.











