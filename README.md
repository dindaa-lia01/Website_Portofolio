<img width="678" height="137" alt="Screenshot 2026-02-28 054116" src="https://github.com/user-attachments/assets/3544a323-ff09-4244-b6fb-ebc41699c4ad" />Nama: Dinda Aulia Rizky

NIM: 2409116076

Kelas: B'24

# Website Portofolio

Web portofolio adalah situs web pribadi yang menampilkan informasi mengenai diri seseorang, seperti pengantar, pengalaman kerja, kemampuan, dan sertifikat yang pernah diperoleh. Web portofolio bisa dianggap seperti CV, hanya saja disajikan dalam bentuk website yang lebih menarik dan bisa berinteraksi. Di dalamnya, orang bisa melihat siapa kita, apa yang sudah kita kerjakan, dan kemampuan apa yang kita punya dengan tampilan yang lebih jelas dan lebih menarik. 

Web portofolio ini dibuat agar kita bisa memperkenalkan diri secara profesional, terutama saat sedang kuliah, mencari magang, atau melamar pekerjaan. Dengan membuat website portofolio, kita bisa menampilkan kemampuan dan pengalaman kita dengan cara yang lebih menarik dan terkini. Selain itu, web portofolio juga bisa digunakan untuk memperkuat citra diri agar terlihat lebih profesional dan siap dalam membangun karier.

# Tampilan Tiap Section

## 1. Home

   Bagian Home merupakan halaman utama yang berfungsi sebagai tampilan awal website. Pada bagian ini ditampilkan identitas singkat seperti nama, foto, dan tagline sebagai gambaran umum mengenai pemilik website.

   <img width="1889" height="1026" alt="image" src="https://github.com/user-attachments/assets/c266c953-8ee1-46a1-8605-2b4a246dbc6a" />
   
## 2. About Me

   Bagian About Me berisi penjelasan lebih lengkap mengenai profil diri, termasuk latar belakang, minat, serta kemampuan yang dimiliki. Tujuannya adalah untuk memberikan informasi yang lebih mendalam kepada pengunjung mengenai pribadi penulis. Selain itu, terdapat tombol navigasi “Explore More” yang berfungsi untuk mengarahkan pengunjung menuju bagian lain dari website.

   <img width="1842" height="763" alt="image" src="https://github.com/user-attachments/assets/e9aa8f8d-ad91-479c-ab20-8003d6d6b4ef" />

## 3. Experience

   Bagian Experience memuat berbagai pengalaman yang pernah diikuti, seperti kegiatan organisasi, kepanitiaan, maupun aktivitas lainnya. Bagian ini bertujuan untuk menunjukkan keterlibatan serta kemampuan dalam bekerja sama dan berkontribusi dalam suatu kegiatan.

   Pada bagian atas terdapat judul halaman serta tombol filter kategori yang memungkinkan pengguna memilih tampilan pengalaman berdasarkan klasifikasi tertentu.

  - Halaman Experience pada semua kategori:
   
    <img width="1867" height="1004" alt="image" src="https://github.com/user-attachments/assets/7f7d1350-c873-4e93-ad50-2120b8d7f06b" />

  - Halaman Experience pada kategori Campus:

    <img width="1772" height="714" alt="image" src="https://github.com/user-attachments/assets/bfa60338-7d76-4f38-9a1e-1dff95a284ec" />

  - Halaman Experience pada kategori School:

    <img width="1736" height="814" alt="image" src="https://github.com/user-attachments/assets/2fb8fa28-c106-4398-a1cb-840265c3c563" />

## 4. Certificates

   Bagian Certificates menampilkan sertifikat atau penghargaan yang pernah diperoleh. Hal ini berfungsi sebagai bukti partisipasi dan pengembangan kompetensi dalam berbagai bidang yang relevan. Sertifikat yang ditampilkan meliputi kegiatan seminar, kepanitiaan, pelatihan, serta kegiatan organisasi sekolah.
   
   - Halaman Certificates pada semua kategori:
   
     <img width="1799" height="984" alt="image" src="https://github.com/user-attachments/assets/3acfd130-a845-44f7-9a06-55e25073cfcf" />

   - Halaman Certificates pada Campus:

     <img width="1786" height="1038" alt="image" src="https://github.com/user-attachments/assets/e385ba20-4302-4ca5-a9c8-55b0c25ba08b" />

