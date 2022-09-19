<h1 align="center"><b>BIG JAVA EARLY OBJECTS</b><br></h1>
<h3 align="center"><b>6/E</b></h3>


<h3 align="center">CAY HORSTMANN<br>San Jose State University<br>WILEY</h3>

----
#
<h1 align = 'center'><b>BAB<br><br>1<b><br><br>INTRODUCTION</b></h1>

#
## __1.1 Program Komputer__

<p align = "justify">Anda mungkin pernah menggunakan komputer untuk bekerja atau bersenang-senang. Banyak orang menggunakan komputer untuk tugas sehari-hari seperti perbankan elektronik atau menulis makalah. Komputer adalah baik untuk tugas-tugas seperti itu. Mereka dapat menangani tugas berulang, seperti menjumlahkan angka atau menempatkan kata-kata di halaman, tanpa merasa bosan atau lelah<br><br>Fleksibilitas komputer adalah fenomena yang cukup menakjubkan. Mesin yang sama dapat menyeimbangkan buku cek Anda, meletakkan kertas istilah Anda, dan bermain game. Sebaliknya, mesin lain melakukan berbagai tugas yang jauh lebih sempit; mobil yang dikendarai dan pemanggang roti bersulang. Komputer dapat melakukan berbagai tugas karena mereka menjalankan tugas yang berbeda program, yang masing-masing mengarahkan komputer untuk bekerja pada tugas tertentu.<br><br>Komputer itu sendiri adalah mesin yang menyimpan data (angka, kata-kata, gambar), berinteraksi dengan perangkat (monitor, sistem suara, printer), dan menjalankan program. Sebuah program komputer memberi tahu komputer, secara rinci, urutan langkah-langkah yang diperlukan untuk memenuhi tugas. Komputer fisik dan perangkat periferal secara kolektif disebut perangkat keras. Program yang dijalankan komputer disebut barang lunak.<br><br>Program komputer saat ini sangat canggih sehingga sulit dipercaya bahwa mereka terdiri dari instruksi yang sangat primitif. Instruksi tipikal mungkin satu dari berikut ini:<br>
•	Letakkan titik merah pada posisi layar tertentu<br>•	Tambahkan dua angka.<br>•	Jika nilai ini negatif, lanjutkan program pada instruksi tertentu.<br><br>Pengguna komputer memiliki ilusi interaksi yang lancar karena sebuah program berisi sejumlah besar instruksi semacam itu, dan karena komputer dapat mengeksekusinya di kecepatan luar biasa.
Tindakan merancang dan mengimplementasikan program komputer disebut pemrograman. Dalam buku ini, Anda akan belajar cara memprogram komputer yaitu cara mengarahkan komputer untuk menjalankan tugas.<br><br>Untuk menulis game komputer dengan efek gerakan dan suara atau pengolah kata yang mendukung font dan gambar mewah adalah tugas kompleks yang membutuhkan tim yang terdiri dari banyak orang programmer yang sangat terampil. Upaya pemrograman pertama Anda akan lebih biasa.Konsep dan keterampilan yang Anda pelajari dalam buku ini membentuk fondasi penting, dan Anda tidak boleh kecewa jika program pertama Anda tidak menyaingi sophis ticated perangkat lunak yang akrab bagi Anda. Sebenarnya, Anda akan menemukan bahwa ada sensasi yang luar biasa bahkan dalam tugas pemrograman sederhana. Ini adalah pengalaman yang luar biasa untuk melihat komputerdengan tepat dan cepat melaksanakan tugas yang akan memakan waktu berjam-jam kerja keras, untuk membuat perubahan kecil dalam program yang mengarah pada perbaikan segera, dan untuk melihat komputer menjadi perpanjangan dari kekuatan mental Anda.
<br><br></p>


## __1.2	Anatomi Komputer__
<p align = "justify">Untuk memahami proses pemrograman, Anda harus memiliki pemahaman dasar
dari blok bangunan yang membentuk komputer. Kami akan melihat secara pribadi
komputer. Komputer yang lebih besar memiliki komponen yang lebih cepat, lebih besar, atau lebih kuat, tetapimereka pada dasarnya memiliki desain yang sama.
Di jantung komputer terletak pusatnyaunit pemrosesan (CPU) (lihat Gambar 1). Bagian dalam
pengkabelan CPU sangat rumit.Misalnya, prosesor Intel Core (yang populerCPU untuk per komputer pribadi pada saat initulisan) terdiri dari beberapa ratus juta elemen struktural, yang disebut transistor.<br><br>CPU melakukan kontrol program dan data
pengolahan. Artinya, CPU menempatkan dan mengeksekusi	© Amorphis/iStockphoto
instruksi program; itu melaksanakan operasi aritmatika seperti penjumlahan, pengurangan,perkalian, dan pembagian; itu mengambil datadari memori eksternal atau perangkat dan tempatdata yang diproses ke dalam penyimpanan.</p>

<img src="G1.png" align="right" width=200>

<p align = "justify">Ada dua macam penyimpanan. Penyimpanan utama,atau memori, dibuat dari sirkuit elektronik yang dapat menyimpan data, asalkan:disuplai dengan tenaga listrik. Penyimpanan sekunder, biasanya hard disk (lihat Gambar 2)atau solid-state drive, menyediakan penyimpanan yang lebih lambat dan lebih murah yang bertahan tanpa
listrik. Sebuah hard disk terdiri dari piringan berputar, yang dilapisi dengan magnetnbahan. Solid-state drive menggunakan komponen elektronik yang dapat menyimpan informasitanpa daya, dan tanpa bagian yang bergerak.Untuk berinteraksi dengan pengguna manusia, komputer membutuhkan perangkat periferal. </p>

![G2](./G2.png)

<p align = "justify">Komputer mentransmisikan informasi (disebut output) kepada pengguna melalui layar tampilan,
speaker, dan printer. Pengguna dapat memasukkan informasi (disebut input) untuk komputerdengan menggunakan keyboard atau alat penunjuk seperti mouse.
Beberapa komputer adalah unit mandiri, sedangkan yang lain saling berhubungan
melalui jaringan. Melalui kabel jaringan, komputer dapat membaca data dan
program dari lokasi penyimpanan pusat atau mengirim data ke komputer lain. Untuk penggunadari komputer jaringan, bahkan mungkin tidak jelas data mana yang berada di komputeritu sendiri dan yang ditransmisikan melalui jaringan.<br><br>Instruksi dan data program (seperti teks, angka, audio, atau video) berada di sekunder penyimpanan atau di tempat lain di jaringan. Ketika sebuah program dimulai, instruksinyadibawa ke memori, di mana CPU dapat membacanya. CPU membaca dan
mengeksekusi satu instruksi pada suatu waktu. Seperti yang diarahkan oleh instruksi ini, CPU membacadata, memodifikasinya, dan menulisnya kembali ke memori atau penyimpanan sekunder. Beberapa programinstruksi akan menyebabkan CPU menempatkan titik-titik pada layar tampilan atau printer atau kegetaran speakernya.<br><br> Karena tindakan ini terjadi berkali-kali dan dengan kecepatan tinggi,pengguna manusia akan melihat gambar dan suara. Beberapa instruksi program membaca penggunamasukan dari keyboard, mouse, sensor sentuh, atau mikrofon. Analisis programsifat input ini dan kemudian mengeksekusi instruksi yang sesuai berikutnya.</p>

![G3](./G3.png)

<p align = "justify">Gambar 3 memberikan gambaran skematis arsitektur komputer pribadi.</p>

### __Komputasi & Masyarakat 1.1 Komputer Ada Dimana-mana__

<p align = "justify">Ketika komputer pertama kali ditemukan pada tahun 1940-an, komputer memenuhi seluruh ruangan.  Foto di bawah menunjukkan ENIAC (integrator numerik elektronik dan komputer), selesai pada tahun 1946 di University of Pennsylvania.  ENIAC digunakan oleh militer untuk menghitung lintasan proyektil.  Saat ini, fasilitas komputasi mesin pencari, toko internet, dan jejaring sosial memenuhi gedung-gedung besar yang disebut pusat data.  Di ujung lain spektrum, komputer ada di sekitar kita.  Ponsel Anda memiliki komputer di dalamnya, seperti halnya banyak kartu kredit dan kartu tarif untuk angkutan umum.  Sebuah mobil modern memiliki beberapa komputer––untuk mengontrol mesin, rem, lampu, dan radio.</p>

<img src="G4.png" align="right" width=300>

