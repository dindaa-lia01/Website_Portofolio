Nama: Dinda Aulia Rizky

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

## **File index.html** 
=> merupakan struktur utama dari website portfolio yang berfungsi sebagai kerangka dasar dalam menampilkan seluruh konten. Pada file ini terdapat pembagian beberapa section yang mewakili fitur utama website, seperti halaman beranda, profil diri, pengalaman, sertifikat, hingga kontak.

### 1. Struktur Dasar HTML

   Bagian ini merupakan struktur dasar HTML.
   - <!DOCTYPE html> berfungsi untuk mendeklarasikan tipe dokumen HTML5.
   - meta viewport digunakan agar website responsif di berbagai ukuran layar.
   - Bootstrap CSS digunakan untuk mempermudah pembuatan layout dan komponen, sedangkan style.css berisi desain kustom.
   
   <img width="1054" height="312" alt="image" src="https://github.com/user-attachments/assets/72da37de-0b0b-4292-98d9-a28e11c0e89c" />

### 2. Navbar

   Navbar berfungsi sebagai menu navigasi untuk berpindah antar section.
   - Class navbar-expand-lg membuat navbar responsif.
   - fixed-top membuat navbar tetap berada di atas saat halaman di-scroll.
   - Link seperti href="#about" mengarahkan ke section tertentu dalam halaman.
   
   <img width="1022" height="439" alt="image" src="https://github.com/user-attachments/assets/8d2031af-1596-46f9-9b8b-119265dd4443" />

### 3. Home Section

   Bagian ini merupakan tampilan awal website (hero section). {{ name }} dan {{ tagline }} menggunakan Vue JS untuk menampilkan data secara dinamis dari bagian data().

   <img width="937" height="217" alt="image" src="https://github.com/user-attachments/assets/85f1fe3f-fcd5-414b-8888-4c901dd583ee" />

### 4. About Me Section

   Struktur Utama: Foto, deskripsi, skills.

   Pada foto pertama ditampilkan struktur dasar section About Me. Bagian ini menggunakan id="about" agar bisa dipanggil melalui navigasi, serta class Bootstrap seperti py-5, container, dan row untuk mengatur jarak dan tata letak agar responsif. Di dalamnya terdapat judul “About Me” yang dibuat rata tengah, serta kolom yang berisi foto profil.

   Gambar diambil dari folder assets dan menggunakan class img-fluid agar tampilannya menyesuaikan ukuran layar.

   <img width="626" height="372" alt="Screenshot 2026-02-28 050936" src="https://github.com/user-attachments/assets/f67012cf-5849-4c23-9e04-1bb6db341919" />

   Pada foto dibawah ini ditampilkan bagian deskripsi, pengalaman, dan skills. Deskripsi menggunakan sintaks {{ description }} yang menunjukkan penggunaan Vue.js untuk menampilkan data secara dinamis.
   
   Bagian skills menggunakan v-for untuk menampilkan nama skill dan tingkat kemampuannya. Progress bar diatur secara dinamis melalui :style sehingga panjang bar sesuai dengan persentase kemampuan masing-masing skill.
   
   <img width="518" height="618" alt="Screenshot 2026-02-28 051037" src="https://github.com/user-attachments/assets/8e9f4dbf-a77f-4107-8332-973f73037d50" />

### 5. Experience Section

   Bagian ini menampilkan pengalaman organisasi atau kegiatan. Filter menggunakan @click untuk mengubah kategori. Data yang ditampilkan dikontrol oleh computed property filteredExperience() yang menyaring data berdasarkan kategori.

   <img width="636" height="772" alt="image" src="https://github.com/user-attachments/assets/0fbdcd94-9797-4ab6-a684-9977b83ae7ca" />

### 6. Certificates Section

   Section ini menampilkan daftar sertifikat. Struktur mirip dengan Experience, tetapi menggunakan data certificates. Filtering dilakukan melalui filteredCertificates().

   <img width="627" height="762" alt="image" src="https://github.com/user-attachments/assets/3384b5b8-52f4-4636-8212-bf66cc040cfa" />

### 7. Contact Section

   Bagian ini berisi informasi kontak.
   - mailto: digunakan untuk membuka email secara langsung.
   - target="_blank" membuat link Instagram terbuka di tab baru.

   <img width="834" height="481" alt="image" src="https://github.com/user-attachments/assets/c67e8b58-9e16-4910-bf3d-c0d65ed6a243" />

