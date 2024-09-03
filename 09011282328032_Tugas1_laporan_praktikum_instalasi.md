<h1>LAPORAN PRAKTIKUM INSTALASI LINUX (UBUNTU)</h1>

<H2>BAB I Pendahuluan</H1>

<H3>1.1 Latar Belakang</H3>
<p >Dalam perkembanga era digital saat ini, Sistem Operasi menjadi komponen utama yang memungkinkan perangkat keras komputer menjalankan berbagai aplikasi dan fungsi. Sistem operasi adalah seperangkat program terstruktur yang mengelola sumber daya perangkat keras (Hardware) dan menyediakan layanan umum untuk aplikasi perangkat lunak (software). Sehingga Sistem operasi merupakan hal yang paling penting dari perangkat lunak dalam sistem komputer. Sistem operasi memiliki jenis jenis antara lain Linux,Windows,Android,dll. Di antara berbagai sistem operasi yang ada, Linux adalah salah satu jenis sistem operasi yang paling populer. Versi Linux pada saat ini terkenal dengan kestabilannya, keamanan, dan sifatnya yang open-source, dimana pengguna memiliki kebebasan untuk mengubah dan mendistribusikan kode sumber sesuai dengan kebutuhan.</p>
Instalasi sistem operasi adalah langkah penting yang harus dikuasai oleh setiap individu yang terlibat dalam teknologi informasi. Proses ini tidak hanya melibatkan pemasangan sistem operasi, tetapi juga pemahaman mengenai struktur sistem, manajemen partisi, dan konfigurasi awal yang diperlukan agar sistem dapat berjalan dengan optimal. Dengan memahami proses instalasi Linux, pengguna dapat mengatur dan memelihara server, mengembangkan aplikasi, atau bahkan menyesuaikan sistem operasi sesuai kebutuhan spesifik. <p/>

 <H3>1.2 Tujuan</H3>
1.	Mengetahui Prosedur instalasi pada sistem operasi linux <br/>
2.	Mampu menjalankan instalasi melalui Graphic User Interface (GUI) maupun Command Line Linux<br/>
3.	Mampu menganalisis proses instalasi.<br/>

<h3>1.3 Alat dan Bahan</h3>
1.	Laptop<br/>
2.	Ubuntu 24.04 LTS<br/>
3.	Virtual Box<br/>

<h3>1.4 Dasar Teori</h3>
Sistem operasi adalahLinux merupakan jenis sistem operasi berbasis UNIX yang open-source. Manfaat dalam penggunaan Linux adalah dalam keamanan Linux memiliki sistem izin yang ketat dan sering dianggap lebih aman dibandingkan sistem operasi lainnya. Selain itu, Linux juga memiliki kestabilan yang baik dan jarang mengalami crash, sehingga sering digunakan pada server yang memerlukan uptime tinggi. Linux juga memiliki kode sumber yang terbuka, yang memungkinkan pengembang untuk memodifikasi dan mendistribusi ulang sistem sesuai dengan kebutuhan. Terdapat banyak distribusi (distro) Linux yaitu Ubuntu,Debian,Fedora, dan CentOS yang dimana masing – masing memiliki kelebihan dan fitur khususus. Dengan demikian, dalam instalasi Linux dapat dilakukan dengan mesin virtual maupun perangkat keras secara langsung.<p/>

<h2> BAB II Pembahasan</h2>
<h3>2.1 Proses Instalasi</h3>
<p> 1.	Download ISO file distribusi Linux yaitu Ubuntu 24.04 LTS dari situs resmi. </p>
<p>2.	Dalam installasi Linux ini saya menggunakan dual boot, yang dimana kita menggunakan perangkat lunak rufus untuk membuat USB bootable dengan ISO Linux yaitu Ubuntu yang telah di unduh. </p>
<p>3.	Lakukan partisi Disk pada Windows pada disk management, kemudian restart komputer dan masuk ke BIOS dengan menekan tombol F2 selama proses booting, lalu simpan pengaturan BIOS dan reboot. Setelah itu komputer akan boot dari USB Linux</p>
4.	Setelah booting dari USB akan muncul antarmuka instalasi Linux seperti berikut ini<p/><p/>
<img src ="https://github.com/user-attachments/assets/19afcafe-4823-4f9f-8fea-8a64e3b00a36"width=500/><p/>
5.	Kita pilih bahasa yang akan digunakan lalu lanjutkan<p/>
<img src="https://github.com/user-attachments/assets/53bed407-8e56-4116-b2ba-f8b530fdb475"width=500/><p/>
6.	Pada bagian ini kita klik next<p/>
 <img src="https://github.com/user-attachments/assets/58218cc8-7f70-4a37-99bf-4c4d7340e597"width=500/><p/>
7.	Kita pilih keyboard layout lalu klik next<p/>
  <img src="https://github.com/user-attachments/assets/cd6785cb-c68a-4ef1-a6ee-2ff801f3aa42"width=500/><p/>
8.	Pilih koneksi internet seperti pada gambar berikut lalu klik next<p/>
  <img src="https://github.com/user-attachments/assets/9b91a0fd-04f3-4cc2-884f-1541be8e0f9e"width=500/><p/>
9.	Pada bagian ini kita klik skip<p/>
  <img src="https://github.com/user-attachments/assets/7f3ae2c8-8af3-4b48-9915-230f4dd74442"width=500/><p/>
10.	Kita install ubuntu lalu klik next<p/>
  <img src="https://github.com/user-attachments/assets/c2f431ce-30ae-4c06-b4fe-5d63f268179b"width=500/><p/>
11.	Pada bagian ini kiita pilih interactive installation lalu klik next<p/>
   <img src="https://github.com/user-attachments/assets/03f02cc9-f77c-43cb-9905-c0a22e125508"width=500/><p/>