<p align = "justify">Munculnya komputasi di mana-mana berubah banyak aspek dari kami hidup.  Pabrik digunakan mempekerjakan orang untuk lakukan perakitan berulang tugas-tugas yang hari ini dilakukan oleh komputer- robot yang dikendalikan, operasi dimakan oleh segelintir orang siapa yang tahu caranya bekerja dengan komputer.  Buku, musik, dan film saat ini sering dikonsumsi di komputer, dan komputer hampir selalu terlibat dalam produksi mereka.  Buku yang sedang Anda baca sekarang tidak mungkin ditulis tanpa komputer. Mengetahui tentang komputer dan cara memprogramnya telah menjadi keterampilan penting dalam banyak karier.  Insinyur merancang mobil yang dikendalikan komputer dan peralatan medis yang menyelamatkan nyawa.  Ilmuwan komputer mengembangkan program yang membantu orang berkumpul untuk mendukung tujuan sosial.  Misalnya, para aktivis menggunakan jejaring sosial untuk berbagi video yang menunjukkan pelecehan oleh rezim yang represif, dan informasi ini berperan penting dalam mengubah opini publik. <br><br>Ketika komputer, besar dan kecil, menjadi semakin tertanam dalam kehidupan kita sehari-hari, semakin penting bagi setiap orang untuk memahami cara kerjanya, dan cara bekerja dengannya.  Saat Anda menggunakan buku ini untuk mempelajari cara memprogram komputer, Anda akan mengembangkan pemahaman yang baik tentang dasar-dasar komputasi yang akan membuat Anda menjadi warga negara yang lebih berpengetahuan dan, mungkin, seorang profesional komputasi.</p>

#
## __1.3 Bahasa Pemrograman Java__
<p align = "justify"></p>
<p align = "justify"></p>

<img src="G6.png" align="LEFT" width=200>

<p align = "justify">Untuk menulis program komputer, Anda perlu memberikan urutan instruksi yang dapat dieksekusi oleh CPU. Sebuah program komputer terdiri dari sejumlah besar program instruksi CPU sederhana, dan membosankan juga rawan untuk kesalahan untuk menentukannya satu persatu. Karena alasan itu, bahasa pemrograman tingkat tinggi telah dibuat. Dalam bahasa tingkat tinggi, Anda menentukan tindakan yang harus dilakukan programnya. Penyusun menerjemahkan instruksi tingkat tinggi ke dalam instruksi yang lebih rinci (disebut kode mesin) yang dibutuhkan oleh CPU. Banyak bahasa pemrograman yang berbeda telah dirancang untuk tujuan yang berbeda.</P>

<img src="G7.png" align="right" width=250>

 <p align = "justify">Pada tahun 1991, sebuah kelompok yang dipimpin oleh James Gosling dan Patrick Naughton di Sun Microsystems merancang sebuah bahasa pemrograman, berkode nama “Green”, untuk kegunaan di perangkat konsumen, seperti “set-top” televisi cerdas. Bahasanya dirancang untuk sederhana, aman, dan dapat digunakan oleh berbagai tipe prosesor yang berbeda. Tidak ada pelanggan yang pernah ditemukan untuk teknologi ini.<br><br>Gosling menceritakan pada tahun 1994 tim menyadari “Kita bisa menulis browser yang sangat keren. Itu adalah salah satu dari sedikit hal dalam arus utama klien/server yang membutuhkan beberapa hal aneh yang telah kami lakukan: arsitektur netral, waktu nyata, andal, aman.” Java diperkenalkan kepada orang banyak yang antusias di pameran SunWorld pada tahun 1995, bersama dengan browser yang menjalankan applet—kode Java yang dapat ditemukan di mana saja di Internet. Gambar di sebelah kanan menunjukkan contoh khas applet.<br><br>Sejak saat itu, Java telah berkembang dengan kecepatan yang fenomenal. Programmer telah menggunakan bahasa ini karena lebih mudah digunakan daripada saingan terdekatnya, C++. Selain itu, Java memiliki perpustakaan yang kaya yang memungkinkan untuk menulis program portabel yang dapat melewati sistem operasi berpemilik—fitur yang sangat dicari oleh mereka yang ingin menjadi independen dari sistem berpemilik tersebut dan diperjuangkan dengan sengit oleh vendor mereka.Karena Java dirancang untuk internet, ia mempunyai dua atrbut yang membuatnya sangat cocok untuk pemula: keamanan dan portabilitas.</p>

![G8](./G8.png)

 <p align = "justify">Java dirancang sehingga siapapun dapat menjalankan program di browser mereka tanpa takut. Fitur keamanan bahasa Java memastikan program dihentikan apabila mencoba untuk melakukan sesuatu membahayakan. Memiliki lingkungan yang aman juga membantu bagi siapapun yang mempelajari Java. Disaat Anda melakukan error yang mengakibatkan perilaku membahayakan, program Anda dihentikan dan Anda menerima laporan eror yang akurat<br><br>Manfaat lain dari Java adalah portabilitas. Program Java yang sama akan jalan, tanpa perubahan, pada Windows, UNIX, Linux, atau Macintosh. Untuk mencapai portabilitas, penyusun Java tidak menerjemahkan program-program Java langsung ke dalam instruksi CPU. Melainkan, program Java yang tersusun memuat instruksi untuk mesin virtual Java, sebuah program yang menyimulasikan CPU nyata. Portabilitas adalah manfaat lain untuk murid pemula. Anda tidak harus belajar bagaimana cara menulis program untuk platform yang berbeda.<br><br>Saat ini, Java telah ditetapkan sebagai salah satu bahasa yang paling penting untuk pemrograman umum serta untuk instruksi ilmu komputer. Namun, meskipun Java adalah bahasa yang baik untuk pemula, tapi tidak sempurna, karena tiga alasan.<br><br>Karena Java tidak dirancang khusus untuk siswa, tidak ada pemikiran yang diberikan untuk membuatnya sangat sederhana untuk menulis program dasar. Sejumlah mesin teknis diperlukan untuk menulis bahkan program yang paling sederhana. Hal ini bukan masalah bagi programmer profesional, tetapi bisa menjadi gangguan bagi pelajar pemula. Saat Anda mempelajari caranya untuk memprogram di Java, akan ada saatnya Anda akan diminta untuk puas dengan penjelasan awal dan menunggu detail yang lebih lengkap di bab selanjutnya.<br><br>Java telah diperpanjang berkali-kali selama masa pakainya—lihat Table 1. Dalam buku ini, kami menganggap bahwa Anda memiliki Java versi 8 atau yang lebih baru.Pada akhirnya, Anda tidak dapat berharap untuk mempelajari keseluruhan dari Java dalam satu pembelajaran. Bahasa Java itu sendiri relatif sederhana, tapi Java berisi sekumpulan library packages yang diperlukan untuk menulis program yang berguna. Ada paket untuk grafik, desain antarmuka pengguna, kriptografi, jaringan, suara, penyimpanan basis data, dan banyak kegunaan lainnya. Bahkan programmer Java yang ahli sekalipun tidak dapat berharap untuk mengetahui isi semua paket—mereka hanya menggunakan yang mereka perlukan untuk proyek tertentu.<br><br>Dengan  menggunakan buku ini, Anda diharapkan untuk belajar banyak tentang bahasa Java dan tentang paket yang paling penting. Camkan selalu bahwa tujuan utama dari buku ini bukan untuk Anda mengingat detail kecil Java, tapi untuk mengajari Anda cara berpikir tentang pemrograman.

#
## __1.4	Menjadi Familiar dengan Lingkungan Pemrograman Anda__

<p align = "justify">Banyak siswa menemukan bahwa alat yang mereka butuhkan sebagai pemrogram sangat berbeda dari perangkat lunak yang mereka kenal. Anda harus meluangkan waktu untuk membiasakan diri dengan lingkungan pemrograman Anda. Karena sistem komputer sangat bervariasi, buku ini hanya dapat memberikan garis besar langkah-langkah yang perlu Anda ikuti. Merupakan ide bagus untuk Anda berpartisipasi dalam lab praktik, atau meminta teman yang berpengetahuan luas untuk memberi Anda penjelasan.</p>

![G9](./G9.png)

<p align = "justify"><b>Langkah 1<b> Mulai lingkungan pengembangan Java.<br>
Sistem komputer sangat berbeda dalam hal ini. Pada banyak komputer terdapat lingkungan pengembangan terintegrasi di mana Anda dapat menulis dan menguji program Anda.
Di komputer Anda pertama kali meluncurkan editor, sebuah program yang berfungsi seperti pengolah kata, di mana Anda dapat memasukkan instruksi Java Anda; Anda kemudian membuka jendela konsol dan ketik perintah untuk menjalankan program Anda. Anda perlu mencari tahu bagaimana memulai dengan lingkungan Anda.<br><br><b>Langkah 2 <b>Tulis sebuah program yang sederhana.<br>
Pilihan tradisional untuk program pertama dalam bahasa pemrograman baru adalah program yang menampilkan sapaan sederhana: “Halo, Dunia!”. Mari kita ikuti tradisi itu. Inilah "Halo, Dunia!" program di java:<br>publicclassHelloPrinter<br>
{<br>
publicstaticvoidmain(String[]args)<br>
{<br>
<br>System.out.println("Hello,World!");<br>
}<br>
}<br><br>
Kami akan memeriksa program ini di bagian selanjutnya.<br><br>
Apa pun lingkungan pemrograman yang Anda gunakan, Anda memulai aktivitas Anda dengan mengetikkan pernyataan program ke dalam jendela editor.<br><br>
Buat file baru dan beri namaHelloPrinter.java, menggunakan langkah-langkah yang sesuai untuk lingkungan Anda. (Jika lingkungan Anda mengharuskan Anda memberikan nama proyek selain nama file, gunakan namahello untuk proyek tersebut.) Masukkan instruksi program persis seperti yang diberikan di atas. Atau, temukan salinan elektronik dalam kode pendamping buku ini dan tempelkan ke editor Anda.<br><br>

