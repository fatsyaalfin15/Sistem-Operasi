# Tugas 1
•	Proses  Memulai Instalasi Ubuntu :
1.	Setelah melakukan proses booting, Anda akan melihat menu dengan opsi seperti "Try Ubuntu" dan 1"Install Ubuntu". Pilih "Install Ubuntu" untuk melanjutkan instalasi.
  <div align="center">
  <img src="https://github.com/fatsyaalfin15/Sistem-Operasi/blob/main/%60Instalasi_ubuntu/Pertama.jpg" alt="Deskripsi Gambar" width="1000"/>
   </div>
   
2. Pengaturan Bahasa
   <div align="center">
   <img src=  "https://github.com/fatsyaalfin15/Sistem-Operasi/blob/main/%60Instalasi_ubuntu/ketiga.jpg" alt="Deskripsi Gambar" width= "1000"/> 
   </div> 
   Pilih bahasa yang diinginkan untuk instalasi (misalnya, "Bahasa Indonesia" atau "English") dan klik "Continue".

3.Koneksi Internet:
Jika tersedia, hubungkan ke jaringan Wi-Fi atau kabel Ethernet. Koneksi internet diperlukan untuk mengunduh pembaruan selama instalasi, namun ini bisa dilewati dan dilakukan nanti.
<div align="center"
<img src="https://github.com/fatsyaalfin15/Sistem-Operasi/blob/main/%60Instalasi_ubuntu/keempat.jpg" alt="Deskripsi Gambar" width="1000"/>
</div>

4. Pilih tata letak keyboard yang sesuai. Jika ragu, pilih "English (US)". Klik "Continue".
  <div align="center">
   <img src=  "https://github.com/fatsyaalfin15/Sistem-Operasi/blob/main/%60Instalasi_ubuntu/ketiga.jpg" alt="Deskripsi Gambar" width= "1000"/> 
   </div> 
   Pilih bahasa yang diinginkan untuk instalasi (misalnya, "Bahasa Indonesia" atau "English") dan klik "Continue".

5. Pilih jenis instalasi. Anda dapat memilih:
-Normal Installation: Menyertakan angkat lunak standar seperti browser, editor teks, dll.
-Minimal Installation: Hanya menyertakan perangkat lunak dasar seperti browser dan utilitas sistem.
<div align="center">
   <img src=  "https://github.com/fatsyaalfin15/Sistem-Operasi/blob/main/%60Instalasi_ubuntu/kelima.jpg" alt="Deskripsi Gambar" width= "1000"/> 
   </div> 

6. Pilih metode partisi:
Erase disk and install Ubuntu: Menghapus semua data di disk dan menginstal Ubuntu sebagai satu-satunya sistem operasi.
Install Ubuntu alongside existing OS: Dual-boot dengan sistem operasi yang sudah ada.
Something else: Opsi lanjutan untuk mengatur partisi manual.
 Pilih opsi yang sesuai dan klik "Install Now".
 <div align="center">
   <img src=  "https://github.com/fatsyaalfin15/Sistem-Operasi/blob/main/%60Instalasi_ubuntu/keenam.jpg" alt="Deskripsi Gambar" width= "1000"/> 
   </div> 


7.	Pengaturan Zona Waktu:
 Pilih zona waktu Anda pada peta atau masukkan kota Anda. Klik "Continue".
 <div align="center">
   <img src=  "https://github.com/fatsyaalfin15/Sistem-Operasi/blob/main/%60Instalasi_ubuntu/kedua.jpg" alt="Deskripsi Gambar" width= "1000"/> 
   </div> 

8.Pengaturan Pengguna:
Masukkan nama Anda, nama komputer, nama pengguna, dan kata sandi. Opsi "Log in automatically" dapat dipilih jika Anda ingin langsung masuk tanpa memasukkan kata sandi setiap kali. Klik "Continue".
Proses Instalasi:
Ubuntu akan mulai menginstal sistem operasi. Proses ini bisa memakan waktu beberapa menit hingga lebih dari setengah jam, tergantung pada kecepatan komputer.
Selesai dan Restart:
<div align="center">
   <img src=  "https://github.com/fatsyaalfin15/Sistem-Operasi/blob/main/%60Instalasi_ubuntu/ketujuh.jpg" alt="Deskripsi Gambar" width= "1000"/> 
   </div> 