12.	Selanjutnya pada bagian ini kita pilih default selection kemudian klik next<p/>
  <img src="https://github.com/user-attachments/assets/77a4f82e-0d30-48d3-a42e-3ccfa4809c99"width=500/><p/>
13.	Kita centang kedua pilihan pada proprietary software installation lalu next<p/>
  <img src="https://github.com/user-attachments/assets/1a324ba5-3eae-4a73-ac96-64c705ad1933"width=500/><p/>
14.	Pada bagian ini kita pilih seperti gambar berikut lalu klik next<p/>
 <img src="https://github.com/user-attachments/assets/79e27541-2a9b-4967-ab37-8baa7f9d8e70"width=500/><p/>
15.	Selanjutnya pada bagian ini kita membuat akun dan kata sandi selanjutnya klik next<p/>
  <img src="https://github.com/user-attachments/assets/b5740412-30a1-413f-a53a-683359e11ef2"width=500/><p/>
16.	Kita pilih timezone Lokasi pada saat ini kemudian next<p/>
  <img src="https://github.com/user-attachments/assets/d738ad61-bdc9-4d7c-b70a-1c9184ccc5fe"width=500/><p/>
17.	Berikut ini masuk pada bagian intallasi klik install dan tunggu beberapa saat.<p/>
  <img src="https://github.com/user-attachments/assets/ff790a0c-af40-4fd5-be51-388ec0506697"width=500/><p/>
18.	Setelah selesai proses installasi kita restart dan masuk dengan menggunakan kata sandi yang telah dibuat sebelumnya<p/>
  <img src="https://github.com/user-attachments/assets/b24b7a24-8cc6-4ec8-b08f-1bfe2d3523ff"width=500/><p/>
19.	Dan berikut ini tampilan dari menu desktop Linux yang telah diinstal<p/>
 <img src="https://github.com/user-attachments/assets/fe6ed188-ea29-4d58-9799-59db2d1e6861"width=500/><p/>

 <h3>2.2  Kenapa saat instalasi perlu dipilih “/” pada opsi Mount Point ?</h3>
Saat instalasi Ubuntu Linux, memilih "/" sebagai mount point menentukan bahwa partisi tersebut akan digunakan sebagai direktori root, yang merupakan pusat dari seluruh struktur sistem file. Ini sangat penting karena semua file sistem dan direktori utama berada di bawah root. Tanpa mount point ini, sistem tidak akan dapat mengakses file penting untuk booting dan operasi normal.

<h3>2.3 Penjelasan tentang ext4, ext3, swap, ntfs, fat32,btrfs</h3>
<b>1. ext4 (Fourth Extended Filesystem)</b><br/>
ext4 adalah penerus dari ext3 dan merupakan sistem file default di banyak distribusi Linux. Dibandingkan dengan ext3, ext4 memiliki dukungan untuk volume yang lebih besar, alokasi yang lebih cepat, dan efisiensi yang lebih baik dalam manajemen file kecil.<br/>
<b>2. ext3 (Third Extended Filesystem)</b><br/>
ext3 adalah versi sebelumnya dari ext4 dan juga mendukung journaling, yang membantu memulihkan data dengan cepat setelah kegagalan sistem. Sistem file ini kompatibel dengan ext2.<br/>
<b>3. Swap</b><br/>
Swap bukanlah sistem file, melainkan partisi khusus yang digunakan sebagai memori virtual. Ketika RAM penuh, sistem akan menggunakan swap untuk menyimpan data sementara, memungkinkan operasi sistem tetap berjalan.<br/>
<b>4. NTFS (New Technology File System)</b><br/>
NTFS adalah sistem file yang dikembangkan oleh Microsoft untuk sistem operasi Windows. NTFS mendukung ukuran file besar dan berbagai fitur keamanan seperti izin file dan enkripsi.<br/>
<b>5. FAT32 (File Allocation Table 32)</b><br/>
 FAT32 adalah sistem file yang lebih tua dan kompatibel dengan hampir semua sistem operasi. Namun, FAT32 memiliki batasan ukuran file hingga 4 GB dan volume hingga 8 TB.<br/>
<b>6. Btrfs (B-Tree File System)</b><br/>
Btrfs adalah sistem file modern yang dikembangkan untuk Linux dengan fokus pada toleransi kesalahan, perbaikan diri, dan manajemen volume yang lebih canggih. Btrfs mendukung fitur seperti snapshot, subvolume, dan pemeriksaan integritas data.<br/>
<h2> BAB III Penutup </h2>
<h3>3.1 Kesimpulan</h3>
<p class="justify">Sistem Operasi menjadi komponen utama yang memungkinkan perangkat keras komputer menjalankan berbagai aplikasi dan fungsi. Sistem operasi adalah seperangkat program terstruktur yang mengelola sumber daya perangkat keras (Hardware) dan menyediakan layanan umum untuk aplikasi perangkat lunak (software). Sehingga Sistem operasi merupakan hal yang paling penting dari perangkat lunak dalam sistem komputer.</p>
<p class="justify">Dalam praktikum installasi Linux yang saya lakukan berhasil dengan lancar. Sistem operasi Linux dapat dijalankan dengan baik, semua aspek dan langkah - langkah dalam proses berjalan dan instalasi telah dilakukan dengan baik. Penggunaan Linux sebagai sistem operasi alternatif memberikan pemahaman yang lebih mendalam tentang manajemen sistem operasi, termasuk pengelolaan partisi dan konfigurasi perangkat keras. Selain itu, pengaturan dual boot juga memperkenalkan cara untuk menggunakan dua sistem operasi pada satu perangkat, yang memberikan fleksibilitas lebih bagi pengguna dalam memilih lingkungan kerja sesuai kebutuhan.</p>