![G8](./G10.png)

<p align = "justify">Saat Anda menulis program ini, perhatikan baik-baik berbagai simbol, dan ingatlah bahwa Java sensitif terhadap huruf besar-kecil. Anda harus memasukkan huruf besar dan kecil persis seperti yang muncul dalam daftar program. Anda tidak dapat mengetikMAIN atauPrintLn. Jika Anda tidak hati-hati, Anda akan mengalami masalah—lihat Kesalahan Umum 1.2.<br><br><b>Langkah 3</b> Jalankan programnya.<br><br>Proses untuk menjalankan program sangat bergantung pada lingkungan pemrograman Anda. Anda mungkin harus mengklik tombol atau memasukkan beberapa perintah. Saat Anda menjalankan program pengujian, pesannya.<br><br>
Hello,World!<br><br>
akan muncul di suatu tempat di layar (lihat Gambar 4 dan Gambar 5).<br><br>
Untuk menjalankan program Anda, kompiler Java menerjemahkan file sumber Anda (yaitu, pernyataan yang Anda tulis) ke dalam file kelas. (Sebuah file kelas berisi instruksi untuk mesin virtual Java.) Setelah kompilator menerjemahkan kode sumber Anda ke dalam instruksi mesin virtual, mesin virtual akan mengeksekusinya. Selama eksekusi, mesin virtual mengakses pustaka kode yang telah ditulis sebelumnya, termasuk implementasi kelasSystem danPrintStream yang diperlukan untuk menampilkan keluaran program. Gambar 6 merangkum proses membuat dan menjalankan program Java. Di beberapa lingkungan pemrograman, kompilator dan mesin virtual pada dasarnya tidak terlihat oleh pemrogram—mereka dijalankan secara otomatis setiap kali Anda meminta untuk menjalankan program Java. Di lingkungan lain, Anda perlu meluncurkan kompiler dan mesin virtual secara eksplisit.<br><br>
<b>Langkah 4 Rapikan pekerjaanmu.</b><br>
Sebagai seorang programmer, Anda menulis program, mencobanya, dan memperbaikinya. Anda menyimpan program Anda dalam file. File disimpan dalam folder atau direktori. Sebuah folder dapat berisi

![G11](./G11.png)

file serta folder lain, yang dengan sendirinya dapat berisi lebih banyak file dan folder 
(lihat Gambar 7). Hirarki ini bisa sangat besar, dan Anda tidak perlu khawatir dengan semua cabangnya. Namun, Anda harus membuat folder untuk mengatur pekerjaan Anda. Sebaiknya buat folder terpisah untuk pro-tugas mata kuliah tata bahasa. Di dalam folder itu, buat folder terpisah untuk setiap program.Beberapa lingkungan pemrograman menempatkan program Anda ke lokasi default jika Anda tidak menentukan folder sendiri. Dalam hal ini, Anda perlu mencari tahu di mana file-file itu berada.Pastikan Anda memahami di mana file Anda berada dalam hierarki folder. Informasi ini penting ketika Anda mengirimkan file untuk penilaian, danuntukmembuat salinan cadangan (lihat Tip Pemrograman 1.1).</p>
#
---
### __Tip Pemrograman 1.1__
### _Salinan Cadangan_

<p align = "justify"> Anda akan menghabiskan banyak waktu untuk membuat dan meningkatkan program Java. Sangat mudah untuk menghapus file secara tidak sengaja, dan terkadang file hilang karena kerusakan komputer. Mengetik ulang konten file yang hilang membuat frustrasi dan memakan waktu. Oleh karena itu, sangat penting bagi Anda untuk mempelajari cara melindungi file dan membiasakannya jikamelakukannya sebelum bencana terjadi. Mencadangkan file di memoristick adalah metode penyimpanan yang mudah dan nyaman bagi banyak orang. Bentuk pencadangan lain yang semakin populer adalah penyimpanan file Internet<br><br>Berikut adalah beberapa petunjuk yang perlu diingat:<br>
•	Sering-seringlah membuat cadangan. Mencadangkan file hanya membutuhkan beberapa detik, dan Anda akan membenci diri sendiri jika harus menghabiskan banyak waktu untuk membuat ulang pekerjaan yang sebenarnya bisa Anda simpan dengan mudah. Saya sarankan Anda mencadangkan pekerjaan Anda setiap tiga puluh menit sekali.<br>
•	Putar cadangan. Gunakan lebih dari satu direktori untuk cadangan, dan putar mereka. Artinya, back up dulu ke direktori pertama. Kemudian kembali ke direktori kedua. Kemudian gunakan yang ketiga, lalu kembali ke yang pertama. Dengan begitu Anda selalu memiliki tiga cadangan terbaru. Jika perubahan terbaru Anda memperburuk keadaan, Anda dapat kembali ke versi yang lebih lama.<br>
•	Perhatikan arah pencadangan. Pencadangan melibatkan penyalinan file dari satu tempat ke tempat lain. Anda harus melakukannya dengan benar—yaitu, menyalin dari lokasi kerja Anda ke lokasi pencadangan. Jika Anda melakukannya dengan cara yang salah, Anda akan menimpa file yang lebih baru dengan versi yang lebih lama.<br>
•	Periksa cadangan Anda sesekali. Periksa kembali apakah cadangan Anda berada di tempat yang Anda pikirkan. Tidak ada yang lebih membuat frustrasi daripada mengetahui bahwa cadangan tidak ada saat Anda membutuhkannya.<br>
•	Santai, lalu pulihkan. Saat Anda kehilangan file dan perlu memulihkannya dari cadangan, kemungkinan besar Anda berada dalam keadaan gelisah dan tidak bahagia. Ambil napas dalam-dalam dan pikirkan proses pemulihan sebelum Anda mulai. Bukan hal yang aneh bagi pengguna komputer yang gelisah untuk menghapus cadangan terakhir ketika mencoba memulihkan file yang rusak.</p>

#
## __1.5 Menganalisis Program Pertama Anda__

<img src="G12.png" align="left" width=100>
<p align = "justify">Pada bagian ini, kitaakanmenganalisis program Java pertamasecararinci. Di siniadalahkodesumber.</p>

<p><img src="G13.png" align="right" width=450></p>

<p align = "justify">
Garis<br>public class HelloPrinte<br>menunjukkandeklarasikelas yang disebutHelloPrinter. 
Setiap program Java terdiridarisatuataulebihkelas.<br>Kitaakanmembahaskelassecaralebihrinci di Bab 2 dan 3.<br>Kata publikmenunjukkanbahwakelasdapatdigunakan oleh "publik". Anda kemudianakanmenemukanfiturpribadi.<br>Di Java, setiap file sumberdapatberisi paling banyaksatukelaspublik, dan namakelaspublikharussesuaidengannama file yang berisikelastersebut.<br>Misalnya, kelasHelloPrinterharusdimuatdalam file bernamaHelloPrinter.java.<br>Konstruksi<br>public static void main(String[] args) <br>{ 
. . . <br>}<br><br>mendeklarasikan metode yang disebut main. Metode berisi kumpulan instruksi pemrograman yang menjelaskan bagaimana melakukan tugas tertentu.
Setiap aplikasi Java harus memiliki metode utama. Sebagian besar program Java berisi metode lain selain utama, dan Anda akan melihat di Bab 3 cara menulis metode lain.
Istilah statis dijelaskan secara lebih rinci dalam Bab 8, dan arti dari String[ ] args dibahas dalam Bab 11. Pada saat ini, cukup pertimbangkan. <br>public class ClassName<br>{ <br>public static void main(String[] args) <br>{ <br>  . . . <br>} <br>} <br><br>sebagai bagian dari "pipa" yang diperlukan untuk membuat program Java. Program pertama kita memiliki semua instruksi di dalam metode main kelas.<br><br>Metode main berisi satu atau lebih instruksi yang disebut pernyataan. Setiap pernyataan diakhiri dengan titik koma (;). Ketika sebuah program dijalankan, pernyataan dalam metode utama dieksekusi satu per satu.</p>

![](./G14.png)

