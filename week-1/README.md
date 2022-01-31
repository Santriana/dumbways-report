# Week 1
## DevOps Concept
DevOps merupakan kombinasi dari serangkaian praktik untuk terus meningkatkan kolaborasi antara pengembang, operasi TI, dan pemangku kepentingan bisnis, menggunakan alat otomatisasi untuk mempercepat penerapan perangkat lunak, meningkatkan penyampaian layanan, dan memastikan meminimalisir kesalahan kode melalui proses yang berulang.
### DevOps Principles
-	Automation
Mengotomatiskan tugas harian yang berulang dapat menghemat waktu yang berharga. Siklus hidup DevOps mencakup otomatisasi dan alat penerapan aplikasi untuk bermigrasi dari satu teknologi atau proses ke teknologi atau proses lainnya secepat, akurat, dan seaman mungkin.
-	Collaboration
DevOps berusaha untuk mencegah pengembang, penguji, dan spesialis operasi TI bersaing secara internal atau menahan umpan balik satu sama lain. Alih-alih, ini memberdayakan pengembang dan tim operasi TI untuk saling berkonsultasi guna meminimalkan penundaan penerapan perangkat lunak.
-	Iteration
DevOps juga berusaha untuk secara konsisten memecahkan masalah perangkat lunak dengan mengkodekan perubahan reguler dan bertahap, mengujinya, dan kemudian mendorongnya dalam rilis atau tambalan. Prinsip DevOps ini membuat penerapan fitur perangkat lunak baru atau menambal aplikasi yang ada menjadi kurang intensif, sehingga meningkatkan kualitas dan keamanan perangkat lunak yang dirilis.
-	Countinuous Improvement
Rilis perangkat lunak tidak pernah menjadi akhir dari proyek apa pun. Peningkatan berkelanjutan terjadi melalui pembaruan yang berkelanjutan, pindah ke infrastruktur yang lebih efisien, atau menargetkan Indikator Kinerja Utama (KPI) baru, antara lain.

## DevOps Workflow
 
1.	Planning, dalam bagian ini pengembang merancang konsep aplikasi atau produk yang akan dibuat dan mempersiapkan kebutuhan – kebutuhan termasuk fitur, peralatan, dan anggaran dalam merancang aplikasi atau produk tersebut.
2.	Coding, dalam bagian ini pengembang akan menyusun code – code yang dibutuhkan untuk mengembangkan aplikasi / produk. Tim pengembang pada dasarnya menggunakan beberapa bahasa pemrograman (Python, Java, PHP, dll).
3.	Build, dalam bagian developer akan memasukan kode tersebut ke dalam shared code repository. Developer akan mengirimkan pull request, setelah developer yang lain akan mereview perubahan yang telah dilakukan. Jika kode tidak memiliki masalah, maka developer tersebut akan menyetujui pull request yang telah dikirim sebelumnya.
4.	Test, dalam bagian ini pengembang melakukan pengujian pada code – code yang telah disetujui sebelumnya. Apabila terdapat masalah, masalah tersebut akan dikirimkan kembali untuk direvisi.
5.	Release, dalam bagian ini code yang telah dirancang dapat dikatakan lulus uji sehingga code tersebut sudah matang dan siap digunakan.
6.	Deploy, pada bagian ini tim pengembang membentuk suatu lingkungan yang telah dikonfigurasi sehingga tim pengembang dapat melihat perkembangan yang terjadi pada environment test / environment development / environment production.
7.	Operate, dalam bagian ini aplikasi/produk yang telah dibentuk sebelumnya dioperasikan.
8.	Monitor, pada bagian ini tim IT operations akan memantau infrastruktur, sistem, dan aplikasi untuk memastikan bahwa aplikasi/produk yang dikembangkan dapat berjalan dengan optimal. Selain itu, mereka juga mengumpulkan data – data penting dari log, analitik, sistem monitoring, dan menerima user feedback untuk mengetahui kinerja dari aplikasi/produk yang dijalankan.