- Halaman Certificates pada School:

  <img width="1781" height="683" alt="image" src="https://github.com/user-attachments/assets/94c7203a-5ba3-4046-8a1b-d10b6558bf12" />

## 5. Contact

   Bagian Contact berisi informasi kontak seperti email dan media sosial yang dapat digunakan untuk menghubungi pemilik website. Bagian ini memudahkan pihak lain untuk menjalin komunikasi lebih lanjut.

   <img width="945" height="470" alt="image" src="https://github.com/user-attachments/assets/7c84fb63-032b-4613-b53e-ab088d942558" />

# Struktur Kode pada Setiap Section
```bash
WEB_PORTOFOLIO
├── assets => Folder untuk menyimpan file pendukung yakni gambar.
├── index.html => File utama yang berisi struktur halaman website.
└── style.css => File untuk mengatur tampilan dan desain website.
```

### **File index.html** merupakan struktur utama dari website portfolio yang berfungsi sebagai kerangka dasar dalam menampilkan seluruh konten. Pada file ini terdapat pembagian beberapa section yang mewakili fitur utama website, seperti halaman beranda, profil diri, pengalaman, sertifikat, hingga kontak.

1. Struktur Dasar HTML

   Bagian ini merupakan struktur dasar HTML.
   - <!DOCTYPE html> berfungsi untuk mendeklarasikan tipe dokumen HTML5.
   - meta viewport digunakan agar website responsif di berbagai ukuran layar.
   - Bootstrap CSS digunakan untuk mempermudah pembuatan layout dan komponen, sedangkan style.css berisi desain kustom.
   
   <img width="1054" height="312" alt="image" src="https://github.com/user-attachments/assets/72da37de-0b0b-4292-98d9-a28e11c0e89c" />

2. Navbar

   Navbar berfungsi sebagai menu navigasi untuk berpindah antar section.
   - Class navbar-expand-lg membuat navbar responsif.
   - fixed-top membuat navbar tetap berada di atas saat halaman di-scroll.
   - Link seperti href="#about" mengarahkan ke section tertentu dalam halaman.
   
   <img width="1022" height="439" alt="image" src="https://github.com/user-attachments/assets/8d2031af-1596-46f9-9b8b-119265dd4443" />

3. Home Section

   Bagian ini merupakan tampilan awal website (hero section). {{ name }} dan {{ tagline }} menggunakan Vue JS untuk menampilkan data secara dinamis dari bagian data().

   <img width="937" height="217" alt="image" src="https://github.com/user-attachments/assets/85f1fe3f-fcd5-414b-8888-4c901dd583ee" />

4. About Me Section

   Struktur Utama: Foto, deskripsi, skills.

   Pada foto pertama ditampilkan struktur dasar section About Me. Bagian ini menggunakan id="about" agar bisa dipanggil melalui navigasi, serta class Bootstrap seperti py-5, container, dan row untuk mengatur jarak dan tata letak agar responsif. Di dalamnya terdapat judul “About Me” yang dibuat rata tengah, serta kolom yang berisi foto profil.

   Gambar diambil dari folder assets dan menggunakan class img-fluid agar tampilannya menyesuaikan ukuran layar.

   <img width="626" height="372" alt="Screenshot 2026-02-28 050936" src="https://github.com/user-attachments/assets/f67012cf-5849-4c23-9e04-1bb6db341919" />

   Pada foto kedua ditampilkan bagian deskripsi, pengalaman, dan skills. Deskripsi menggunakan sintaks {{ description }} yang menunjukkan penggunaan Vue.js untuk menampilkan data secara dinamis.
   
  Bagian skills menggunakan v-for untuk menampilkan nama skill dan tingkat kemampuannya. Progress bar diatur secara dinamis melalui :style sehingga panjang bar sesuai dengan persentase kemampuan masing-masing skill.
   
   <img width="518" height="618" alt="Screenshot 2026-02-28 051037" src="https://github.com/user-attachments/assets/8e9f4dbf-a77f-4107-8332-973f73037d50" />

