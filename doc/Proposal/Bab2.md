<h3 align="center">BAB II</h3>


<h3 align="center">LANDASAN TEORI</h3>


**2.1 Kajian Pustaka**

**2.1.1	Pengertian Sistem**

Sistem adalah jaringan kerja dari prosedur-prosedur yang saling berhubungan, berkumpul bersama-sama untuk melakukan suatu kegiatan atau menyelesaikan suatu sasaran tertentu.[1]

**2.1.2	WhatsApp**

Salah satu aplikasi messenger yang paling banyak pengguna untuk saat ini. Whatsapp dapat berjalan lintas platform, baik Android, IOS, Nokia Symbian S60 dan Windows Phone. Untuk dapat bekerja dengan Whatsapp. Diperlukan sebuah API yang dapat bekerja pada board RPi2.[2]

**2.1.3	Raspberry Pi2**

Raspberry Pi adalah komputer kecil yang memiliki ukuran sebesar kartu kredit namun memiliki fungsi yang lengkap sebagai komputer dikarenakan Raspberry Pi memiliki prosesor, RAM dan port hardware. Sistem operasi utama untuk Pi adalah Raspbian OS dan didasarkan dari Debian.
Raspberry Pi memiliki dua model yaitu model A dan model B. Perbedaan model A dan B terletak pada memory yang digunakan, Model A menggunakan memory 256 MB dan model B 512 MB. Selain itu model B juga sudah dilengkapi dengan ethernet port  yang tidak terdapat di model A. Desain Raspberry Pi didasarkan seputar SoC (System-on-a-chip) Broadcom BCM2835, yang telah menanamkan prosesor ARM1176JZF-S dengan 700 MHz, VideoCore IV GPU, dan 256 Megabyte RAM. Penyimpanan data menggunakan kartu micro sd dimana didalamnya sudah termasuk sistem operasi untuk booting dan penyimpanan data – data lainnya. Untuk daya yang digunakan menggunakan tegangan 5 volt via micro usb. Dalam perkembangannya Raspberry Pi dimulai dari Raspberry Pi tipe A sampai dengan yang terbaru adalah Raspberry Pi 3, namun saat ini lebih banyak digunakan Raspberry Pi 2 karena kemampuan yang lebih baik dan harga yang tidak terlalu mahal. Hal ini dapat lebih jelas ditunjukkan oleh gambar 1 mengenai komparasi spesifikasi Raspberry tipe B sampai dengan yang terbaru Raspberry Pi 3.
Raspberry Pi dapat diintegrasikan dengan sensor ataupun perangkat elektronik lainnya melalui General Purpose Input/Output (GPIO). Salah satu contoh sensor yang bisa diintegrasikan adalah sensor HC-SR04.
Sensor HC-SR04 adalah sensor pengukur jarak berbasis gelombang ultrasonik. Salah satu aplikasinya pada [3] dengan prinsip kerjanya memancarkan gelombang ultrasonik sampai gelombang tersebut terpantul kembali dan diterima oleh receiver ultrasonik. 
Contoh perangkat keluaran yaitu buzzer. Buzzer adalah sebuah komponen elektronika yang berfungsi untuk mengubah getaran listrik menjadi getaran suara. Perangkat keluaran lainnya adalah kamera. Salah satu percobaan yang pernah dilakukan pada [2] mengenai kamera pada raspberry menunjukkan bahwa raspberry juga dapat diandalkan dalam hal pengolahan citra. Dengan meningkatnya perkembangan teknologi maka saat ini Raspberry Pi mampu menggunakan kamera tipe webcam. Raspberry Pi dapat mengambil gambar atau merekam sebuah video yang akan tersimpan di media penyimpanan lokal.[3]

**2.1.4	Python**