## CI/CD Concept
CI/CD merupakan serangkaian prinsip operasi, dan kumpulan praktik yang memungkinkan tim pengembangan aplikasi mengirimkan perubahan kode lebih sering dan andal. Penggunaan CI/CD memiliki banyak manfaat untuk perusahaan diantaranya
1.	Waktu yang dibutuhkan untuk dipasarkan lebih cepat hal ini dikarenakan tujuan utama dari pipa CI/CD adalah untuk memberikan perangkat lunak yang berfungsi kepada pengguna dengan cepat dan sering.
2.	Meminimalisir resiko hal ini dikarenakan waktu yang dibutuhkan untuk dipasarkan lebih singkat makka memberikan kesempatan bagi manajer produk dan profesional pemasaran untuk terlibat lebih dekat dengan proses pengembangan.
3.	Waktu peninjauan lebih singkat artubya Dengan integrasi berkelanjutan, pengembang didorong untuk melakukan perubahan kode mereka lebih sering – setidaknya sekali sehari sebagai aturan praktis. Berbagi kode dengan anggota tim lainnya secara teratur tidak hanya memastikan setiap orang membangun di atas fondasi yang sama, tetapi juga menghasilkan tinjauan kode yang lebih cepat dan mempermudah integrasi perubahan.
4.	Kualitas kode yang lebih baik hal ini dikarenakan bagian utama dari setiap pipeline CI/CD adalah serangkaian pengujian otomatis yang dijalankan pada setiap tahap build. 
- Continuous Integration atau CI merupakan serangkaian praktik yang mendorong tim pengembangan untuk menerapkan perubahan kecil dan sering memeriksa kode ke repositori kontrol versi. Karena sebagian besar aplikasi modern memerlukan pengembangan kode dalam platform dan alat yang berbeda, tim memerlukan mekanisme untuk mengintegrasikan dan memvalidasi perubahannya.
-	Continuous Delivery atau CD merupakan kelanjutan dari CI yang berperan untuk mengotomatiskan pengiriman aplikasi ke lingkungan infrastruktur yang dipilih. Sebagian besar tim bekerja dengan beberapa lingkungan selain produksi, seperti lingkungan pengembangan dan pengujian, dan CD memastikan ada cara otomatis untuk mendorong perubahan kode pada mereka.

## Tools untuk menerapkan DevOps
### Source Code Management
Pengembang dapat memeriksa dan mengubah kode tanpa harus saling menulis menggunakan repositori sumber. Ini adalah bagian penting dari Continuous Integration, atau CI. Tools yang memiliki fungsi sebagai SCM diantaranya :
-	GitLab yang merupakan repositori Git berbasis web yang menyediakan repositori terbuka dan pribadi gratis, kemampuan mengikuti masalah, dan wiki. Ini adalah platform DevOps lengkap yang memungkinkan para profesional untuk melakukan semua tugas dalam sebuah proyek—dari perencanaan proyek dan manajemen kode sumber hingga pemantauan dan keamanan.
-	Bitbucket menyediakan tempat sentral untuk mengelola repositori git, berkolaborasi pada kode sumber dan memandu melalui alur pengembangan. Bitbucket menyediakan fitur luar biasa yang meliputi: Kontrol akses untuk membatasi akses ke kode sumber.
### Build Server
Build server merupakan serangkaian alat otomatisasi yang menyusun kode yang terdapat pada Source Code Repository menjadi dasar kode yang dapat digunakan oleh pengembang. Tools yang memiliki fungsi sebagai Build Server diantaranya :
-	Jenkins yang dapat mengotomatiskan aspek proses pembuatan, pengujian, dan penerapan dalam proyek perangkat lunak, memungkinkan integrasi dan pengiriman berkelanjutan. Ini memudahkan pengembang untuk bekerja meningkatkan produk dengan memasukkan modifikasi ke dalam proyek.
### Configuration Management
Configuration Management memiliki fungsi untuk menyiapkan konfigurasi server atau lingkungannya. Tools yang memiliki fungsi sebagai manajemen konfigurasi diantaranya :
-	CHEF solusi manajemen konfigurasi yang mengontrol infrastruktur menggunakan kode daripada proses manual, memungkinkannya untuk segera diotomatisasi, diuji, dan disebarkan.
### Virtual Infrastructure
Virtual Infrastructure mencakup layanan seperti Amazon Web Services dan Microsoft Azure. Cloud yang menjual infrastruktur atau Platform sebagai Layanan menyediakan infrastruktur virtual (PaaS). Infrastruktur ini menawarkan API yang memungkinkan kita  menggunakan alat manajemen konfigurasi untuk menghasilkan mesin baru secara terprogram.
### Test Automation
Pada DevOps testing ditekankan untuk melakukan pengujian secara otomatis di seluruh proses build untuk menjamin bahwa build yang dapat diterapkan telah selesai.

