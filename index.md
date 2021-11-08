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

Disini saya akan memasang sistem operasi open source distribusi bebas, yakni Linux dengan distro Ubintu. Pemasangannya sendiri tidak langsung didalam device yang saya pakai, tetapi akan saya pasang didalam ruang virtual, yakni menggunakan bantuan software tambahan yang biasa disebut VirtualBox.

1. Membuat Virtual Machine Baru dan Memasukkan file ISO kedalam Virtual Machine tersebut

    ![image](https://user-images.githubusercontent.com/74701531/140766619-ad902755-7e21-4e7d-b4a6-e703f70dfea8.png)

    Tahap awal kita melakukan instalasi distro linux adalah membuat virtual machine baru dan memasukkan file ISO salah satu distro linux yang kita download kedalam Virtudal Machine tersebut. ISO disini dapat kita anggap sebuah DVD.
    
2. 