<p align ="justify">Dalam contoh program kita, metode utama memiliki satu pernyataan:<br>System.out.println("Hello, World!");<br>Pernyataan ini mencetak sebaris teks, yaitu “Hello, World!”. Dalam pernyataan ini, kita memanggil metode yang, untuk alasan yang tidak akan kita jelaskan di sini, ditentukan dengan nama System.out.println yang agak panjang.<br><br>Kita tidak harus mengimplementasikan metode ini—programmer yang menulis library Java sudah melakukannya untuk kita. Kita hanya ingin metode melakukan tugas yang dimaksudkan, yaitu mencetak nilai.<br><br>Setiap kali Anda memanggil metode di Java, Anda perlu menentukan<br>1. Metode yang ingin Anda gunakan (dalam hal ini, System.out.println).<br>2. Nilai apa pun yang dibutuhkan metode untuk menjalankan tugasnya (dalam hal ini, "Hello, World!"). Istilah teknis untuk nilai seperti itu adalah argumen. Argumen diapit dalam tanda kurung. Beberapa argumen dipisahkan dengan koma.<br><br>Urutan karakter yang diapit tanda kutip<br>"Hello, World!"<br>disebut string. Anda harus menyertakan isi string di dalam tanda kutip sehingga kompilator mengetahui maksud Anda secara harfiah "Hello, World!". Ada alasan untuk persyaratan ini. Misalkan Anda perlu mencetak kata main. Dengan melampirkannya dalam tanda kutip, "main", kompiler tahu maksud Anda urutan karakter m a i n,
bukan metode bernama main. Aturannya sederhana, Anda harus menyertakan semua string teks dalam tanda kutip, sehingga kompilator menganggapnya sebagai teks biasa dan tidak mencoba menafsirkannya sebagai instruksi program.<br><br>Anda juga dapat mencetak nilai numerik. Misalnya pernyataan<br>System.out.println(3 + 4);<br>mengevaluasi ekspresi 3 + 4 dan menampilkan angka 7.
<br><br>Metode System.out.println mencetak string atau angka dan kemudian memulai baris baru. Misalnya, urutan pernyataann<br>System.out.println("Hello"); <br>System.out.println("World!");<br>mencetak dua baris teks:<br>Hello <br>World!<br><br>Ada metode kedua, System.out.print, yang dapat Anda gunakan untuk mencetak item tanpa memulai baris baru. Misalnya, output dari dua pernyataan<br>System.out.print("00");<br>System.out.println(3 + 4);<br>adalah garis tunggal<br>007</p>

#
### __Kesalahan Umum 1.1__
### _Menghilangkan Titik Koma_

<p align = "justify">Di Java setiap pernyataan harus diakhiri dengan titik koma. Lupa mengetik titik koma adalah kesalahan umum. Ini membingungkan kompiler, karena kompiler menggunakan titik koma untuk menemukan di mana satu pernyataan berakhir dan yang berikutnya dimulai. Kompilator tidak menggunakan jeda baris atau kurung kurawal untuk mengenali akhir pernyataan. Misalnya, kompiler menganggap<br>System.out.println("Hello")<br> System.out.println("World!");<br><br>satu pernyataan, seolah-olah Anda telah menulis<br>System.out.println("Hello")<br>System.out.println("World!");<br><br>Kemudian tidak mengerti pernyataan itu, karena tidak mengharapkan kata Sistem mengikuti kurung penutup setelah "Hello".
Obatnya sederhana. Pindai setiap pernyataan untuk mencari titik koma, sama seperti Anda akan memeriksa bahwa setiap kalimat bahasa Inggris diakhiri dengan tanda titik. Namun, jangan menambahkan titik koma di akhir public class Hello atau public static void main. Garis-garis ini bukan pernyataan.

## __1.6 Kesalahan__

<img src="G15.png" align="left" width=200>

<p align = "justify">Bereksperimenlah sedikit dengan program HelloPrinter. Apa yang terjadi jika Anda membuat kesalahan pengetikan seperti<br>System.ou.println("Hello, World!");<br>System.out.println("Hello, Word!");<br>Dalam kasus pertama, kompiler akan mengeluh. Kompiler akan mengatakan bahwa ia tidak tahu apa yang Anda maksud dengan ou. Kata-kata yang tepat dari pesan kesalahan tergantung pada lingkungan pengembangan Anda, tetapi mungkin seperti "Tidak dapat menemukan simbol ou". Ini adalah kesalahan waktu-kompilasi. Ada yang salah menurut aturan bahasa dan kompiler menemukannya. Untuk alasan ini, kesalahan waktu kompilasi sering disebut kesalahan sintaksis. Ketika kompilator menemukan satu atau lebih kesalahan, ia menolak untuk menerjemahkan program ke dalam instruksi mesin virtual Java, dan sebagai konsekuensinya Anda tidak memiliki program yang dapat dijalankan. Anda harus memperbaiki kesalahan dan mengkompilasi lagi. Faktanya, kompilator cukup pilih-pilih, dan adalah umum untuk melewati beberapa putaran memperbaiki kesalahan waktu kompilasi sebelum kompilasi berhasil untuk pertama kalinya.
Jika kompiler menemukan kesalahan, itu tidak akan berhenti dan menyerah begitu saja. Kompiler akan mencoba melaporkan kesalahan sebanyak yang dapat ditemukan, sehingga Anda dapat memperbaiki semuanya sekaligus.<br>Terkadang, kesalahan membuat kompiler keluar jalur. Misalkan, misalnya, Anda lupa tanda kutip di sekitar string: System.out.println(Hello, World!). Kompiler tidak akan mengeluh tentang tanda kutip yang hilang. Sebagai gantinya, kompiler akan melaporkan "Tidak dapat menemukan simbol Hello". Sayangnya, kompilernya tidak terlalu pintar dan tidak menyadari bahwa Anda bermaksud menggunakan string. Terserah Anda untuk menyadari bahwa Anda perlu menyertakan string dalam tanda kutip.<br>Kesalahan pada baris kedua di atas adalah jenis yang berbeda. Program akan dikompilasi dan dijalankan, tetapi outputnya akan salah. Ini akan mencetak<br>Hello, Word!<br>Ini adalah kesalahan run-time. Program ini secara sintaksis benar dan melakukan sesuatu, tetapi tidak melakukan apa yang seharusnya dilakukan. Karena kesalahan run-time disebabkan oleh kelemahan logis dalam program, mereka sering disebut kesalahan logika.<br>Kesalahan run-time khusus ini tidak menyertakan pesan kesalahan. Itu hanya menghasilkan output yang salah. Beberapa jenis kesalahan run-time sangat parah sehingga menghasilkan pengecualian: pesan kesalahan dari mesin virtual Java. Misalnya, jika program Anda menyertakan pernyataan<br>System.out.println(1 / 0);<br>Anda akan mendapatkan pesan kesalahan run-time "Pembagian dengan nol".<br>Selama pengembangan program, kesalahan tidak dapat dihindari. Begitu sebuah program lebih panjang dari beberapa baris, itu akan membutuhkan konsentrasi manusia super untuk memasukkannya dengan benar tanpa tergelincir satu kali pun. Anda akan menemukan diri Anda menghilangkan titik koma atau tanda kutip lebih sering daripada yang Anda inginkan, tetapi kompilator akan melacak masalah ini untuk Anda.<br>Kesalahan run-time lebih merepotkan. Kompilator tidak akan menemukannya—sebenarnya, kompilator akan dengan senang hati menerjemahkan program apa pun selama sintaksnya benar—tetapi program yang dihasilkan akan melakukan kesalahan. Ini adalah tanggung jawab pembuat program untuk menguji program dan menemukan kesalahan run-time.</p>

### __Kesalahan Umum 1.2__
### _Kata-kata yang salah eja_

<p align = "justify"> Jika Anda secara tidak sengaja salah mengeja kata, maka hal-hal aneh mungkin terjadi, dan mungkin tidak selalu jelas dari pesan kesalahan apa yang salah. Berikut adalah contoh yang baik tentang bagaimana kesalahan ejaan sederhana dapat menyebabkan masalah:<br>public class<br>HelloPrinter<br>{<br>public static void Main(String[] args)<br>{<br> 
System.out.println("Hello, World!");<br>}<br>}<br><br>Kelas ini mendeklarasikan sebuah metode yang disebut Main. Kompiler tidak akan menganggap ini sama dengan metode main, karena Main dimulai dengan huruf besar dan bahasa Java peka huruf besar/kecil. Huruf besar dan kecil dianggap benar-benar berbeda satu sama lain, dan bagi kompiler Main tidak lebih cocok untuk main daripada rain. Kompiler akan dengan senang hati mengkompilasi metode Main Anda, tetapi ketika mesin virtual Java membaca file yang dikompilasi, ia akan mengeluh tentang metode utama yang hilang dan menolak untuk menjalankan program. Tentu saja, pesan "metode utama yang hilang" akan memberi Anda petunjuk di mana mencari kesalahan.<br>Jika Anda mendapatkan pesan kesalahan yang tampaknya menunjukkan bahwa kompiler atau mesin virtual berada di jalur yang salah, periksa ejaan dan kapitalisasi. Jika Anda salah mengeja nama simbol (misalnya, ou alih-alih out), kompilator akan menghasilkan pesan seperti "tidak dapat menemukan sym bol ou". Pesan kesalahan itu biasanya merupakan petunjuk bagus bahwa Anda membuat kesalahan ejaan.</p>

#
## __1.7 Pemecahan Masalah: Desain Algoritma__
<p align = "justify">Anda akan segera belajar bagaimana memprogram perhitungan dan pengambilan keputusan di Java. Tetapi sebelum kita melihat mekanisme penerapan perhitungan di bab berikutnya, mari kita pertimbangkan bagaimana Anda dapat menjelaskan langkah-langkah yang diperlukan untuk menemukan solusi dari suatu masalah.</p>

### __1.7.1 Konsep Algoritma__

<img src="G16.png" align="left" width=200>

