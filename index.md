## Tugas UTS Praktikum Sistem Komputer

Pada artikel kali ini, saya akan membahas Tugas UTS dari Mata Kuliah Praktikum Sistem Komputer dengan dosen pengampu saya, Pak Johan Ericka Wahyu Prakasa, M.Kom.Sebelum kita membahas persoalan dari tugas UTS ini, akan saya jelaskan terlebih dahulu apa itu mata kuliah Praktikum Sistem Komputer.

## Praktikum Sistem Komputer

Praktikum Sistem Komputer ialah salah satu mata kuliah di prodi Teknik Informatika Universitas Islam Negeri Maulana Malik Ibrahim, Malang yang membahas tentang cara kerja sebuah komputer. Apa saja hardware atau komponen penting didalam komputer, bagaimana komputer dapat berjalan, hingga cara kerja tiap komponennya dijelaskan didalam mata kuliah ini. Operating System, komponen input, proccess dan output juga dibahas didalam modul mata kuliah Praktikum SIstem Komputer ini.

## Tugas Ujian Tengah Semester

Ada beberapa persoalan yang harus diselesaikan didalam tugas UTS Praktikum Sistem Komputer kali ini. Berikut ini persoalan, ketentuan dan keterangan serta aturan yang diberikan.

```markdown
Kerjakan Ujian Tengah Semester ini secara mandiri.

Buat blog yang berisi tentang :

1. Penjelasan langkah - langkah untuk melakukan instalasi sistem operasi proprietary versi bebas (nilai : 20)

2. Penjelasan langkah - langkah untuk melakukan instalasi sistem operasi open source distribusi bebas (nilai : 20)

3. Penjelasan langkah - langkah untuk melakukan partisi harddisk pada sistem operasi proprietary (nilai : 30)

4. Penjelasan langkah - langkah untuk melakukan partisi pada sistem operasi open source (nilai : 30)

Catatan :
URL blog di paste pada Submission UTS di situs E-Learning UIN Maliki Malang.

Aturan  :
Apabila ditemukan kemiripan dengan tugas mahasiswa lain ( lebih dari 20% ) maka nilai akan di bagi rata
Apabila ditemukan kemiripan dengan sumber yang ada di internet (lebih dari 20% ) maka nilai akan dikurangi 50%
```

Sebelum memasuki ke pembahasan tiap poin permasalahan, ada baiknya kita mengetahui terlebih dahulu setiap istilah yang ada didalam persoalan diatas.

1. Sistem Operasi
Sistem Operasi adalah perangkat lunak atau software yang memiliki peranan penting sebagai pengatur sumber daya utama dari keseluruhan sistem terutama antara hardware dengan software agar bisa digunakan. Bagaimana sistem akan berjalan, bagaimana struktur dari proses hardware dilakukan, bagaimana agar komputer dapat melakukan boot, adalah tugas dari Sistem Operasi ini.

2. Proprietary versi bebas
Proprietary berasal dari kata property yang berarti suatu benda. Istilah proprietary ini lebih merujuk kepada suatu benda yang dimiliki oleh suatu pemilik.  Lalu apa yang dimaksud dengan sistem operasi jenis Proprietary ini? Sistem operasi Proprietary  versi bebas adalah suatu sistem operasi yang perkembangan dan kepemilikannya dimiliki oleh suatu organisasi atau perusahaan atau bahkan oleh seseorang. Yang termmasuk kedalam sistem operasi jenis ini adalah Windows.

2. Open Source distribusi bebas
Open Source disini berarti semua source codenya dapat dikelola maupun dimiliki oleh orang atau kelompok lain tanpa perlu membayar. Kita snediri dapat memiliki sistem operasi yang kita buat sendiri dari mengembangkan sistem operasi jenis ini. Namun, untuk hak cipta sistem operasi jenis ini akan membutuhkan biaya yang tidak murah. Yang termasuk kedalam sistem operasi open source ini ialah Linux.

Karena istilah yang dipilih telah dipahami, kita akan masuk ke pembahasan tiap poin permasalahan.

### Persoalan No 01

Notes : Penjelasan langkah - langkah untuk melakukan instalasi sistem operasi proprietary versi bebas (nilai : 20)

