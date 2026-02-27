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

File index.html merupakan struktur utama dari website portfolio yang berfungsi sebagai kerangka dasar dalam menampilkan seluruh konten. Pada file ini terdapat pembagian beberapa section yang mewakili fitur utama website, seperti halaman beranda, profil diri, pengalaman, sertifikat, hingga kontak.

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

   Section ini menjelaskan profil diri.
   - v-for digunakan untuk menampilkan daftar skill secara otomatis berdasarkan data array.
   - :style (v-bind) digunakan untuk mengatur lebar progress bar sesuai persentase skill.

   

   



























    