<p align = "justify"> Anda mungkin telah menemukan iklan yang mendorong Anda untuk membayar layanan terkomputerisasi mencocokkan Anda dengan pasangan cinta. Memikirkan bagaimana ini bisa berhasil. Anda mengisi formulir dan kirimkan. Yang lain melakukan hal yang sama. Data diproses oleh program komputer. Apakah masuk akal untuk asumsikan bahwa komputer dapat melakukan tugasmenemukan pasangan terbaik untuk Anda? Misalkan Anda adik laki-laki, bukan komputer, memiliki semua formulir di mejanya. Instruksi apa yang bisa Anda berikan? memberinya? Anda tidak bisa mengatakan, “Temukan yang paling tampan orang yang suka inline skating dan browsing internet”. Tidak ada standar objektif untuk ketampanan, dan pendapat saudaramu (atau itu program komputer yang menganalisis foto calon mitra) kemungkinan akan berbeda dari milik Anda. Jika Anda tidak dapat memberikan instruksi tertulis kepada seseorang untuk menyelesaikannya masalah, tidak mungkin komputer secara ajaib dapat menemukan solusi yang tepat. Itu komputer hanya dapat melakukan apa yang Anda perintahkan. Itu hanya melakukannya lebih cepat, tanpa mendapatkan bosan atau lelah.<br><br>Oleh karena itu, layanan pembuatan jodoh yang terkomputerisasi tidak dapat menjamin untuk menemukanpasangan yang optimal untuk Anda. Sebagai gantinya, Anda mungkin disajikan dengan serangkaian calon mitra yang memiliki minat yang sama dengan Anda. Itu adalah tugas yang program computer dapat memecahkan.<br><br>Agar program komputer memberikan jawaban atas masalah yang menghitung
jawaban, itu harus mengikuti urutan langkah-langkah yang<br>• Jelas<br>• Dapat dijalankan<br>• Mengakhiri<br><br>Urutan langkah tidak ambigu ketika ada instruksi yang tepat tentang apa yang harus dilakukan pada setiap langkah dan kemana harus pergi selanjutnya. Tidak ada ruang untuk menebak atau pendapat pribadi. Sebuah langkah dapat dieksekusi ketika itu dapat dilaksanakan dalam praktek. Misalnya, komputer dapat mencantumkan semua orang yang memiliki hobi yang sama dengan Anda, tapi itu tidak bisa memprediksi siapa yang akan menjadi pasangan seumur hidup Anda. Akhirnya, urutan langkah berakhir jika pada akhirnya akan berakhir. Sebuah program yang terus bekerja tanpa memberikan jawaban adalah jelas tidak berguna.</p>

<img src="G17.png" align="right" width=200>

<p align = "justify">Urutan langkah yang tidak ambigu, dapat dieksekusi, dan diakhiri disebut algoritma. Meskipun tidak ada algoritme untuk menemukan pasangan, banyak masalah memiliki algoritme untuk diselesaikan mereka. Bagian berikutnya memberikan contoh.</p>

### __1.7.2 Algoritma untuk Memecahkan Masalah Investasi__

<p align = "justify">Pertimbangkan masalah investasi berikut:
Anda memasukkan $10.000 ke dalam rekening bank yang menghasilkan bunga 5 persen per tahun. Berapa banyak tahun yang diperlukan agar saldo akun menjadi dua kali lipat dari aslinya?
Bisakah Anda memecahkan masalah ini dengan tangan? Tentu, Anda bisa. Anda mengetahui keseimbangannya sebagai berikut:<br><br>Anda terus berjalan sampai saldo setidaknya $20.000. Kemudian angka terakhir di tahun inikolom adalah jawabannya.
Tentu saja, melakukan perhitungan ini sangat membosankan bagi Anda atau adik laki-laki Anda. Tetapi komputer sangat pandai melakukan perhitungan berulang dengan cepat dan tanpa cacat. Yang penting bagi komputer adalah deskripsi langkah-langkah untuk menemukan solusi. Setiap langkah harus jelas dan tidak ambigu, tidak memerlukan tebak-tebakan. Berikut adalah deskripsi seperti itu:<br>Setel tahun ke 0, saldo ke 10.000.<br>Ketika saldo kurang dari $20,000<br>Tambahkan 1 ke tabel tahun.<br>Tetapkan bunga ke saldo x 0,05 (yaitu, bunga 5 persen).<br>Tambahkan bunga ke saldo<br><br><i>Laporan tahun sebagai jawabannya.</i><br>Langkah-langkah ini termasuk dalam bahasa yang belum dapat dipahami oleh komputer, tapi kamu akan segera belajar bagaimana merumuskannya dalam Java. Deskripsi ini disebut dengan pseudocode. Kami membahas aturan untuk menulis pseudocode di bagian selanjutnya.</p>

#
### __1.7.3 Pseudocode__
<p align = "justify">Tidak ada persyaratan ketat untuk pseudocode karena dibaca oleh manusia,bukan program komputer. Berikut adalah jenis-jenis pernyataan pseudocode dan bagaimana kita akan menggunakan penerapannya dalam buku ini:<br>•	Gunakan pernyataan seperti berikut ini untuk menjelaskan bagaimana suatu nilai ditetapkan atau diubah:<br>biaya total = harga beli + biaya operasi<br>Kalikan nilai saldo dengan 1,05.<br>Hapus karakter pertama dan terakhir dari kata.<br>•	Jelaskan keputusan dan pengulangan sebagai berikut:<br>Jika total biaya 1 < total biaya 2<br>Ketika saldo kurang dari $20,000<br>Untuk setiap gambar dalam urutan<br>Gunakan lekukan untuk menunjukkan pernyataan mana yang harus dipilih atau diulang:<br>Untuk setiap mobil<br>biaya operasi = 10 x biaya bahan bakar tahunan<br>biaya total = harga beli + biaya operasi<br>Di sini, lekukan menunjukkan bahwa kedua pernyataan harus dieksekusi untuk setiap mobil.<br>•	Tunjukkan hasil dengan pernyataan seperti:<br>Pilih mobil1.<br>
Laporkan tahun sebagai jawabannya.</p>

#
### __1.7.4 Dari Algoritma ke Program__

<p align = "justify">Di Bagian 1.7.2, kami mengembangkan pseudocode untuk menemukan berapa lama waktu yang dibutuhkan untuk menggandakan investasi. Mari kita periksa kembali bahwa pseudocode mewakili suatu algoritma itu . adalah bahwa pseudocode itu jelas, dapat dieksekusi, dan diakhiri.<br><br>Pseudocode kami jelas. Ini hanya memberi tahu cara memperbarui nilai di setiap langkah. Pseudocode dapat dieksekusi karena kami menggunakan tingkat bunga tetap. Apakah kami mengatakan untuk menggunakan tingkat bunga aktual yang akan dibebankan di tahun-tahun mendatang, dan bukan tingkat bunga tetap 5 persen per tahun, instruksi tidak akan dapat dieksekusi. Tidak ada jalan bagi siapa pun untuk mengetahui berapa tingkat bunga di masa depan. Ini membutuhkan sedikit berpikir untuk melihat bahwa langkah-langkahnya berakhir: Dengan setiap langkah, keseimbangan naik setidaknya $ 500, jadi akhirnya harus mencapai $ 20.000.<br><br>Oleh karena itu, kami telah menemukan algoritme untuk menyelesaikan masalah investasi kami, dan kami tahu kami dapat menemukan solusinya dengan memprogram komputer. Keberadaan algoritma adalah prasyarat penting untuk memprogram tugas. Anda harus terlebih dahulu algoritma untuk tugas anda sebelum Anda memulai pemrograman (lihat Angka 8). Dalam bab-bab berikutnya, Anda akan mempelajari cara mengekspresikan algoritme dalam bahasa Java.</p>

#
### __BAGAIMANA 1.1__

### _Menjelaskan algoritma dengan Pseudocode_

