# SEMANTIC-HTML
Latihan Praktikum Semantic HTML
<br>NAMA : LISTRIA INDAH MAWARNI<br>
<br>NIM  : 2205101014<br>
<br>KELAS : 5B - TIF<br>

<br>##DOKUMEN INDEX HTML##<br>
<br>STRUKTUR DASAR<br>
<br>!DOCTYPE html: Mendefinisikan bahwa dokumen ini adalah dokumen HTML5<br>
<br>html lang="en": Menandakan bahwa dokumen menggunakan bahasa Inggris.<br>
<br>head: Berisi informasi metadata seperti karakter encoding, pengaturan tampilan responsif, judul halaman, dan referensi ke file CSS.<br>
<br>body: Berisi semua konten yang ditampilkan pada halaman web.<br>

<br>ELEMEN PADA HEAD<br>
<br>meta charset="UTF-8" /: Mengatur karakter encoding menjadi UTF-8, sehingga semua karakter (termasuk karakter khusus seperti simbol) dapat ditampilkan dengan benar.<br>
<br>meta name="viewport" content="width=device-width, initial-scale=1.0" /: Mengatur agar halaman terlihat responsif di berbagai perangkat, seperti desktop dan ponsel.<br>
<br>title: Memberikan judul pada halaman web yang akan tampil di tab browser.<br>
<br>link rel="stylesheet" href="./assets/styles/styles.css": Menghubungkan file CSS eksternal yang digunakan untuk mendesain halaman web.<br>

<br>ELEMEN PADA BODY<br>
<br>Header: Bagian header digunakan untuk menampilkan judul utama halaman, yaitu "HTML5 Semantic".<br>
<br>Navigation(Nav): Bagian ini adalah menu navigasi. Terdapat tautan ke berbagai bagian halaman:<br>
<br>#home: Menuju ke bagian "Home".<br>
<br>#pengertian: Menuju ke bagian "Pengertian".<br>
<br>#kesimpulan: Menuju ke bagian "Kesimpulan".<br>
<br>Section: Bagian ini adalah tempat untuk menyimpan konten utama. Namun, kontennya hanya berisi teks "Konten". Anda dapat memperluasnya dengan menambahkan elemen lain seperti paragraf, gambar, atau tabel.<br>
<br>Footer:Bagian footer biasanya digunakan untuk memberikan informasi hak cipta atau tautan tambahan seperti kebijakan privasi atau kontak.<br>

##KEKURANGAN ATAU PERBEDAANNYA##
<br>Pada Struktur dasarnya kurang lengkap. tidak ada html lang en, header dan body, itu mempengaruhi tampilan saat di RUN<br>
<br>Selain itu juga tidak ada "elemen pada head"<br>
<br>Bagian "section" hanya menampilkan teks "Konten". Sebaiknya diisi dengan deskripsi atau informasi tambahan.<br>

<br>##DOKUMEN STYLES CSS##<br>
<br>Header: Terletak di baris pertama, memanjang seluruh lebar halaman (100%).<br>
<br>Navigation: Terletak di sebelah kiri baris kedua (20% lebar).<br>
<br>Section (Konten Utama): Mengisi dua kolom sisanya di baris kedua.<br>

<br>BODY MENGATUR TATA LETAK DENGAN GRID<br>
<br>display: grid;: Mengaktifkan Grid Layout pada elemen body.<br>
<br>grid-template-areas: Menentukan nama-nama area grid untuk berbagai elemen:<br>
<br>"header header header": Baris pertama diisi oleh area bernama header, mencakup seluruh kolom.<br>
<br>"nav section section": Baris kedua diisi oleh area nav di kolom pertama, dan section di dua kolom berikutnya.<br>
<br>"footer footer footer": Baris ketiga diisi oleh area footer, mencakup seluruh kolom.<br>
<br>grid-template-rows: Menentukan tinggi masing-masing baris:<br>
<br>80px: Baris pertama (header) memiliki tinggi 80 piksel.<br>
<br>1fr: Baris kedua (konten) menyesuaikan ruang yang tersisa secara proporsional.<br>
<br>50px: Baris ketiga (footer) memiliki tinggi 50 piksel.<br>
<br>grid-template-columns: Menentukan lebar masing-masing kolom:<br>
<br>20%: Kolom pertama (nav) mengambil 20% lebar total.<br>
<br>1fr: Kolom kedua (konten utama) mengambil sisa ruang secara proporsional.<br>
<br>18%: Kolom ketiga (bagian tambahan) mengambil 18% lebar total.<br>
<br>grid-gap: 5px;: Menentukan jarak antar elemen grid.<br>
<br>height: 100vh;: Mengatur tinggi badan halaman untuk memenuhi seluruh tinggi viewport (layar pengguna).<br>
<br>Footer: Terletak di baris ketiga, memanjang seluruh lebar halaman.<br>

<br>ELEMEN LAINNYA<br>
<br>header<br>
<br>background: #707070;: Memberikan warna latar abu-abu gelap untuk header.<br>
<br>grid-area: header;: Menghubungkan elemen <header> dengan area grid bernama header.<br>
<br>text-align: center;: Mengatur teks header agar berada di tengah secara horizontal.<br>
<br>nav<br>
<br>background: #C9BFBF;: Memberikan warna latar abu-abu muda untuk navigasi.<br>
<br>grid-area: nav;: Menghubungkan elemen <nav> dengan area grid bernama nav.<br>
<br>section<br>
<br>background: #ABABAB;: Memberikan warna latar abu-abu medium untuk konten utama.<br>
<br>grid-area: section;: Menghubungkan elemen <section> dengan area grid bernama section.<br>
<br>footer<br>
<br>background: #707070;: Memberikan warna latar abu-abu gelap untuk footer.<br>
<br>grid-area: footer;: Menghubungkan elemen <footer> dengan area grid bernama footer.<br>
<br>font-size: small;: Mengatur ukuran teks footer menjadi kecil.<br>
<br>text-align: center;: Mengatur teks footer agar berada di tengah secara horizontal.<br>

<br>KEKURANGAN / KELEBIHAN ATAU PERBEDAANNYA<br>
<br>tag pada elemennya tidak berurutan membuat tata letak berantakan<br>
<br>untuk isi pada elemennya sudah sesuai<br>
<br>Responsif: Grid Layout memungkinkan halaman beradaptasi pada berbagai resolusi layar.<br>
<br>Struktur Rapi: Setiap elemen memiliki area yang jelas dan terdefinisi.<br>
<br>Mudah Dimodifikasi: Area dan ukuran dapat diatur ulang dengan mengubah properti Grid.<br>