### 8. Vue JS (Data dan Logika)

   Bagian data() menyimpan seluruh informasi yang digunakan dalam website, seperti nama, pengalaman, sertifikat, dan skill. Vue membuat data ini bisa ditampilkan secara dinamis di HTML.

   <img width="213" height="191" alt="image" src="https://github.com/user-attachments/assets/dc06bae7-8baf-4ec6-a469-fb799100e736" />

### 9. Computed (Filter Logic)

   Computed digunakan untuk memproses data sebelum ditampilkan. Fungsi ini menyaring data berdasarkan kategori yang dipilih.

   <img width="765" height="258" alt="image" src="https://github.com/user-attachments/assets/b5a3d25a-ac65-4665-84d7-fa0cc26662af" />

### 10. Animasi Scroll

   Script ini berfungsi untuk memberikan efek animasi saat halaman di-scroll. Ketika elemen masuk ke area layar, class show ditambahkan sehingga animasi muncul.

  <img width="644" height="386" alt="image" src="https://github.com/user-attachments/assets/4646b38b-6180-4c8b-9963-a5ed30ff340e" />

### 11. Footer

   Pada bagian pertama terdapat elemen _footer_ yang berfungsi sebagai penutup halaman website. Footer menggunakan class Bootstrap seperti bg-dark, text-center, dan py-3 untuk memberikan latar belakang gelap, warna teks putih, posisi teks di tengah, serta padding vertikal. Di dalamnya terdapat tag _p_ yang menampilkan copyright dan nama pemilik website.
   
   <img width="665" height="155" alt="image" src="https://github.com/user-attachments/assets/1e02b424-7f7f-4c51-9ec0-b2c69796005e" />

### 12. Bootstrap JS

   Terdapat pemanggilan Bootstrap JS melalui CDN. File ini berfungsi untuk mengaktifkan komponen interaktif Bootstrap seperti navbar toggle, dropdown, dan modal. Setelah itu terdapat pemanggilan Vue JS melalui CDN yang digunakan untuk mengelola data secara dinamis menggunakan reactive system dan data binding.

   <img width="994" height="73" alt="image" src="https://github.com/user-attachments/assets/e628ccaf-445c-4696-b41b-4a06a3f17dbc" />

### 13. Vue JS

   Berfungsi untuk menghubungkan website dengan library Vue.js versi 3 melalui CDN. Pada bagian <script> dengan const { createApp } = Vue, kode ini digunakan untuk menginisialisasi aplikasi Vue agar data seperti description, experiences, dan skills dapat ditampilkan secara dinamis pada halaman.
    
   <img width="678" height="137" alt="Screenshot 2026-02-28 054116" src="https://github.com/user-attachments/assets/15a59287-7e4d-4ff6-a91f-f23d8f76f937" />

## **File style.css** 
=> Digunakan untuk mengatur tampilan dan desain website. CSS berfungsi memperindah halaman dengan mengatur warna, font, layout, animasi, serta efek seperti hover dan transisi. Pada project ini, style.css mengatur background animasi, tampilan navbar, hero section, gambar profil, progress bar, card, tombol, serta efek scroll agar website terlihat lebih modern dan menarik.

### 1. Google Font

   Bagian ini mengimpor font Poppins dari Google Fonts. Font ini digunakan sebagai font utama agar tampilan website terlihat modern dan konsisten.

   <img width="955" height="114" alt="image" src="https://github.com/user-attachments/assets/c7afa1af-fd86-4259-b035-2ae0f03c0719" />

### 2. Global Style

   Bagian global mengatur tampilan dasar seluruh halaman. Background menggunakan animasi gradasi warna dengan @keyframes gradientMove, sehingga latar belakang terlihat bergerak secara halus. Selain itu, diatur juga warna teks utama menjadi putih, scroll menjadi smooth, dan mencegah overflow horizontal. Fungsinya adalah memberikan identitas visual utama pada website.

   <img width="811" height="308" alt="image" src="https://github.com/user-attachments/assets/a9b6f6b8-f200-4b5b-a237-0efcb18f09f8" />

### 3. Navbar

   Bagian navbar mengatur tampilan menu navigasi. Background dibuat transparan dengan efek blur (glassmorphism). Warna teks diberi efek neon biru dan memiliki efek hover. Fungsinya untuk memperjelas navigasi dan memberikan kesan modern.

   <img width="472" height="561" alt="image" src="https://github.com/user-attachments/assets/739c1be0-3f2e-4fcb-a196-88dfe1590d9b" />