9. Selanjutnya akan muncul tampilan seperti dibawah ini yang menandakan ubuntu sudah bisa dijalankan
 <div align="center">
   <img src=  "https://github.com/fatsyaalfin15/Sistem-Operasi/blob/main/%60Instalasi_ubuntu/VirtualBox_Ubuntu%2024.04_29_08_2024_15_42_19.png" alt="Deskripsi Gambar" width= "1000"/> 
   </div> 
   ini merupakan tampilan gui dari ubuntu
  <div align="center">
   <img src=  "https://github.com/fatsyaalfin15/Sistem-Operasi/blob/main/%60Instalasi_ubuntu/VirtualBox_Ubuntu%2024.04_29_08_2024_15_25_40.png" alt="Deskripsi Gambar" width= "1000"/> 
   </div>  
# Tugas 2
•	Mengapa saat instalasi perlu dipilih “/” pada opsi Mount Point??
karena pada opsi tersebut saat memilih”/” tersebut kita akan tahu installer di mana sistem operasi utama (termasuk kernel, sistem file, dan aplikasi inti) akan diinstal.
Ini adalah lokasi di mana seluruh sistem Linux akan diatur dan berjalan. Ini juga  berarti  kita akan memilih "/" sebagai mount point untuk satu partisi menandakan
bahwa seluruh struktur sistem file akan dimulai dari partisi tersebut dan tanpa root directory, sistem operasi tidak akan bisa berfungsi dengan baik karena tidak ada 
struktur yang mengatur lokasi file dan direktori.

•	Penjelasan tentang Ext4, Ext3, swap, ntfs, fat32, btrfs.

1.	Ext4  merupakan versi terbaru dari seri EXT (Extended Filesystem) dan merupakan sistem file default di banyak distribusi Linux . Fungsi utamanya untuk  adalah menyimpan, mengorganisasi, dan mengelola data di penyimpanan (seperti hard disk atau SSD) dan alokasi ruang yang lebih efisien

2.	Ext3  merupakan sistem file default sebelum Ext4 yang mana Fungsinya menyediakan lingkungan penyimpanan yang lebih andal dibandingkan dengan EXT2, berkat fitur jurnal yang mencatat perubahan sebelum diimplementasikan pada disk. Ini membantu mempercepat pemulihan sistem setelah kegagalan atau crash.

3.	Swap merupakan  ruang di disk yang digunakan oleh sistem operasi Linux sebagai memori tambahan (virtual) di luar RAM fisik. Swap bisa berupa partisi khusus atau file swap di dalam sistem file, fungsinya untuk membantu sistem tetap beroperasi ketika RAM fisik penuh. Saat RAM sudah mencapai kapasitasnya, data yang tidak aktif di RAM dapat dipindahkan sementara ke swap, sehingga RAM dapat digunakan oleh proses yang lebih membutuhkan.

4.	NTFS (new tecnologi file system) merupakan adalah sistem file milik Microsoft yang diperkenalkan dengan Windows NT dan digunakan secara luas di sistem operasi Windows , fungsinya untuk mengelola dan menyimpan data pada sistem operasi Windows. Fungsi utamanya meliputi dukungan untuk ukuran file yang sangat besar, fitur keamanan (seperti kontrol akses file), kompresi file, enkripsi, dan fitur pemulihan setelah crash. Di Ubuntu, NTFS digunakan untuk mengakses data yang disimpan di partisi Windows.

5.	FAT32 (File Allocation Table 32) merupakan versi dari sistem file FAT yang menggunakan tabel alokasi file 32-bit pada perangkat penyimpanan portable fungsinya 
untuk menyimpan dan mengatur file pada media penyimpanan yang memerlukan kompatibilitas luas, seperti flash drive, kartu SD, dan disk eksternal.

6.	Btrfs (B-Tree File System) merupakan sistem file modern yang dikembangkan oleh komunitas Linux dengan fokus pada fitur lanjutan seperti manajemen volume, snapshot, dan pemeriksaan integritas data, memiliki fungsi menyediakan sistem file 