<p align = "justify">Ini adalah yang pertama dari banyak cara bagian dalam buku ini yang memberikan Anda langkah-demi-langkah prosedur untuk melaksanakan tugas-tugas penting dalam mengembangkan program komputer.<br><br>Sebelum Anda siap untuk menulis sebuah program di Java, Anda perlu mengembangkan metode algorithma untuk tiba di solusi untuk masalah tertentu menggambarkan algoritma di pseudocode urutan langkah-langkah yang tepat dirumuskan dalam bahasa Inggris untuk menggambarkan, kami akan merancang sebuah algoritma untuk masalah ini:<br><img src="G21.png" align="right" width=200><br><b>Pernyataan Masalah<b>	 Anda memiliki pilihan untuk membeli salah satu dari dua mobil. Satu lebih hemat bahan bakar daripada yang lain, tetapi juga lebih mahal.<br>Anda tahu harga dan efisiensi bahan bakar (dalam mil per galon, mpg) dari kedua mobil. Anda berencana untuk menyimpan mobil selama sepuluh tahun. Asumsikan harga $4 per galon gas dan penggunaan 15.000 mil per tahun. Anda akan membayar tunai untuk mobil dan tidak khawatir tentang biaya pembiayaan. Mobil mana yang lebih baik?<br><p align = "justify"><b>Langkah 1</b>	Tentukan input dan output.<br> Dalam contoh soal kami, kami memiliki input ini:<br>• Harga beli1 dan efisiensi bahan bakar1, harga dan efisiensi bahan bakar (dalam mpg) mobil pertama.<br>• Harga beli2 dan efisiensi bahan bakar2, harga dan efisiensi bahan bakar mobil kedua.<br>Kami hanya ingin tahu mobil mana yang lebih baik dibeli. Itu adalah keluaran (output) yang diinginkan.<br><br><b>Langkah 2</b> Memecah masalah menjadi tugas-tugas yang lebih kecil.<br>Untuk setiap mobil, kita perlu mengetahui total biaya mengemudinya. Mari kita lakukan perhitungan ini secara terpisah untuk setiap mobil. Setelah kita memiliki total biaya untuk setiap mobil, kita dapat memutuskan mobil mana yang lebih baik.
Total biaya untuk setiap mobil adalah harga beli + biaya operasional.<br>Kami mengasumsikan penggunaan konstan dan harga gas selama sepuluh tahun, sehingga biaya operasi tergantung pada biaya mengemudi mobil selama satu tahun.
Biaya operasi adalah 10 x biaya bahan bakar tahunan.
Biaya bahan bakar tahunan adalah harga per galon x bahan bakar tahunan yang dikonsumsi.<br>Bahan bakar tahunan yang dikonsumsi adalah jarak tempuh tahunan / efisiensi bahan bakar. Misalnya, jika Anda mengendarai mobil sejauh 15.000 mil dan efisiensi bahan bakarnya 15 mil/galon, mobil tersebut mengkonsumsi 1.000 galon.<br><br><b>Langkah 3</b>Jelaskan setiap subtugas dalam pseudocode.<br>Dalam uraian Anda, atur langkah-langkahnya sehingga setiap nilai antara dihitung sebelum diperlukan dalam perhitungan lain. Misalnya, daftar langkah:<br>biaya total = harga pembelian + biaya operasi<br>Setelah Anda menghitung biaya operasi. <br>Berikut adalah algoritma untuk memutuskan mobilmana yang akan dibeli:<br>Untuk setiap mobil, hitung total biaya sebagai berikut: <br>konsumsi bahan bakar tahunan = jarak tempuh tahunan / efisiensi bahan bakar <br>biaya bahan bakar tahunan = harga per galon x konsumsi bahan bakar tahunan <br>biaya operasional = 10 x biaya bahan bakar tahunan <br>total biaya = harga beli + biaya operasional <br>Jika total biaya mobil1 < total biaya mobil2<br>Pilih mobil1. <br>Lainnya<br>Pilih mobil2.<br><br><b>Langkah 4</b> Uji pseudocode Anda dengan mengerjakan soal.<br>Kami akan menggunakan nilai sampel ini: <br>Mobil 1: $25.000, 50 mil/galon <br>Mobil 2: $20.000, 30 mil/galon <br><br>Berikut adalah perhitungan biaya mobil pertama:<br>konsumsi bahan bakar tahunan = jarak tempuh tahunan / efisiensi bahan bakar = 15000 / 50 = 300 <br>biaya bahan bakar tahunan = harga per galon x konsumsi bahan bakar tahunan = 4 x 300 = 1200 <br>biaya operasi = 10 x biaya bahan bakar tahunan = 10 x 1200 = 12000 <br>total biaya = harga pembelian + biaya operasi = 25000 + 12000 = 37000 <br>Demikian pula, total biaya untuk mobil kedua adalah $ 40.000. Oleh karena itu, keluaran dari algoritma adalah memilih mobil 1.<br><br>Contoh Kerja berikut menunjukkan bagaimana menggunakan konsep-konsep dalam bab ini dan langkah-langkah dalam Cara untuk memecahkan masalah lain. Dalam hal ini, Anda akan melihat bagaimana mengembangkan algoritme untuk meletakkan ubin dalam pola warna yang bergantian. Anda harus membaca Contoh yang Dikerjakan untuk meninjau apa yang telah Anda pelajari, dan untuk bantuan dalam mengatasi masalah lain.<br><br>Di bab-bab selanjutnya, contoh yang dikerjakan ditunjukkan dengan deskripsi singkat tentang masalah yang ditangani dalam contoh, ditambah pengingat untuk melihatnya di eTeks Anda atau mengunduhnya dari situs web pendamping buku di www.wiley.com/go/bjeo7. Anda akan menemukan kode apa pun yang terkait dengan Contoh yang Dikerjakan yang disertakan dengan kode pendamping buku untuk bab ini. Saat Anda melihat deskripsi Contoh yang Dikerjakan, buka contoh dan lihat dan jalankan kode untuk mempelajari bagaimana masalah tersebut diselesaikan</p>


### __CONTOH YANG BERHASIL 1.1__

### _Menulis Sebuah Algoritma untuk Memasang Ubin Lantai_

<p align = "justify">Rumusan Masalah Tulis sebuah algoritma untuk memasang ubin lantai kamar mandi persegi panjang dengan ubin hitam putih berselang-seling berukuran 4×4 inci. Dimensi lantai, diukur dalam inci, dengan kelipatan 4.<br><b>Step 1</b> Tentukan input dan outputnya.</br>Inputnya merupakan dimensi lantai (panjang × lebar), diukur dengan inci. Outputnya merupakan lantai keramik.</br></br><b>Step 2</b> Pecah masalah ke dalam tugas-tugas kecil.<br><img src="G22.png" align="right" width=200><br>Subtugas natural yaitu membuat satu baris ubin. Jika kamu bisa selesaikan tugas itu, maka kamu dapat menyelesaikan masalah dengan membuat satu baris di samping yang lain, mulai dari dinding, hingga kamu mencapai dinding yang berlawanan.<br><br>Bagaimana cara membuat baris tersebut? Mulailah dengan ubin di satu dinding. Jika tersebut berwarna putih, letakkan yang hitam di sebelahnya. Jika berwarna hitam, taruh ubin putih di sebelahnya. Terus lakukan hal tersebut hingga kamu mencapai dinding yang berlawanan. Baris akan berisi lebar / 4 ubin.<br><br><b>Step 3</b> Jelaskan setiap tugas ke dalam pseudocode (kodesemu).<br>Dalam kodesemu, kamu ingin lebih tepat tentang di mana tepatnya ubin ditempatkan.
Tempatkan ubin hitam di sudut barat laut Sementara lantai belum terisi<br>Ulangi lebar / 4 – 1 kali<br>Tempatkan ubin di sebelah timur ubin yang ditempatkan sebelumnya. Jika ubin yang ditempatkan sebelumnya berwarna putih, pilih yang hitam; jika tidak, pilih yang putih.<br>Kembali pada ubin di awal baris yang baru saja kamu tempatkan. Jika ada
ruang di selatan, letakkan ubin dengan warna yang berlawanan di bawahnya.<br><br><b>Step 4</b> Uji kodesemu dengan mengerjakan suatu masalah.<br>Misalkan kamu ingin memasang ubin di area berukuran 20 × 12 inci. Langkah pertama adalah menempatkan ubin hitam di sudut barat laut.<br><img src="G24.png" align="center" width=200><br>Selanjutnya, tempatkan empat ubin secara bergantian hingga mencapai dinding timur. (lebar / 4 – 1 = 20 / 4 – 1 = 4).<br><img src="G24.png" align="center" width=200><br>Ada ruang di selatan. Kembali pada ubin di awal baris yang sudah selesai. Warnanya hitam. Tempatkan ubin putih di sebelah selatannya.<br><img src="G25.png" align="center" width=200><br>Lengkapi baris.<br><img src="G26.png" align="center" width=200><br>Masih ada ruang di selatan. Kembali pada ubin di awal baris yang sudah selesai. Warnanya putih. Tempatkan ubin hitam di selatannya.<br><img src="G27.png" align="center" width=200><br>Lengkapi baris.<br><img src="G28.png" align="center" width=200><br>Sekarang seluruh lantai terisi dan selesai.</p>
 
#
## __RINGKASAN BAB__