Python merupakan bahasa pemrograman yang berorientasi obyek dinamis, dapat digunakan untuk bermacam-macam pengembangan perangkat lunak http://www.python.org/about/apps. Python menyediakan dukungan yang kuat untuk integrasi dengan bahasa pemrograman lain dan alat-alat bantu lainnya. Python hadir dengan pustakapustaka standar yang dapat diperluas serta dapat dipelajari hanya dalam beberapa hari. Sudah banyak programmer Python yang menyatakan bahwa mereka mendapatkan produktivitas yang lebih tinggi. Mereka juga merasakan bahwa Python meningkatkan kualitas pengembangan karena kode sumber yang mereka tulis dapat terus dipelihara. Python dapat berjalan di banyak platform / sistem operasi seperti Windows, Linux/Unix, Mac OS X, OS/2, Amiga, Palm Handhelds dan telepon genggam Nokia. Saat ini Python juga telah diporting ke dalam mesin virtual Java dan .NET. Python didistribusikan dibawah lisensi OpenSource yang disetujui OSI (OpenSource Initiatives), sehingga Python bebas digunakan, gratis digunakan, bahkan untuk produk-produk komersil. Yayasan Perangkat Lunak Python – Python Software Foundation (PSF) memegang dan melindungi hak atas kekayaan intelektual dibawah Python, tertuang dalam konferensi PyCon, serta mendanai proyek-proyek pada komunitas Python. Saat tulisan ini dibuat, PyCon yang akan datang, diselenggarakan di Cyberbase de la Vileete, Paris, Perancis pada tanggal 30/31 Mei 2009.[4]

**2.1.5	UML**

Unified Modelling Language (UML) adalah suatu alat untuk memvisualisasikan dan mendokumentasikan hasil analisa dan desain yang berisi sintak dalam memodelkan sistem secara visual (Braun, et. al. 2001). Juga merupakan satu kumpulan konvensi pemodelan yang digunakan untuk menentukan atau menggambarkan sebuah sistem software yang terkait dengan objek (Whitten, et. al. 2004). Sejarah UML sendiri terbagi dalam dua fase; sebelum dan sesudah munculnya UML. Dalam fase sebelum, UML sebenarnya sudah mulai diperkenalkan sejak tahun 1990an namun notasi yang dikembangkan oleh para ahli analisis dan desain berbeda-beda, sehingga dapat dikatakan belum memiliki standarisasi. Fase kedua; dilandasi dengan pemikiran untuk mempersatukan metode tersebut dan dimotori oleh Object Management Group (OMG) maka pengembangan UML dimulai pada akhir tahun 1994 ketika Grady Booch dengan metode OOD (Object-Oriented Design), Jim Rumbaugh dengan metode OMT (Object Modelling Technique) mereka ini bekerja pada Rasional Software Corporation dan Ivar Jacobson dengan metode OOSE (Object-Oriented Software Engineering) yang bekerja pada perusahaan Objectory Rasional.  Sebagai pencetus metode-metode tersebut mereka bertiga berinisiatif untuk menciptakan bahasa pemodelan terpadu sehingga pada tahun 1996 mereka berhasil merilis UML versi 0.9 dan 0.91 melalui Request for Proposal (RFP) yang dikeluarkan oleh OMG (Braun, et.al. 2001). Kemudian pada Januari 1997 IBM, ObjecTime, Platinum Technology, Ptech, Taskon, Reich Technologies dan Softeam juga menanggapi Request for Proposal (RFP) yang dikeluarkan oleh OMG tersebut dan menyatakan kesediaan untuk bergabung. Perusahaan-perusahaan ini menyumbangkan ide-ide mereka, dan bersama para mitra menghasilkan UML revisi 1.1. Fokus dari UML versi rilis 1.1 ini adalah untuk meningkatkan kejelasan UML Semantik versi rilis 1.0. Hingga saat ini UML versi terbaru adalah versi 2.0 (http://www.uml.org/).  Saat ini sebagian besar para perancang sistem informasi dalam menggambarkan informasi dengan memanfaatkan UML diagram dengan tujuan utama untuk membantu tim proyek berkomunikasi, mengeksplorasi potensi desain, dan memvalidasi desain arsitektur perangkat lunak atau pembuat program.[5]

**2.1.6	Basis Data (Database)**

		Basis data merupakan kumpulan data, yang dapat digambarkan sebagai aktiftas dari satu atau lebih organisasi yang saling berelasi. Kemampuannya untuk mengatur atau mengelolah sejumlah data, dan kecepatan untuk mencari informasi yang sangat besar.[6]

**2.1.7	MySql**

		MySQL merupakan DBMS yang pertama kali mulai dikembangkan tahun 1994 oleh sebuah perusahaan software bernama TcX Data Konsultan AB yang di kemudian hari berganti label menjadi MySQL-AB. Saat ini MySQL digunakan oleh sebagian besar Web Server yang ada di jagat internet. Di samping karena dianggap simple, MySQL memiliki fitur-fitur yang sangat baik dan dapat di-porting pada berbagai Sistem Operasi sekelas server, seperti Windows, Linux, Solaris, Mac OS, BSD, Unix, IBM-AIX, sehingga sangat cocok untuk digunakan dalam implmentasi aplikasi basis data khususnya yang berbasis Web.[6]
