Proses instalasi sistem operasi Linux  
1.Masukkan DVD Ubuntu-24.04-dekstop-amd64
![Oracle VM VirtualBox Manager 29_08_2024 18_55_49](https://github.com/user-attachments/assets/3e46cc7e-47fa-4db0-ad3d-94d444f08e14)

2.Atur berapa banyak memori dan CPU pada processor  yang digunakan
![image](https://github.com/user-attachments/assets/db306670-07eb-4f59-a883-7148e4d1ca73)

3.Atur berapa banyak penyimpanan yang akan digunakan untuk menjalan sistem operasi Linux
![image](https://github.com/user-attachments/assets/65237a9d-cc5d-4fb0-83d3-1977a9d1fe74)

4.Pada saat dijalankan akan diberi pilihan untuk booting, namun jika ingin melakukan instalasi, pilih Try or install Ubuntu
![image](https://github.com/user-attachments/assets/96e0d05d-a7f6-4147-b8cc-44835c76b1fb)

5.Setelah booting, akan terlihat seperti ini. Selesaikan pengaturan sebelum memulai instalasi
a.Pilih bahasa sistem operasi
![image](https://github.com/user-attachments/assets/7d750bee-27be-4da2-94f7-d52fd63c87fb)

b.Atur aksesibilitas
![image](https://github.com/user-attachments/assets/1bc92867-33c7-4689-b2a6-d94c2fdb0d27)

 
c.Pilih layout keyboard
![image](https://github.com/user-attachments/assets/c2abf242-dbe1-4429-b123-a222aca1436c)

d.Konektivitas internet
![image](https://github.com/user-attachments/assets/66f3fb3f-b2e5-45bb-8a47-9b550e6a9e07)

e.Pilih Install Ubuntu jika ingin menginstal sistem operasi, namun jika ingin mencoba tanpa melakukan instalasi pilih Try Ubuntu
![image](https://github.com/user-attachments/assets/7142b99d-7a8a-4cbf-a111-f28cda899409)

f.Cara untuk menginstal sistem operasi
![image](https://github.com/user-attachments/assets/9386b785-f0ba-4610-8d1a-430e36c3965f)

g.Pilihan aplikasi yang diinstal setelah instalasi
![image](https://github.com/user-attachments/assets/697c3f26-3d30-4695-9312-35dac41d8598)

h.yang dilakukan pada penyimpanan pada saat instalasi
![image](https://github.com/user-attachments/assets/435517a8-19b3-4ae4-864a-b70492ba2ef7)

i.Buat username dan password untuk verifikasi saat masuk atau login ke sistem operasi
![image](https://github.com/user-attachments/assets/94ee1004-12f3-461c-8d30-5b7497423d53)

j.Pilih zona waktu
![image](https://github.com/user-attachments/assets/ff2125ec-5642-4bee-bd51-fb7cbf5863b8)

6.Setelah selesai melakukan pengaturan, klik Install
![image](https://github.com/user-attachments/assets/6442a6fa-4616-49a6-be5a-4d1392802635)

Pada saat instalasi, tampilannya akan terlihat seperti gambar dibawah
![image](https://github.com/user-attachments/assets/c1ecb838-bdb4-4d96-9fdb-0227eb211e2d)

7.Setelah selesai instalasi, maka sistem operasi akan melakukan reboot. ketika reboot selesai, masukkan password untuk masuk ke sistem operasi. Selanjutnya terlihat seperti gambar di bawah menunjukkan, bahwa sistem operasi telah terinstal dan siap untuk digunakan
![image](https://github.com/user-attachments/assets/b98b23c1-cec7-48c6-b43f-09ec24f307b1)

'

'

2. Analisislah pada gambar kenapa saat instalasi perlu dipilih “/” pada opsi Mount Point ?
![image](https://github.com/user-attachments/assets/e4877b36-9cd9-4e4c-88a7-16292e1afa9b)

Karena tanda "/" adalah tanda root dari partisi, partisi root merupakan partisi  tertinggi di  Linux  atau  mudahnya  partisi  root  hampir  sama  dengan drive  C:  di  Windows  pada opsi  Mount  Point.  Jadi  tanda  tersebut  akan menunjukkan langsung pilihan Use As Ext4 dan lain-lain.

3. Berikan penjelasan tentang ext4, ext3, swap, ntfs, fat32,btrfs !

a. EXT4
EXT4 dirilis secara komplit dan stabil berawal dari kernel 2.628 jadi apabila distro anda yang secara default memiliki versi kernel tersebut atau diatasnya otomatis system anda sudah support ext4.

b. EXT3
EXT3 adalah peningkatan dari EXT2 file system. Ext3 merupakan suatu journalled  file  system,  journalled  file  system  didesain  untuk  membantu melindungi  data  yang  ada  di  dalamnya.  Dengan  adanya  journalled filesystem,  maka  kita  tidak  perlu  lagi  untuk  melakukan  pengecekan kekonsistensian data, yang akan memakan waktu sangat lama bagi harddisk yang berkapasitas besar.

c. SWAP 
Swap  adalah  sebuah  ruang  pada  harddisk  yang  dijadikan  ruang  virtual memory  yang  digunakan  ketika  komputer/laptop  membutuhkan  lebih banyak memory. Dalam artian partisi dengan filesystem Swap ini bekerja sebagai cadangan , apabila RAM yang digunakan penuh. 

d. NTFS 
NTFS  kepanjangan  dari  New  Technology  File  System,  yang  merupakan sebuah  sistem  berkas  yang  masukkan  oleh  Microsoft  dalam  kumpulan sistem operasi windows NT, yang terdiri dari Windows 2000, Windows XP, Windows Server 2003, Windows Vista, Windows 7. 

e. FAT32 
Sistem  file  tertua  yang  dikembangkan pada  tahun  1970-an  yang  tersedia untuk sistem operasi Windows. Ini pada dasarnya dirancang untuk floppy drive  yang  memiliki  ukuran  kurang  dari  500  K.  Ada  tiga  versi  FAT.  FAT12,  FAT16  dan  FAT32  dan  mereka  berbeda  dalam  ukuran  file  dan struktur pada disk. 

f. BTRFS 
BTRFS  (B-Tree  FileSystem)  adalah  sebuah FileSystem modern berbasis Copy on Write (CoW). FileSystem ini pada awalnya didesain oleh Oracle  sejak  tahun  2007  dan  diciptakan  dengan  tujuan  memberikan implementasi  fitur  lanjutan  dan  memudahkan  administrasi  reparasi  data. Fitur utama yang diunggulkan oleh BTRFS di antaranya adalah Subvolume, snapshot,  software  based RAID,  dan checksum untuk  data  dan  metadata untuk reparasi otomatis.

