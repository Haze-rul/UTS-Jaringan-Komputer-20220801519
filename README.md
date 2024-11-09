# UTS-Jaringan-Komputer-20220801519

1.	Jaringan komputer adalah kumpulan dari dua atau lebih perangkat computer yang terhubung untuk berbagi data, sumber daya dan layanan. Perangkat-perangkat tersebut dapat berkomunikasi dan bertukar informasi melalui perangkat pengubung seperti router, switch atau hub.

2.	OSI Layer (Open Systems Interconnection) adalah model konseptual yang dikembangkan oleh ISO (International Organization for Standardization) untuk mempermudah pemahaman dan pengembangan jaringan komputer. Model OSI membagi proses komunikasi jaringan menjadi 7 lapisan (layer), di mana masing-masing lapisan memiliki fungsi spesifik. Tujuan utama dari model OSI adalah untuk memungkinkan interoperabilitas antara berbagai sistem dan standar dalam jaringan komputer.
1) Physical Layer (Lapisan Fisik)
2) Data Link Layer (Lapisan Data Link)
3) Network Layer (Lapisan Jaringan)
4) Transport Layer (Lapisan Transportasi)
5) Session Layer (Lapisan Sesi)
6) Presentation Layer (Lapisan Presentasi)
7) Application Layer (Lapisan Aplikasi)

3.	DHCP Server adalah server yang secara otomatis memberikan alamat IP dan informasi konfigurasi jaringan lainnya kepada perangkat yang terhubung ke jaringan. Dengan DHCP, perangkat dapat memperoleh alamat IP tanpa perlu dikonfigurasi secara manual.

4.	DHCP Client adalah perangkat atau sistem dalam jaringan yang meminta alamat IP dan konfigurasi jaringan lain dari DHCP Server secara otomatis. Ketika terhubung ke jaringan, DHCP Client mengirimkan permintaan ke DHCP Server, dan server akan memberikan alamat IP serta informasi konfigurasi seperti gateway, DNS server, dan subnet mask kepada client tersebut.

5.	- IP Class A
IP yang umumnya digunakan untuk organisasi atau jaringan yang sangat besar. IP Class ini memiliki jumlah host per jaringan sebanyak 16 juta dengan jumlah jaringan 128 jaringan dan memiliki IP Address mulai dari 1.0.0.0 hingga 126.0.0.0
- IP Class B
IP ini digunakan untuk jaringan sedang hingga besar seperti universitas atau Perusahaan. Memiliki jumlah host per jaringan sebanyak 65 ribu dengan jumlah jaringan 16384 jaringan. IP Address dimulai dari 128.0.0.0 hingga 191.255.0.0
- IP Class C
IP yang biasanya digunakan untuk jaringan kecil atau local seperti kantor atau rumah. IP ini memeiliki jumlah jaringan hingga 2 juta lebih jaringan dengan jumlah host per jaringannya adalah 254 host. IP Address yang digunakan mulai dari 192.0.0.0 hingga 223.255.255.0

6.	Firewall adalah sistem keamanan jaringan yang memantau dan mengontrol lalu lintas data masuk dan keluar berdasarkan aturan keamanan yang telah ditentukan. Firewall berfungsi sebagai penghalang antara jaringan internal yang aman dan jaringan eksternal yang berpotensi berbahaya, dengan tujuan mencegah akses tidak sah, serangan siber, atau aktivitas berbahaya lainnya.

7.	NAT  atau Network Address Translation adalah metode yang digunakan dalam jaringan untuk mengubah atau menerjemahkan alamat IP dari perangkat yang berada di dalam jaringan lokal menjadi alamat IP publik saat perangkat tersebut berkomunikasi ke internet. NAT biasanya diterapkan pada router atau firewall yang menghubungkan jaringan internal ke jaringan eksternal.

8.	Routing adalah proses menentukan jalur terbaik untuk mengirimkan data dari satu jaringan ke jaringan lain dalam sebuah jaringan komputer. Dalam proses ini, router atau perangkat jaringan lainnya menganalisis informasi jaringan untuk menentukan jalur tercepat atau paling efisien agar paket data sampai ke tujuan dengan tepat.
 
Studi Kasus 
Langkah-langkah yang harus dilakukan untuk mencapai topologi jaringan seperti gambar di soal adalah sebagai berikut :
1.	Persiapkan Perangkat
Pastikan Router dapat terhubung ke internet dan siapkan laptop yang memiliki fungsi VPCS (Virtual PC Simulator) jika digunakan dalam Cisco Packet Tracer.
2.	Konfigurasi Router
Hubungkan Router ke internet dengan menyambungkan port WAN router ke sumber internet. Konfigurasi WAN lalu konfigurasi NAT (Network Address Translation) jika router akan menerjemahkan Alamat IP privat ke Alamat public.
3.	Konfigurasi LAN pada Router
Atur IP Lan pada Router dan aktifkan DHCP Server di Router agar perangkat yang terhubung secara otomatis mendapatkan alamat IP.
4.	Koneksikan Laptorp ke Router
Sambungkan laptop menggunakan kabel ethernet atau melalui Wi-Fi tergantung jenis koneksi yang diinginkan.
5.	Verifikasi Koneksi
Periksa IP di Laptop, cek apakah laptop telah menerima IP dari router dengan cara ipconfig pada Command Prompt di Windows atau ifconfig pada Linux.
Tes koneksi ke Router dengan ping alamat IP router dari laptop.