<p align ="justify">Mendefinisikan "program komputer" dan pemrograman<br>•	Komputer menjalankan instruksi yang sangat mendasar secara berurutan.<br>•	Program komputer adalah urutan instruksi dan keputusan.<br>•	Pemrograman adalah tindakan merancang dan mengimplementasikan program komputer.<br><br><img src="G1.png" align="left" width=100>Penjelasan komponen-komponen komputer<br>•	Unit pemrosesan pusat (CPU) melakukan kontrol program dan pemrosesan data.<br>•	Perangkat penyimpanan termasuk memori dan penyimpanan sekunder<br><br><img src="G6.png" align="left" width=200>Penjelasan proses penerjemahan bahasa tingkat tinggi ke kode mesin<br>•	Java awalnya dirancang untuk memprogram perangkat konsumen, tetapi pertama kali berhasil digunakan untuk menulis applet internet.<br>•	Java dirancang agar aman dan portabel, bermanfaat bagi pengguna internet dan pelajar.<br>•	Program java didistribusikan sebagai instruksi untuk mesin virtual, menjadikannya platform-independen.<br>•	Java memiliki perpustakaan yang sangat besar, fokuslah untuk mempelajari bagian- bagian perpustakaan yang Anda butuhkan untuk proyek pemrograman Anda.
<br><br>Menjadi akrab dengan lingkungan pemrograman java Anda<br>•	Luangkan waktu untuk membiasakan diri dengan lingkungan pemrograman yang akan Anda gunakan untuk tugas kelas Anda.<br>•	Editor adalah program untuk memasukkan dan memodifikasi teks, seperti program java.<img src="G29.png" align="right" width=200><br>•	Java peka huruf besar-kecil, Anda harus berhati-hati dalam membedakan antara huruf besar dan huruf kecil.<br>•	Kompiler java menerjemahkan kode sumber ke dalam file kelas yang berisi instruksi untuk mesin virtual java.<br>•	Mengembangkan strategi untuk menyimpan salinan cadangan pekerjaan Anda sebelum masalah terjadi.<img src="G12.png" align="left" width=120><br><br>Menggambarkan blok bangunan dari program sederhana<br>•	Kelas adalah blok bangunan dasar dari program java.<br>•	Setiap aplikasi java berisi kelas dengan metode utama, ketika bintang aplikasi, instruksi dalam metode utama dijalankan.<br>•	Setiap kelas berisi deklarasi metode, setiap metode berisi urutan instruksi.<br>•	Sebuah metode dipanggil dengan menentukan metode dan argumennya.<br>•	String adalah urutan karakter yang diapit tanda kutip.<br><img src="G15.png" align="left" width=150><br><br>Mengklasifikasikan kesalahan program sebagai kompilasi - kesalahan waktu dan waktu berjalan<br>•	Kesalahan waktu kompilasi adalah pelanggaran aturan bahasa pemrograman yang dideteksi oleh kompiler.<br>•	Kesalahan run waktu berjalan menyebabkan program mengambil tindakan yang tidak diinginkan oleh programmer.<img src="G17.png" align="right" width=150><br><br>Tulis kode semu untuk algoritma sederhana<br>•	Algoritma untuk memecahkan masalah adalah urutan langkah yang jelas dapat dieksekusi dan diakhiri.<br>•	Kode semu adalah deskripsi informal dari urutan langkah-langkah untuk memecahkan masalah.

#
## __ITEM PERPUSTAKAAN STANDAR YANG DIPERKENALKAN DALAM BAB INI__

java.io.PrintStream	java.lang.System print		out
println
 
Tinjau latihan	EXl-1


■	R1.1 Menjelaskan perbedaan antara menggunakan program komputer dan memprogram komputer.

■	R1.2 Bagian komputer mana yang dapat menyimpan kode program? Yang dapat menyimpan data pengguna

■	R1.3 Bagian mana dari komputer yang berfungsi untuk memberikan informasi kepada pengguna? Bagian mana yang menerima input pengguna?

■	■ R1.4 Pemanggang roti adalah perangkat fungsi tunggal, tetapi komputer dapat diprogram untuk melakukan tugas yang berbeda. Apakah ponsel Anda perangkat fungsi tunggal, atau komputer yang dapat diprogram? (Jawaban Anda akan tergantung pada model ponsel Anda.)

■	■ R1.5 Jelakan dua manfaat menggunakan Java daripada kode mesin.

■	■ R1.6 Di komputer Anda sendir atau di komputer lab, temukan lokasi yang tepat (nama folder atau direktori) dari
a.	Contoh file HelloPrinter. java, yang Anda tulis dengan editor.
b.	Program peluncur java.exe atau java.
c.	File library rt.jar yang berisi library/perpustakaan run-time.

■	■ R 1.7  Apa yang dicetak oleh program ini?
public class Test
{
public static void main(String[] args)
{
System.out.println("39 + 3");
System.out.println(39 + 3);
}
}

■■ R 1.8   Apa yang dicetak oleh program ini? Perhatikan baik-baik spasi.
public class Test
{
public static void main(String[] args)
{
System.out.print("Hello"); System.out.println("World");
}
}
■	■ R1.9  Apa kesalahan compile-time pada program ini?
public class Test
{
public static void main(String[] args)
{
System.out. println("Hello", "World!");
}
}

■	■ R1.10 Tulis tiga versi dari HelloPrinter.java Program yang memiliki kesahalan
compile• time yang berbeda. Tulis versi yang memiliki kesalahan run-time.

■	R1.11 Bagaimana Anda menemukan kesalahan sintaks? Bagaimana anda menemukan kesalahan logika?
 
EXl-2	Bab l Pengantar

■	■ ■ R1.12 Kafetaria menawarkan kartu diskon untuk Anda, selama periode tertentu, untuk makan gratis setiap kali Anda membeli sejumlah makanan tertentu dengan harga reguler. Detail pasti dari penawaran berubah dari waktu ke waktu. Jelaskan algoritme yang memungkinkan Anda menentukan apakah penawaran tertentu merupakan pembelian yang baik. Apa masukan lain yang Anda butuhkan?

■	■ R 1.13 Tulis algoritma untuk menyelesaikan pertanyaan berikut: Rekening bank dimulai dengan $10.000. Bunga dimajemukkan setiap bulan sebesar 6 persen per tahun (0,5 persen per bulan). Setiap bulan, $500 ditarik untuk memenuhi biaya kuliah. Setelah berapa tahun apakah akun tersebut habis?

■	■ ■ R1.14 Perhatikan pertanyaan pada Latihan•• Rl .13. Misalkan angka ($ 10.000, 6 persen, $ 500) dapat dipilih pengguna. Apakah ada nilai yang tidak akan dihentikan oleh algoritma yang Anda kembangkan? Jika demikian, ubah algoritmanya untuk memastikannya selalu berakhir.

■	■ ■ R1.15 Untuk memperkirakan biaya pengecatan rumah, seorang pelukis perlu mengetahui luas permukaan bagian luarnya. Kembangkan algoritma untuk menghitung nilai itu. Masukan Anda adalah lebar, panjang, dan tinggi rumah, jumlah jendela dan pintu, serta dimensinya. (Asumsikan jendela dan pintu memiliki ukuran yang seragam.)

■	■ R 1.16 Di How To 1.1, Anda membuat asumsi tentang harga bensin dan penggunaan tahunan untuk membandingkan mobil. Idealnya, Anda ingin tahu mobil mana yang lebih baik tanpa membuat asumsi ini. Mengapa program komputer tidak dapat menyelesaikan masalah itu?

■	■ R1.17 Misalkan Anda menempatkan adik laki-laki Anda yang bertanggung jawab untuk mendukung pekerjaan Anda. Tulis satu set instruksi rinci untuk melaksanakan tugasnya. Jelaskan seberapa sering dia harus melakukannya, dan file apa yang perlu dia salin dari folder mana ke lokasi mana. Jelaskan bagaimana dia harus memverifikasi bahwa pencadangan dilakukan dengan benar.

■	R 1.18	Tulis pseudocode untuk algoritme yang menjelaskan cara menyiapkan sarapan hari Minggu di rumah Anda.

■	■R1.19  Orang Babilonia kuno memiliki algoritme untuk menentukan akar kuadrat dari suatu bilangan a. Mulailah dengan tebakan awal a/2. Kemudian temukan rata-rata tebakan Anda g dan a/g. Itu tebakan Anda selanjutnya. Ulangi sampai dua tebakan berturut-turut cukup dekat. Tulis pseudocode untuk algoritma ini.

#
## __Latihan__

<p align = "justify">E1.1	Tulis sebuah program yang mencetak salam pilihan Anda, mungkin dalam bahasa selain bahasa Inggris.<br>E1.2	Tulis program yang mencetak jumlah sepuluh bilangan bulat positif pertama, 1 + 2 + … + 10<br>E1.3	Tulis program yang mencetak hasil kali sepuluh bilangan bulat positif pertama, 1 × 2 × … × 10. (Gunakan * untuk menunjukkan perkalian di Java.)<br>E1.4	Buatlah program yang mencetak saldo akun setelah tahun pertama, kedua, dan ketiga. Akun tersebut memiliki saldo awal $1.000 dan menghasilkan bunga 5 persen per tahun.<br>E1.5	Tulis program yang menampilkan nama Anda di dalam kotak di layar, seperti ini: Dave Lakukan yang terbaik untuk memperkirakan garis dengan karakter seperti | - +<br>E1.6	Tulis program yang mencetak nama Anda dalam huruf besar, seperti<br>E1.7	Tulislah program yang mencetak nama Anda dalam kode Morse, seperti ini:
 .... .- .-. .-. -.- - Gunakan panggilan terpisah ke System.out.print untuk setiap huruf.<br>E1.8	Tulis program yang mencetak wajah yang mirip dengan (tetapi berbeda dari) berikut ini:<br>E1.9	Tulis program yang mencetak tiruan lukisan Piet Mondrian. (Cari di Internet jika Anda tidak mengenal lukisannya.) Gunakan urutan karakter seperti @@@ atau ::: untuk menunjukkan warna yang berbeda, dan gunakan - dan | untuk membentuk garis.<br>E1.10	Buatlah program untuk mencetak sebuah rumah yang bentuknya persis seperti berikut ini:<br>E1.11	Buatlah program yang mencetak hewan yang mengucapkan salam, mirip dengan (tetapi berbeda dari) berikut ini<br>E1.12	Tulis program yang mencetak tiga item, seperti nama tiga sahabat atau film favorit Anda, pada tiga baris terpisah.<br>E1.13	Tulis program yang mencetak puisi pilihan Anda. Jika Anda tidak memiliki puisi favorit, cari di Internet untuk "Emily Dickinson" atau "e e cummings".<br>E1.14	Tulis program yang mencetak bendera Amerika Serikat, menggunakan karakter * dan =.