Disini saya akan memasang sistem operasi proprietary versi bebas, yakni Windows 10. Pemasangannya sendiri tidak langsung didalam device yang saya pakai, tetapi akan saya pasang didalam ruang virtual, yakni menggunakan bantuan software tambahan yang biasa disebut VirtualBox.

1. Membuat Virtual Machine Baru dan Memasukkan file ISO kedalam Virtual Machine tersebut

    ![W01](https://user-images.githubusercontent.com/74701531/140753169-13dc3d90-dc39-4c25-87fd-cfb481f8c75f.png)

    Tahap awal kita melakukan instalasi Windows 10 adalah membuat virtual machine baru dan memasukkan file ISO dari sistem operasi Windows yang kita download kedalam Virtudal Machine tersebut. ISO disini dapat kita anggap sebuah DVD.

2. Pemilihan bahasa sewaktu pemasangan, pengaturan waktu dan mata uang dan pengaturan bahasa dari keyboard atau inputan

    ![W02](https://user-images.githubusercontent.com/74701531/140753803-d40f3c69-6574-4541-ab91-e879ef4c6e43.png)

    Pada tahap ini kita disuruh untuk mengatur dan memilih beberapa hal dasar yang terdiri dari Pemilihan bahasa sewaktu pemasangan, pengaturan waktu dan mata uang dan pengaturan bahasa dari keyboard atau inputan.

3. Pengambilan Keputusan Pemasangan

    ![W03](https://user-images.githubusercontent.com/74701531/140754502-c2acf530-4fad-40de-846e-c34f58b1d4cc.png)
    
    Pada proses kali ini, kita disuruh untuk menekan tombol Install Now apabila ingin memasang Windows 10 di device tersebut sekarang.
    
4. Pemilihan versi atau jenis OS yang akan kita pasang

    ![W04](https://user-images.githubusercontent.com/74701531/140760651-6f438022-1f1c-4751-96b7-55bf2be3213b.png)
    
    Pada proses kali ini kita disuruh untuk memilih salah satu jenis atau versi dari windows 10 yang ada didalam file iso windows tersebut. Karena kita hanya menggunakan OS ini untuk pembelajaran kita pilih saja Windows 10 Home.

5. Menyetujui Ketentuan
    
    ![W05](https://user-images.githubusercontent.com/74701531/140761198-64fa69bb-8e55-47a0-8171-6b60f0e980d4.png)
    
    Untuk melanjutkan ke proses selanjutnya, kita disuruh untuk mengetahui berbagai hal tentang ketentuan dari Windows 10. Jika sudah kita baca dan menyetujui ketentuan tersebut, kita centang kotak kecil disamping kata I Accept The License Terms. Kemudian klik Next Button.
    
6. Memilih Tipe Instalasi

    ![W06](https://user-images.githubusercontent.com/74701531/140761480-b22d35f5-2477-4ca5-8871-67d367984ec0.png)
    
    Disini kita disuruh untuk memilih tipe instalasi / pemasangan. Diantaranya ada Upgrade Install Windows and keep files, setting and applications dan Custom Install Windows only (Advanced). Opsi pertama untuk pemasangan windows dengan menyimpan file, setting, dan aplikasi sebelumnya. Opsi kedua adalah benar benar menindih pengaturan OS sebelumnya. Kita akan pilih yang custom karena kita baru saja memasang OS Windows.
    
7. Memilih tempat pengalokasian OS
    
    ![W07](https://user-images.githubusercontent.com/74701531/140761993-7099248e-b7d7-4ac6-ade6-0d0aea0b1e2c.png)
    
    Disini kita dapat meilih di disk mana kita akan memasang OS kita. Kita juga bisa membagi partisi disini. Kita juga dapat melakukan berbagai proses terhadap storage device kita.
    
8. Pemasangan Awal
    
    ![W08](https://user-images.githubusercontent.com/74701531/140762230-1707e1d5-6e59-4204-ba75-887672bb621a.png)
    
    ![W08a](https://user-images.githubusercontent.com/74701531/140762400-8ba6b56d-e2c0-49e5-a91a-f90bdf80caac.png)
    
    ![image](https://user-images.githubusercontent.com/74701531/140762487-f79b5ece-a8ba-448b-8ac8-58482d5b29c1.png)
    
    Pemasangan Windows 10 telah dilakukan. Kita akan menunggu beberapa saat hingga proses selesai. Semakin bagus performa dari device yang kita pakai, semakin cepat proses pemasangannya.
    
9. Memilih negara yang kita tempati saat ini

    ![image](https://user-images.githubusercontent.com/74701531/140762616-26c1c056-b0dc-48ab-8894-c20c9a1913d4.png)

    Disini kita disuruh memilih negara mana yang kita tinggali saat ini. Kalau sudah memilih, tekan tombol Yes.
    
10. Memilih tata letak keyboard

    ![image](https://user-images.githubusercontent.com/74701531/140762779-4b8d285c-e9e2-4a57-ac9e-4afacadfabb0.png)

    Disini kita disuruh memilih desain tata letak dari keyboard kita. Klik tombol yes apabila sudah memilih.
    
11. Memilih tata letak keyboard kedua

    ![image](https://user-images.githubusercontent.com/74701531/140762878-8371883f-7716-4671-a6fe-be9863b994ed.png)

    Disini kita disuruh memilih desain tata letak dari keyboard kedua kita. Klik tombol Add Layout apabila ingin menambahkan desain tata letak atau klik tombol Skip untuk melewati proses ini.

12. Pemilihan jaringan (Internet)

    ![image](https://user-images.githubusercontent.com/74701531/140763018-01e47223-4aad-4d78-9a57-f5ab62cd4fbf.png)

    Pilih jaringan yang akan kita gunakan untuk proses pemasangan. Apabila tidak ada atau tidak bisa terhubung, klik teks I don’t have internet.
    
13. Pemilihan jaringan (Internet)

    ![image](https://user-images.githubusercontent.com/74701531/140763103-09fe057a-176c-4c8f-a981-0cd369c064d7.png)
    
    ![image](https://user-images.githubusercontent.com/74701531/140763211-a6da1d0f-4958-487e-bd0e-c0a1ac87502e.png)

    Pilih jaringan yang akan kita gunakan untuk proses pemasangan. Apabila ada atau terhubung, klik teks tombol Next.
    
14. Menambahkan akun Microsoft

    ![image](https://user-images.githubusercontent.com/74701531/140763272-c7e25f2e-fb59-4891-9097-79d8c040ee81.png)

    Disini kita disuruh untuk memasukkan email Microsoft kita agar bisa melanjutkan proses pemasangan. Hal ini wajib sebagai persyarat pemasangan windows. Apabila tidak punya akun, kita bisa klik Create Account dan apabila sudah punya, kalian hanya perlu mengisi kolom yang telah disediakan lalu klik tombol Next.
    
15. Memasukkan Katasandi Akun Microsoft

    ![image](https://user-images.githubusercontent.com/74701531/140763401-0ae4698e-39ef-4e04-ba2b-f3c1b69e6864.png)

    Pada tahap ini kita disuruh untuk memasukkan katasandi dari akun microsoft yang telah kita masukkan pada bagian sebelumnya.
    
16. Membuat PIN

    ![image](https://user-images.githubusercontent.com/74701531/140763505-78abbd45-ef1d-4b8e-9551-dcaa8314759e.png)

    Klik tombol Create PIN.
    
    ![image](https://user-images.githubusercontent.com/74701531/140763668-7a6092e9-952b-4e76-93c7-0700ee9cae8b.png)

    Isi dengan pin yang anda inginkan untuk mengamankan device anda. Jika sudah, klik OK
    
17. Memilih pengaturan privasi untuk device kita

    ![image](https://user-images.githubusercontent.com/74701531/140763811-ce9a1009-dcc5-43bd-a4e4-1b1632fe8218.png)

    Disini ada berbagai macam pengaturan keamanan akun. Dari keamanan lokasi, diagnosis data, pencarian device apabila hilang, sponsor, dll. Kita bisa tidak mengaktifkannya apabila tidak diperlukan. Kalau sudah, klik tombol Accept.
    
18. Memilih Kustomisasi Pengalaman untuk Device kita

    ![image](https://user-images.githubusercontent.com/74701531/140763909-b8c4fbc8-5296-43c6-89f2-d625b5718007.png)

    OS Windows saat ini memiliki banyak kemudahan dengan hadirnya teknologi AI pada dirinya. Dan salah satunya ada dibagian ini. Kita bisa kustomisasi pengalaman penggunaan device nanti seperti apa. Yang kemudian akan memudahkan kita dalam pengalaman penggunaan Windows nantinya. Klik tombol Skip apabila tidak diperlukan atau klik salah satu kustomisasi pengalaman dan kemudian klik tombol Accept.
    
19. Pemberitahuan Windows terkait Penggunaan Android phone dari PC

    ![image](https://user-images.githubusercontent.com/74701531/140764035-94280ec4-06cb-4b65-8c92-25699f70ed1d.png)

    Disini kita disuguhkan dengan informasi fitur terbaru dari windows dan salah satunya penggunaan Android phone dari windows 10. Klik tombol No Thanks apabila tidak berminat atau klik tombol Remind Me Later apabila ingin diingatkan setelah pemasangan terkait fitur ini.
    
20. Keputusan Back Up dokumen dengan OneDrive

    ![image](https://user-images.githubusercontent.com/74701531/140764103-4060a13c-8dd8-4c50-9d3a-c88b39a64ad6.png)

    Apabila kalian ingin Back Up data kalian secara online di OneDrive, kalian bisa klik tombol Next. Apabila tidak, klik Only save files to this PC.
    
21. Klaim Microsoft 365 Trial

    ![image](https://user-images.githubusercontent.com/74701531/140764228-bf37a27a-6d2e-4ba7-b7f2-1bd35a775356.png)

    Apabila kalian ingin mencoba menggunakan software Microsoft 365, kalian bisa klik tombol Try for Free. Apabila tidak ingin, klik tombol No, Thanks.
    
22. Penagktifan Fitur Cortana

    ![image](https://user-images.githubusercontent.com/74701531/140764327-e83f0992-55a3-4784-aab4-27686236fb09.png)

    Apabila kalian ingin mengaktifkan Cortana, klik tombol Accept. Apabila tidak, cukup klik tombol Not Now.
    
23. Proses Pemasangan Konfigurasi

    ![image](https://user-images.githubusercontent.com/74701531/140764388-fab96f52-c7ff-4ccc-bfbc-5531ed4df81d.png)

    Kita disuruh menunggu beberapa saat sampai proses konfigurasi windows 10 telah selesai.
    
24. Tampilan Awal Windows 10

    ![image](https://user-images.githubusercontent.com/74701531/140764475-57219bcf-c96e-45eb-80e6-7ef32397b00f.png)

    Dan inilah tampilan awal Windows 10 setelah di pasang. SELESAI
    
### Persoalan No 02

Notes : Penjelasan langkah - langkah untuk melakukan instalasi sistem operasi open source distribusi bebas (nilai : 20)

Disini saya akan memasang sistem operasi open source distribusi bebas, yakni Linux dengan distro Ubuntu versi 21.04. Pemasangannya sendiri tidak langsung didalam device yang saya pakai, tetapi akan saya pasang didalam ruang virtual, yakni menggunakan bantuan software tambahan yang biasa disebut VirtualBox.

1. Membuat Virtual Machine Baru dan Memasukkan file ISO kedalam Virtual Machine tersebut

    ![image](https://user-images.githubusercontent.com/74701531/140766819-9937676b-c393-4e5e-970f-e52c4a7bdafb.png)

    Tahap awal kita melakukan instalasi distro linux adalah membuat virtual machine baru dan memasukkan file ISO salah satu distro linux yang kita download kedalam Virtudal Machine tersebut. ISO disini dapat kita anggap sebuah DVD.
    
2. Proses Checking Disk

    ![image](https://user-images.githubusercontent.com/74701531/140767308-e659a79c-8082-4c06-b815-24e358155264.png)

    Pada tahap ini kita disuruh menunggu beberapa saat. Virtual Machine / Device masih membaca / mengecek semua data yang ada didalam file ISO yang telah kita masukkan tadi.
    
3. Tampilan Awal Instalasi Linux Ubuntu

    ![image](https://user-images.githubusercontent.com/74701531/140767396-d0af20d0-a022-4872-b157-404196b06317.png)

    Pada tahap ini kita disuruh memilih bahasa yang akan kita gunakan sewaktu instalasi dan memilih apakah hanya ingin mencoba ubuntu atau install penuh ubuntu. Klik Install untuk memulai instalasi penuh.
    
4. Memilih Layout Keyboard

    ![image](https://user-images.githubusercontent.com/74701531/140767468-2e19d783-a83c-4cc2-a981-71d1a0d8f9a6.png)

    Disini kita disuruh untuk memilih layout dari keyboard kita nanti. Selain bisa memilih tatanan keyboard yang telah disediakan, kita juga bisa kustomisasi layout keyboardnya. Pilih US kemudian klik tombol Continue.
    
5. Updates and Other Software

    ![image](https://user-images.githubusercontent.com/74701531/140767543-ad7fbebd-5547-4dff-a8c4-b7364ec2c17c.png)

    Pada tahap ini kita disuruh memilih mode instalasi, apakah normal installation (paket lengkap dari UBUNTU) atau minimal installation (Web Browser dan basic utilities). Kita juga dapat mengaktifkan updates ketika install UBUNTU dan juga memakai software pihak ketiga. Disini saya menggunakan minimal installation dengan updates dinyalakan. Klik tombol Continue.
    
6. Installation Type

    ![image](https://user-images.githubusercontent.com/74701531/140767623-0b225126-da26-4e9f-9b0b-72a06bbf2d91.png)

    Pada tahap ini kita disuruh memilih, apakah install ubuntu langsung di drive ini sekarang dan membuang apapun di drive atau membuat partisi baru. Disini saya menggunakan Erase disk dan Install Ubuntu. Klik tombol Install Now.
    
7. Pop Up Alert

    ![image](https://user-images.githubusercontent.com/74701531/140767882-b93fc8b2-8ec0-40dc-b530-7f647d9a3ed7.png)

    Jika kita memilih Erase Disk tadi, maka akan keluar pop up seperti gambar disamping. Klik tombol Continue.
    
8. Pengaturan Lokasi

    ![image](https://user-images.githubusercontent.com/74701531/140767939-c2f6a606-4e11-41a0-b8f2-b7c2bf533a56.png)

    Pada tahap ini, kita disuruh memilih lokasi kita saat ini. Hal ini untuk memudahkan pengaturan waktu, lokasi, dll nanti. Klik tombol Continue.
    
9. Data diri

    ![image](https://user-images.githubusercontent.com/74701531/140768012-3eac9888-9856-4d46-a9ef-682d0c2c4820.png)

    Isi data diri kalian disini. Nama lengkap, nama komputer, username dan password. Jika kalian ingin login otomatis kedalam os ini nanti, cukup centang log in automatically, jika ingin mengunci device os kalian, centang Require my password to login. Klik Continue.
    
10. Instalasi

    ![image](https://user-images.githubusercontent.com/74701531/140768097-43b2c54e-37d8-4db7-870c-521727d12ae3.png)

    Tampilan ini adalah tampilan proses instalasi dari linux Ubuntu. Tunggu hingga selesai.
    
11. Instalasi Selesai

    ![image](https://user-images.githubusercontent.com/74701531/140768180-b9cb70b9-3c72-4b3f-b3e7-c0743e056ee3.png)

    Setelah instalasi selesai, kita disuruh untuk restart device kita. Klik tombol Restart Now.
    
12. Remove Installation CD / DVD

    ![image](https://user-images.githubusercontent.com/74701531/140768243-78f0d207-ae51-4bca-9f3b-81b7dd1587ae.png)

    Pada tahap ini kita disuruh untuk melepas file ISO yang sbeelumnya kita masukkan. Lalu klik enter.
    
13. Login

    ![image](https://user-images.githubusercontent.com/74701531/140768322-01d78da3-5b49-465d-b2d5-baf85bb6e9ae.png)
    
    Buka lockscreen dengan klik saja akun yang ingin dimasuki lalu isi password dengan password yang telah dibuat saat instalasi.
    
14. Tampilan Awal Linux Ubuntu

    ![image](https://user-images.githubusercontent.com/74701531/140768592-941060b3-b350-41e8-8e9d-5407a35502b1.png)

    SELESAI
    
### Persoalan No 03

Notes : Penjelasan langkah - langkah untuk melakukan partisi harddisk pada sistem operasi proprietary (nilai : 30)

Disini saya akan malekukan partisi storage device (harddisk) pada sistem operasi proprietary versi bebas, yakni Windows 10. Proses partisinya sendiri tidak langsung didalam device yang saya pakai, tetapi akan saya akan melakukan partisi didalam ruang virtual, yakni menggunakan bantuan software tambahan yang biasa disebut VirtualBox. Untuk partisi di Windows sendiri, dapat memakai aplikasi bawaan dari Windows yang kemudian akan saya sebutkan langkah-langkahnya dibawah ini.

1. Buka terlebih dahulu VirtualBox

    ![image](https://user-images.githubusercontent.com/74701531/140772400-e5670da0-8a3d-4d1c-863a-a96eb3746188.png)

2. Jalankan virtual machine yang akan dibagi partisinya (Windows OS)

    ![image](https://user-images.githubusercontent.com/74701531/140773308-a6e2102b-4037-41b7-a203-8fc22748a065.png)

3. Masuk kedalam Windows

    ![image](https://user-images.githubusercontent.com/74701531/140773350-b8d89fe7-6ab1-40a7-b65d-734114fcacb2.png)
    
    ![image](https://user-images.githubusercontent.com/74701531/140773377-cd983dd5-cb22-49f3-bbc3-b5d7a19922ac.png)

4. Buka File Explorer

    ![image](https://user-images.githubusercontent.com/74701531/140773418-03c7bdee-6a72-4b6c-ad15-6480b26234d9.png)

5. Pilih “computer” pada tab library diatas, kemudian pilih “manage”

    ![image](https://user-images.githubusercontent.com/74701531/140773723-31d58790-ff0a-4ed4-9b38-34f8e7010b81.png)

6. Kemudian pilih “Disk Management”

    ![image](https://user-images.githubusercontent.com/74701531/140773890-96a57e42-aee9-4b58-88b9-bb41c3527e26.png)

7. Kemudian klik kanan pada partisi C, lalu pilih “Shrink Volume”

    ![image](https://user-images.githubusercontent.com/74701531/140774014-99dca3e4-a17a-4879-8356-4129226c38f0.png)

8. Tentukan ukuran yang akan dibagi, lalu klik tombol “Shrink” dan tunggu beberapa saat (80% dari 50GB adalah 40GB, jadi partisi C 30GB dan partisi D adalah 10GB)

    ![image](https://user-images.githubusercontent.com/74701531/140774063-95a72f47-8054-4d5a-80a6-b0097d70d610.png)
    
    Catatan :
-	Total size before shrink in MB 		: Ukuran sebelum dibagi (C)
-	Size of Available shrink space in MB 	: Ukuran maksimal yang tersedia untuk dibagi
-	Enter the amount of space to shrink ...	: Ukuran partisi yang kita inginkan untuk dibagi (D)
-	Total size after shrink in MB		: Ukuran setelah dibagi (C)

9. Kemudian klik kanan pada “unallocated partition” (partisi kosong yang telah kita buat), selanjutnya klik “New Simple Volume”

    ![image](https://user-images.githubusercontent.com/74701531/140774239-42a90717-a8b4-423e-b55a-e66ff05f069b.png)

10. Kemudian klik "next”

    ![image](https://user-images.githubusercontent.com/74701531/140774299-fb1346d3-f921-47d1-a614-7fdeea1b8a25.png)

11. Kemudian tentukan, berapa ukuran partisi yang akan kita buat dari partisi kosong tersebut. Karena kita akan memakai semuanya (10GB), maka klik tombol “next” saja

    ![image](https://user-images.githubusercontent.com/74701531/140774369-19475c47-e46d-43c0-b210-a459d470f71b.png)

12. Kemudian, kita pilih drive letter nya. Karena kita akan menggunakaan drive letter D, maka pilih karakter D. Lalu klik tombol “Next”

    ![image](https://user-images.githubusercontent.com/74701531/140774411-ec092b9f-48a3-4bce-9c38-384e7cf61ffb.png)

13. Kemudian pilih jenis sistem filenya. Kita gunakan NTFS. Pada “volume label” kita berikan nama dari partisi yang akan kita buat. Lalu klik tombol “Next”

    ![image](https://user-images.githubusercontent.com/74701531/140774452-e99449bd-88a8-4653-aca5-2da31cabc446.png)

14. Lalu, klik tombol “Finish” untuk memulai pembuatan partisi. Kemudian tunggu beberapa saat hingga proses pembuatan selesai.

    ![image](https://user-images.githubusercontent.com/74701531/140774492-cb82140a-da81-4647-a62b-a05d6a297ceb.png)

15. Selesai. Partisi telah dibuat.

    ![Uploading image.png…]()