## Operating Systems Concept
Operating Systems (OS) adalah seperangkat perangkat lunak yang mengelola sumber daya perangkat keras komputer dan menyediakan fungsi umum untuk program. Dalam sistem komputer, sistem operasi adalah komponen penting dari perangkat lunak sistem. Sistem operasi merupakan program perangkat lunak yang menghubungkan pengguna komputer dengan perangkat kerasnya. Sistem operasi adalah bagian dari perangkat lunak yang mengelola file, mengelola memori, mengelola proses, menangani input dan output, dan mengontrol perangkat periferal seperti drive disk dan printer. Contoh dari sistem operasi diantaranya yaitu Ubuntu, Windows, MacOS.

## Virtualization and Container
### Virtualization
Virtualisasi dapat meningkatkan kelincahan, fleksibilitas, dan skalabilitas IT sekaligus menurunkan biaya. Manfaat virtualisasi mencakup peningkatan mobilitas beban kerja, peningkatan kinerja dan ketersediaan sumber daya, dan operasi otomatis, yang semuanya membuat IT lebih mudah dikelola dan lebih murah untuk dibeli dan dioperasikan. Tools yang umumnya digunakan pada virtualization diantaranya VMWare, VirtualBox, Microsoft Hyper-V, Qemu, PROXMOX.

### Container
Container adalah jenis virtualisasi untuk sistem operasi. Dari layanan mikro kecil atau proses perangkat lunak hingga aplikasi besar, satu container dapat mengoperasikan semuanya. Semua executable yang diperlukan, kode biner, perpustakaan, dan file konfigurasi terkandung dalam sebuah container. Container, berbeda dengan virtualisasi server atau mesin, tidak berisi gambar sistem operasi. Hasilnya, mereka lebih ringan dan portabel, dengan lebih sedikit overhead. Beberapa container dapat digunakan sebagai satu atau beberapa cluster container dalam penerapan aplikasi yang lebih besar. Tools yang umumnya digunakan sebagai Container diantaranya Docker, Kubernetes, podman, dan lain lain.

## Cloud Computing Concept
### Private Cloud
Private Cloud adalah konsep komputasi awan di mana infrastruktur didedikasikan untuk perusahaan pengguna tunggal. Private Cloud Solutions memberi bisnis lebih banyak kontrol dan keamanan atas server cloud pribadi mereka, meskipun mereka memang membutuhkan tingkat pengalaman IT yang lebih tinggi daripada menggunakan cloud publik.
### Public Cloud
Public Cloud adalah arsitektur IT di mana pemasok pihak ketiga mengelola layanan dan infrastruktur komputasi sesuai permintaan yang dibagikan di berbagai perusahaan melalui Internet publik. Public cloud membuat sumber daya komputasi tersedia untuk dibeli oleh siapa saja. Public cloud sering dibagikan oleh banyak pengguna.