<br>E1.15	Ketik dan jalankan program berikut. Kemudian ubah untuk menampilkan pesan “Hello, your name!”. 
 import javax.swing.JOptionPane; 
public class DialogViewer 
{ 
    public static void main(String[] args) 
    {
        JOptionPane.showMessageDialog(null, "Hello, World!")
     }
}<br>E1.16	Ketik dan jalankan program berikut. Kemudian ubah untuk mencetak "Halo, nama!", Menampilkan nama yang diketik pengguna.
  import javax.swing.JOptionPane;
public class DialogViewer 
{
    public static void main(String[] args) 
   { 
String name = JOptionPane.showInputDialog("What is your name?");                         System.out.println(name);
    }
}<br>E1.17	Ubah program dari Latihan •• E1.16 sehingga dialog berlanjut dengan pesan “Nama saya Hal! Apa yang bisa saya kerjakan?" Buang input pengguna dan tampilkan pesan seperti
 Maafkan aku, Dave. Aku takut aku tidak bisa melakukan itu. 
Ganti Dave dengan nama yang diberikan oleh pengguna.<br>E1.18	Ketik dan jalankan program berikut. Kemudian ubah untuk menampilkan sapaan dan gambar yang berbeda.

import java.net.URL; 
import javax.swing.ImageIcon;
import javax.swing.JOptionPane;

public class Test
{ 
    public static void main(String[] args) throws Exception 
   { 
      URL imageLocation =newURL (  
       	"http://horstmann.com/java4everyone/duke.gif");
     JOptionPane.showMessageDialog(null, "Hello", "Title",
JOptionPane.PLAIN_MESSAGE, new ImageIcon(imageLocation));
   }
}<br>Bisnis E1.19	Tulis program yang mencetak daftar dua kolom ulang tahun teman Anda. Di kolom pertama, cetak nama-nama sahabatmu; di kedua, cetak ulang tahun mereka.<br>Bisnis E1.20	Di Amerika Serikat tidak ada pajak penjualan federal, jadi setiap negara bagian dapat mengenakan pajak penjualannya sendiri. Cari di Internet untuk pajak penjualan yang dikenakan di lima negara bagian AS, lalu tulis program yang mencetak tarif pajak untuk lima negara bagian pilihan Anda. <br><br>Bisnis E1.21	Berbicara lebih dari satu bahasa adalah keterampilan yang berharga di pasar tenaga kerja saat ini. Salah satu keterampilan dasar adalah belajar menyapa orang. Tulis sebuah program yang mencetak daftar dua kolom dengan frase sapaan yang ditunjukkan pada tabel. Di kolom pertama, cetak frasa dalam bahasa Inggris, di kolom kedua, cetak frasa dalam bahasa pilihan Anda. Jika Anda tidak berbicara bahasa selain bahasa Inggris, gunakan penerjemah online atau tanyakan pada teman.</p>

### __Proyek Pemrograman__
<p align = "justify">P1.1	Anda ingin memutuskan apakah Anda harus mengendarai mobil ke kantor atau naik kereta. Anda mengetahui jarak satu arah dari rumah Anda ke tempat kerja Anda, dan efisiensi bahan bakar mobil Anda (dalam mil per galon). Anda juga tahu harga satu arah dari	sebuah tiket kereta api. Anda mengasumsikan biaya bensin pada $4 per galon, dan perawatan mobil pada 5 sen per mil. Tulis algoritme untuk memutuskan perjalanan mana yang lebih murah.<br><br>P1.2	Anda ingin mengetahui bagian mana dari penggunaan mobil Anda untuk berangkat kerja, dan yang untuk penggunaan pribadi. Anda tahu jarak satu arah dari rumah Anda ke kerja. Untuk periode tertentu, Anda mencatat jarak tempuh awal dan akhir di odometer dan jumlah hari kerja. Tulis algoritma untuk menyelesaikan pertanyaan ini.<br><br>P1.3	Nilai dapat dihitung menurut rumus berikut: <br>π/4=1-  1/3 + 1/5 - 1/7+1/9-…Tulis algoritma untuk menghitung . Karena rumusnya adalah deret tak hingga dan algoritma harus berhenti setelah sejumlah langkah yang terbatas, Anda harus berhenti ketika Anda memiliki hasilnya ditentukan untuk enam penggalian signifikan<br><br>Bisnis P1.4	Bayangkan Anda dan sejumlah teman pergi ke restoran mewah, dan ketika Anda mintalah tagihan yang ingin Anda bagi jumlahnya dan tip (15 persen) di antara semuanya. Tulis pseudocode untuk menghitung jumlah uang yang harus dibayar setiap orang. Program Anda harus mencetak jumlah tagihan, tip, total biaya, dan jumlah yang harus dibayar setiap orang. Itu juga harus mencetak berapa banyak dari apa yang setiap orang membayar adalah untuk tagihan dan tip
<br><br>P1.5	Tulis algoritma untuk membuat pola ubin yang terdiri dari hitam dan ubin putih, dengan pinggiran ubin hitam di sekelilingnya dan dua atau tiga ubin hitam di tengah, berjarak sama dari ary terikat. Input ke algoritme Anda adalah jumlah total baris dan kolom dalam pola.<br><br>P1.6	Tulis algoritma yang memungkinkan robot untuk memotong rumput persegi panjang, asalkan ditempatkan di sudut seperti ini:                                                                          Robot (ditandai sebagai R) dapat:
	Maju satu unit.
	Belok kiri atau kanan.
	Rasakan warna tanah satu unit di depannya.<br><br>P1.7 	Pertimbangkan sebuah robot yang ditempatkan di sebuah ruangan. Robotnya bisa: 
	Maju satu unit.
	Belok kiri atau kanan.
	Rasakan apa yang ada di depannya: dinding, jendela, atau
juga tidak.<br>Tulis algoritma yang memungkinkan robot, ditempatkan di mana saja di dalam ruangan, untuk menghitung jumlah jendela. Untuk contoh, di ruangan di sebelah kanan, robot (ditandai sebagai R) harus menemukan bahwa ia memiliki dua jendela.<br><br>P1.8	 Perhatikan sebuah robot yang ditempatkan di dalam labirin. Aturan tangan kanan memberi tahu Anda caranya untuk melarikan diri dari labirin: Selalu memiliki tangan kanan di samping dinding, dan akhirnya Anda akan menemukan jalan keluar. Robotnya bisa:<br>Maju satu unit.<br>Belok kiri atau kanan.<br>Rasakan apa yang ada di depannya: tembok, jalan keluar, atau bukan keduanya. <br><br>Tulis algoritme yang memungkinkan robot keluar dari labirin. Anda mungkin berasumsi bahwa ada jalan keluar yang dapat dicapai oleh aturan tangan kanan. Tantangan Anda adalah menghadapi situasi di yang jalannya berbelok. Robot tidak bisa melihat belokan. Itu hanya bisa melihat apa yang ada di depannya.<br><br>Bisnis P1.9 	Misalkan Anda menerima promosi loyalitas yang memungkinkan Anda membeli satu item, dihargai hingga $100, dari katalog online. Anda ingin membuat penawaran terbaik. Kamu punya daftar semua barang untuk dijual, beberapa di antaranya kurang dari $100, beberapa lagi. Menulis sebuah algoritma untuk menghasilkan item yang paling dekat dengan $100. Jika ada lebih dari satu seperti itu item, daftar semuanya. Ingatlah bahwa komputer akan memeriksa satu item dalam satu waktu—itu tidak bisa hanya melihat daftar dan menemukan yang terbaik.<br><br>Sains P1.10	 Sebuah produsen televisi mengiklankan bahwa satu set televisi memiliki ukuran tertentu, diukur secara diagonal. Anda bertanya-tanya bagaimana set akan masuk ke ruang tamu Anda. Tulislah algoritma yang menghasilkan garis horizontal dan ukuran vertikal televisi. Masukan Anda adalah ukuran diagonal dan rasio aspek (rasio lebar tinggi, biasanya 16 : 9 untuk pesawat televisi). <br><br>Sains P1.11	 Kamera saat ini dapat memperbaiki masalah “mata merah” disebabkan saat foto flash membuat mata terlihat merah.Tulis pseudocode untuk algoritma yang dapat mendeteksi mata merah. Masukan Anda adalah sebuah pola warna, seperti yang di sebelah kanan.<br>Anda diberi jumlah baris dan kolom. Untuk nomor baris atau kolom apa pun, Anda dapat menanyakan warna, yang akan menjadi merah, hitam, atau yang lainnya. Jika Anda menemukan itu pusat piksel hitam bertepatan dengan pusat piksel merah, Anda memiliki menemukan mata merah, dan output Anda harus "ya". Jika tidak, output Anda adalah "tidak".</p>