6. Experience Section

   Bagian ini menampilkan pengalaman organisasi atau kegiatan. Filter menggunakan @click untuk mengubah kategori. Data yang ditampilkan dikontrol oleh computed property filteredExperience() yang menyaring data berdasarkan kategori.

   <img width="636" height="772" alt="image" src="https://github.com/user-attachments/assets/0fbdcd94-9797-4ab6-a684-9977b83ae7ca" />

7. Certificates Section

   Section ini menampilkan daftar sertifikat. Struktur mirip dengan Experience, tetapi menggunakan data certificates. Filtering dilakukan melalui filteredCertificates().

   <img width="627" height="762" alt="image" src="https://github.com/user-attachments/assets/3384b5b8-52f4-4636-8212-bf66cc040cfa" />

8. Contact Section

   Bagian ini berisi informasi kontak.
   - mailto: digunakan untuk membuka email secara langsung.
   - target="_blank" membuat link Instagram terbuka di tab baru.

   <img width="834" height="481" alt="image" src="https://github.com/user-attachments/assets/c67e8b58-9e16-4910-bf3d-c0d65ed6a243" />

9. Vue JS (Data dan Logika)

   Bagian data() menyimpan seluruh informasi yang digunakan dalam website, seperti nama, pengalaman, sertifikat, dan skill. Vue membuat data ini bisa ditampilkan secara dinamis di HTML.

   <img width="213" height="191" alt="image" src="https://github.com/user-attachments/assets/dc06bae7-8baf-4ec6-a469-fb799100e736" />

11. Computed (Filter Logic)

    computed digunakan untuk memproses data sebelum ditampilkan. Fungsi ini menyaring data berdasarkan kategori yang dipilih.

    <img width="765" height="258" alt="image" src="https://github.com/user-attachments/assets/b5a3d25a-ac65-4665-84d7-fa0cc26662af" />

12. Animasi Scroll

    Script ini berfungsi untuk memberikan efek animasi saat halaman di-scroll. Ketika elemen masuk ke area layar, class show ditambahkan sehingga animasi muncul.

    <img width="644" height="386" alt="image" src="https://github.com/user-attachments/assets/4646b38b-6180-4c8b-9963-a5ed30ff340e" />

13. Footer

    Pada bagian pertama terdapat elemen <footer> yang berfungsi sebagai penutup halaman website. Footer menggunakan class Bootstrap seperti bg-dark, text-white, text-center, dan py-3 untuk memberikan latar belakang gelap, warna teks putih, posisi teks di tengah, serta padding vertikal. Di dalamnya terdapat tag <p> yang menampilkan copyright dan nama pemilik website.

    <img width="665" height="155" alt="image" src="https://github.com/user-attachments/assets/1e02b424-7f7f-4c51-9ec0-b2c69796005e" />


14. Bootstrap JS

    Selanjutnya terdapat pemanggilan Bootstrap JS melalui CDN. File ini berfungsi untuk mengaktifkan komponen interaktif Bootstrap seperti navbar toggle, dropdown, dan modal. Setelah itu terdapat pemanggilan Vue JS melalui CDN yang digunakan untuk mengelola data secara dinamis menggunakan reactive system dan data binding.

    <img width="994" height="73" alt="image" src="https://github.com/user-attachments/assets/e628ccaf-445c-4696-b41b-4a06a3f17dbc" />

15. Vue JS

    <img width="678" height="137" alt="Screenshot 2026-02-28 054116" src="https://github.com/user-attachments/assets/15a59287-7e4d-4ff6-a91f-f23d8f76f937" />

    Berfungsi untuk menghubungkan website dengan library Vue.js versi 3 melalui CDN. Pada bagian <script> dengan const { createApp } = Vue, kode ini digunakan untuk menginisialisasi aplikasi Vue agar data seperti description, experiences, dan skills dapat ditampilkan secara dinamis pada halaman.


### **File style.css** digunakan untuk mengatur tampilan dan desain website. CSS berfungsi memperindah halaman dengan mengatur warna, font, layout, animasi, serta efek seperti hover dan transisi. Pada project ini, style.css mengatur background animasi, tampilan navbar, hero section, gambar profil, progress bar, card, tombol, serta efek scroll agar website terlihat lebih modern dan menarik.



   

   



























    