## Basic Network
Jaringan komputer merupakan suatu sistem yang menghubungkan dua atau lebih komputer yang saling bersinergi. Hubungan ini dapat terhubung menggunakan kabel atau tanpa kabel (wireless).
### Network Type
-	Personal Area Network (PAN)
PAN terdiri dari modem nirkabel, satu atau lebih komputer, telepon, printer, tablet, dan perangkat lain yang berputar di sekitar satu orang dalam satu gedung. Jaringan ini biasanya ditemukan di kantor atau rumah kecil, dan dikendalikan oleh satu orang atau organisasi menggunakan satu perangkat.
-	Local Area Network (LAN)
LAN memungkinkan kelompok komputer dan perangkat bertegangan rendah untuk berbagi informasi dan sumber daya melalui jarak kecil (di dalam gedung atau antara dua atau tiga gedung yang berdekatan satu sama lain). LAN sering dikelola dan dipelihara oleh bisnis.
-	Metropolitan Area Network (MAN)
Jaringan ini lebih besar dari LAN tetapi tidak sebesar WAN. MAN mencakup area geografis yang luas (biasanya kota kecil atau kota besar, tetapi terkadang kampus). Satu orang atau perusahaan bertanggung jawab atas kepemilikan dan pemeliharaan (dewan lokal, perusahaan besar, dll).
-	Wide Area Network (WAN)
WAN menghubungkan komputer dengan jarak fisik yang lebih jauh. Hal ini memungkinkan komputer dan perangkat bertegangan rendah untuk berkomunikasi satu sama lain melalui jaringan yang luas, bahkan jika jaraknya ribuan mil.
Internet adalah contoh paling dasar dari WAN karena menghubungkan semua komputer di planet ini. Karena jangkauannya yang luas, WAN biasanya dimiliki dan dikelola oleh sekelompok administrator atau masyarakat umum.
### Types of  Computer Network
-	Client-Server Network
Tipe jaringan ini menyimpan data, mengelola/menyediakan sumber daya, dan mengontrol akses pengguna menggunakan komputer (server) khusus. Server berfungsi sebagai hub untuk jaringan, menghubungkan semua komputer lain. Client adalah komputer yang terhubung ke server.
-	Peer to Peer Network
Peer to peer network adalah infrastruktur IT yang memungkinkan dua atau lebih sistem komputer untuk berkomunikasi dan berbagi sumber daya tanpa memerlukan server atau perangkat lunak server yang terpisah. Jaringan peer to peer dapat diatur di tempat kerja dengan menghubungkan komputer secara fisik atau dengan membangun jaringan virtual. Anda juga dapat mengonfigurasi PC untuk bertindak sebagai klien dan server jaringan.

## Network Topology
-	Topology Mesh
Topologi mesh mengacu pada metode jaringan di mana semua mesin dihubungkan bersama. Koneksi antar perangkat dalam Topologi Mesh dibuat secara acak. Komputer, sakelar, hub, dan perangkat lain dapat digunakan sebagai simpul yang terhubung. Bahkan jika salah satu link gagal dalam topologi ini, node lain masih dapat menyebar. Topologi ini sangat mahal karena tidak memiliki hierarki, saling ketergantungan, dan pola yang konsisten antara node. Koneksi topologi mesh tidak mudah dibangun.
-	Topology Bus
Topologi bus, juga dikenal sebagai topologi garis, adalah topologi jaringan di mana semua perangkat jaringan dihubungkan oleh satu kabel jaringan RJ-45 atau kabel koaksial. Bus, backbone, atau trunk mengacu pada kabel tunggal yang mentransmisikan semua data antar perangkat. Terdapat dua tipe topologi bus yaitu linear bus topology dimana semua perangkat terhubung ke satu kabel dengan dua titik akhir. Sedangkan distributed bus topology dimana semua perangkat terhubung ke satu kabel yang bercabang menjadi beberapa bagian, menghasilkan lebih dari dua titik akhir.
-	Topology Ring
Topologi ring adalah pengaturan jaringan yang membuat saluran data melingkar dengan menghubungkan perangkat dalam lingkaran. Seperti titik dalam lingkaran, setiap perangkat jaringan terhubung ke dua perangkat lainnya. Jaringan cincin terdiri dari perangkat yang terhubung dalam topologi cincin. Paket data berpindah dari satu perangkat ke perangkat berikutnya dalam jaringan dering hingga mencapai tujuannya. Jaringan cincin searah adalah topologi cincin di mana paket hanya dapat bergerak dalam satu arah. Lainnya, yang dikenal sebagai dua arah, memungkinkan data mengalir di kedua arah. Kelemahan utama dari topologi ring adalah jika salah satu koneksi ring gagal, seluruh jaringan akan terganggu.
-	Topology Star
Setiap node pada topologi star terhubung ke perangkat jaringan pusat, seperti hub, switch, atau komputer, dalam topologi ini. Perangkat jaringan inti berfungsi sebagai server, sedangkan klien adalah perangkat periferal. Tergantung pada jenis kartu jaringan yang ditempatkan di setiap komputer, kabel jaringan koaksial atau RJ-45 digunakan dalam susunan topologi bintang. Karena dibentuk seperti bintang, grafik menunjukkan bagaimana susunan jaringan ini mendapatkan namanya.
-	Topology Tree
Topologi star bus adalah nama lain dari topologi tree. Ini menggabungkan elemen dari kedua bus dan topologi star. Contoh diagram jaringan dari topologi pohon ditunjukkan di atas ini, di mana node inti dari dua jaringan bintang bergabung. Hanya ada satu link antara dua node yang terhubung dalam struktur pohon. Topologi pohon membuat hierarki induk dan anak alami karena setiap node hanya dapat memiliki satu tautan umum.