### 4. Hero Section

   Hero section mengatur tampilan halaman pertama yang memenuhi tinggi layar (100vh). Konten dibuat berada di tengah secara vertikal dan horizontal. Fungsinya untuk memberikan kesan pertama yang menarik saat website dibuka.

   <img width="393" height="504" alt="image" src="https://github.com/user-attachments/assets/a547d83b-e50a-40b0-bcba-9818be4c032a" />

### 5. Section Title

   Mengatur tampilan semua tag h2 agar memiliki warna dan efek glow yang konsisten. Fungsinya untuk menjaga keseragaman desain antar section.

   <img width="384" height="192" alt="image" src="https://github.com/user-attachments/assets/b91088c6-e80c-4d53-abc2-af97adcc2ca9" />

### 6. Progress Bar (Skills)

   Bagian ini mengatur tampilan progress bar pada section skills. Warna background dibuat gelap, sedangkan bagian progress menggunakan warna biru neon. Fungsinya untuk menampilkan tingkat kemampuan secara visual.

   <img width="398" height="356" alt="image" src="https://github.com/user-attachments/assets/918eacfc-d1d6-4a2f-8e48-31d4f3ba782c" />

### 7. Card (Experience & Certificate)

   Mengatur tampilan card agar memiliki sudut melengkung, efek bayangan, dan animasi saat hover. Fungsinya untuk membuat tampilan pengalaman dan sertifikat lebih interaktif dan tidak monoton.

   <img width="568" height="348" alt="image" src="https://github.com/user-attachments/assets/25e768e3-f4f5-4b61-ab30-31efc7aa45ca" />

### 8. Image Experience & Certificate

   Mengatur ukuran dan tampilan gambar agar proporsional serta tidak terdistorsi. Fungsinya agar gambar tetap rapi dan responsif.

   <img width="308" height="237" alt="image" src="https://github.com/user-attachments/assets/b842ad0c-bfed-47be-a1b9-90b1ed42966e" />

   <img width="312" height="234" alt="image" src="https://github.com/user-attachments/assets/9673b2eb-89ba-4cb4-9671-ae978f045d78" />

### 9. Contact Link

   Mengatur tampilan link pada bagian contact agar tidak memiliki underline dan memiliki warna khusus. Fungsinya untuk memperjelas informasi kontak.

   <img width="289" height="208" alt="image" src="https://github.com/user-attachments/assets/8a60274d-dca3-41f6-af4a-201cdfd8338b" />

### 10. Button

   Mengatur tampilan tombol utama dengan warna neon biru serta efek hover transparan. Fungsinya untuk meningkatkan interaktivitas pengguna.

   <img width="360" height="423" alt="image" src="https://github.com/user-attachments/assets/6abc4dd7-0d97-4817-a8c5-b46f0d430eab" />

### 11. Section Background Custom

   Memberikan background khusus pada section experience dan contact dengan efek blur dan border transparan. Fungsinya untuk membedakan section dari background utama.

   <img width="412" height="251" alt="image" src="https://github.com/user-attachments/assets/47dca067-4f44-4689-ae79-59440244508c" />

### 12. Filter Button Active

   Mengatur tampilan tombol filter yang sedang aktif agar terlihat menonjol. Fungsinya untuk memberikan feedback visual kepada pengguna.

   <img width="353" height="207" alt="image" src="https://github.com/user-attachments/assets/f976ff84-a1de-40ad-ae5d-5d359f4acefe" />

### 13. Scroll Animation

   Mengatur animasi saat section muncul ketika discroll. Awalnya elemen tidak terlihat, kemudian muncul dengan efek fade dan slide. Fungsinya untuk meningkatkan pengalaman visual pengguna.

   <img width="423" height="373" alt="image" src="https://github.com/user-attachments/assets/5b3c776b-205b-4f8b-8a2b-550fd88a9e8a" />

### 14. About Image Style

   Mengatur tampilan foto pada section About agar memiliki frame gradasi dan efek zoom. Fungsinya untuk memperindah tampilan bagian profil.

   <img width="605" height="568" alt="image" src="https://github.com/user-attachments/assets/ccdab388-9df5-4a2d-b81f-c0249a3aa13b" />



























    
