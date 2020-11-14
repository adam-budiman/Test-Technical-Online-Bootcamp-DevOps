DNS adalah singkatan dari Domain Name System yang merupakan sebuah sistem untuk menyimpan informasi tentang nama host maupun nama domain dalam bentuk basis data tersebar (distributed database) di dalam jaringan komputer, misalkan: Internet. DNS menyediakan alamat IP untuk setiap nama host dan mendata setiap server transmisi surat (mail exchange server) yang menerima surat elektronik (email) untuk setiap domain.DNS biasanya digunakan sebuah Layanan Nama Domain untuk menyelesaikan permintaan untuk nama-nama website menjadi alamat IP untuk tujuan menemukan layanan komputer serta perangkat di seluruh dunia. DNS menyediakan pelayanan yang cukup penting untuk internet, ketika perangkat keras komputer dan jaringan bekerja dengan alamat IP untuk mengerjakan tugas seperti pengalamatan dan penjaluran (routing), manusia pada umumnya lebih memilih untuk menggunakan nama host dan nama domain, contohnya adalah penunjukan sumber universal (URL) dan alamat surel. Analogi yang umum digunakan untuk menjelaskan fungsinya adalah DNS bisa dianggap seperti buku telepon internet dimana saat pengguna mengetikkan www.indosat.net.id di peramban web maka pengguna akan diarahkan ke alamat IP 124.81.92.144 (IPv4) dan 2001:e00:d:10:3:140::83 (IPv6).

Cara Kerja DNS
DNS resolver melakukan pencarian alamat host pada file HOSTS. Jika alamat host yang dicari sudah ditemukan dan diberikan, maka proses selesai.
DNS resolver melakukan pencarian pada data cache yang sudah dibuat oleh resolver untuk menyimpan hasil permintaan sebelumnya. Bila ada, kemudian disimpan dalam data cache lalu hasilnya diberikan dan selesai.
DNS resolver melakukan pencarian pada alamat server DNS pertama yang telah ditentukan oleh pengguna.
Server DNS ditugaskan untuk mencari nama domain pada cache-nya.
Apabila nama domain yang dicari oleh server DNS tidak ditemukan, maka pencarian dilakukan dengan melihat file database (zones) yang dimiliki oleh server.
Apabila masih tidak ditemukan, pencarian dilakukan dengan menghubungi server DNS lain yang masih terkait dengan server yang dimaksud. Jika sudah ditemukan kemudian disimpan dalam cache lalu hasilnya diberikan ke client (melalui web browser).
Jadi, jika apa yang dicari di server DNS pertama tidak ditemukan. Pencarian dilanjutkan pada server DNS kedua dan seterusnya dengan 6 proses yang sama seperti di atas. Perlu dicatat, pencarian dari client ke sejumlah server DNS dikenal dengan istilah proses pencarian iteratif sedangkan proses pencarian domain antar server DNS dikenal dengan istilah pencarian rekursif.

![bagaimana-cara-kerja-dns](https://user-images.githubusercontent.com/63648786/99139783-618fbc80-266e-11eb-8250-afd74d4dd9b0.png)

Cara kerja DNS secara Umum