## IP Address
Alamat protokol internet (IP address) adalah pengenal numerik yang terhubung dengan komputer atau jaringan komputer tertentu. Ketika komputer terhubung ke internet, alamat IP memungkinkan mereka untuk mengirim dan menerima data.
### IP Public
Penyedia layanan internet Anda memberikan alamat IP publik ke router jaringan Anda sehingga dapat diakses langsung melalui internet (ISP). Saat Anda terhubung ke internet menggunakan IP publik router Anda, perangkat pribadi Anda memiliki alamat IP pribadi yang tetap tersembunyi.
Menghubungkan ke internet menggunakan alamat IP publik mirip dengan mengirim email ke P.O. kotak daripada memberikan alamat rumah Anda. Ini sedikit lebih aman, tetapi juga lebih terlihat.
### IP Private
Alamat yang dialokasikan router jaringan Anda ke perangkat Anda dikenal sebagai alamat IP pribadi. Setiap perangkat di jaringan internal yang sama diberikan alamat IP pribadi yang unik (juga dikenal sebagai alamat jaringan pribadi) yang memungkinkan mereka untuk berkomunikasi satu sama lain.
Alamat IP pribadi memungkinkan perangkat di jaringan yang sama untuk berkomunikasi tanpa perlu terhubung ke internet. IP pribadi membantu memperkuat keamanan dalam jaringan tertentu, seperti rumah atau kantor Anda, dengan mempersulit host atau pengguna eksternal untuk membuat sambungan.
### Static IP
Alamat IP yang tidak berubah dikenal sebagai alamat IP statis. Saat perangkat Anda diberi alamat IP statis, biasanya alamat tersebut tetap seperti itu hingga dihentikan atau arsitektur jaringan Anda berubah. Server dan peralatan utama lainnya biasanya menggunakan alamat IP statis.
Penyedia Layanan Internet (ISP) menetapkan alamat IP statis (ISP). Bergantung pada persyaratan perjanjian layanan Anda, ISP Anda mungkin atau mungkin tidak memberi Anda alamat IP statis. Opsi Anda akan dibahas nanti, tetapi untuk saat ini, harap alamat IP statis akan meningkatkan biaya kontrak ISP Anda.
### Dynamic IP
Alamat IP yang ditetapkan untuk host dinamis dapat berubah sewaktu-waktu. Server Dynamic Host Configuration Protocol (DHCP) menetapkan alamat dinamis sesuai kebutuhan.
Karena IPv4 tidak memberikan alamat IP statis yang cukup, kami menggunakan alamat dinamis. Sebuah hotel, misalnya, mungkin memiliki alamat IP statis, tetapi setiap perangkat di kamarnya mungkin memiliki alamat IP dinamis.

## OSI Concept
Model Interkoneksi Sistem Terbuka (Model OSI) adalah kerangka teoritis untuk menggambarkan fungsi sistem jaringan. Untuk memfasilitasi interoperabilitas antara beragam perangkat dan aplikasi, model OSI menggambarkan fungsi komputasi ke dalam seperangkat aturan dan standar universal. Pada model OSI terdapat tujuh buah layer yang menggambarkan fungsi sistem jaringan.
 
### Physical 
Lapisan terendah Model OSI berkaitan dengan melewatkan bit data mentah yang tidak terstruktur secara elektrik atau optik melalui jaringan dari lapisan fisik perangkat pengirim ke lapisan fisik perangkat penerima.
### Data Link
Pada lapisan data link, node yang terhubung langsung digunakan untuk melakukan transfer data node-to-node dimana data dikemas ke dalam frame. Lapisan data link juga mengoreksi kesalahan yang mungkin terjadi pada lapisan fisik.
Lapisan data link dibagi menjadi dua sub-lapisan. Yang pertama, kontrol akses media (MAC), mengontrol dan menggandakan transmisi perangkat di seluruh jaringan. Yang kedua, kontrol tautan logis (LLC), mengontrol lalu lintas dan kesalahan pada media fisik sambil juga mengidentifikasi protokol jalur.
### Network
Menerima frame dari lapisan data link dan mengirimkannya ke tujuan yang diinginkan berdasarkan alamat yang terkandung dalam frame adalah tanggung jawab lapisan jaringan. Alamat logika, seperti alamat IP, digunakan oleh lapisan jaringan untuk menemukan tujuan (protokol internet).
### Transport
Lapisan transport bertanggung jawab atas pengiriman paket data dan pengecekan kesalahan. Ini mengontrol ukuran, pengurutan, dan, pada akhirnya, transit data antara sistem dan host. TCP, atau Transmission Control Protocol, adalah salah satu contoh lapisan transport yang paling sering.
### Session
Lapisan sesi bertugas mengoordinasikan percakapan antar komputer. Pada lapisan 5, sesi atau koneksi antara mesin dibuat, dikelola, dan diakhiri. Otentikasi dan rekoneksi juga merupakan bagian dari layanan lapisan sesi.
### Presentation
Lapisan presentasi memformat atau mengonversi data untuk lapisan aplikasi berdasarkan sintaks atau semantik yang diterima aplikasi. Akibatnya, terkadang disebut sebagai lapisan sintaksis. Lapisan ini juga dapat menangani kebutuhan enkripsi dan dekripsi lapisan aplikasi.
### Application
Pada tingkat ini baik pengguna akhir dan lapisan aplikasi berinteraksi dengan aplikasi perangkat lunak secara langsung. Aplikasi pengguna akhir, seperti browser web, menerima layanan jaringan melalui lapisan ini.

## TCP/IP Concept
Bahasa yang digunakan komputer untuk mengakses internet adalah Transmission Control Protocol/Internet Protocol (TCP/IP). Ini adalah seperangkat protokol yang digunakan untuk membuat jaringan jaringan yang memungkinkan sebuah host untuk terhubung ke internet.
TCP/IP bertanggung jawab atas komunikasi data internet penuh dan transmisi data dari ujung ke ujung, serta layanan lain seperti pengalamatan, pemetaan, dan pengakuan. TCP/IP memiliki empat lapisan, yang agak berbeda dari model OSI.
 
### Network Access
Tanggung jawab utama dari lapisan jaringan adalah untuk menentukan bagaimana komputer terhubung ke jaringan. Sebuah host dapat berkomunikasi menggunakan berbagai topologi jaringan, termasuk Ethernet, Token Ring, dan Fiber Distributed Data Interface (FDDI).
### Internet
Interaksi dengan skema alamat jaringan dan komunikasi di berbagai segmen jaringan ditangani oleh lapisan Internet. Menggunakan router dan alamat IP, lapisan Internet akhirnya menentukan bagaimana sistem pada segmen jaringan yang berbeda menemukan dan berkomunikasi satu sama lain.
### Transport
Transport Layer berinteraksi dengan data aplikasi dan mempersiapkannya untuk transmisi jaringan. Melalui pengurutan paket data selama transmisi menggunakan TCP atau User Datagram Protocol (UDP) melalui IP, lapisan ini memungkinkan konektivitas yang dapat diandalkan, pemulihan kesalahan, dan kontrol aliran dari ujung ke ujung.
### Application
Lapisan Aplikasi bertanggung jawab untuk mengelola, menyiapkan, mengoordinasikan, dan mengakhiri dialog antar aplikasi di kedua ujung komunikasi. Ini juga memastikan bahwa data dari host pengirim diterima dalam format yang dapat dipahami oleh host penerima, sambil tetap mendukung aplikasi perangkat lunak dan proses pengguna akhir.


# Penyelesaian
- [Setup ubuntu server di VMWare & Install aplikasi nginx](setup-ubuntu-server-di-vmware-dan-install-aplikasi-nginx.md)
- [Setup ubuntu server di AWS & Deploy aplikasi frontend](setup-ubuntu-server-di-aws-dan-deploy-aplikasi-frontend.md)
