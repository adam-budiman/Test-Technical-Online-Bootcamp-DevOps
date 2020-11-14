![49e298a6-cara-membuat-akun-ssh-gratis-serta-situs-ssh-gratis](https://user-images.githubusercontent.com/63648786/99139561-69e6f800-266c-11eb-9ec0-381e865fd7b3.png)

1. Selalu menggunakan akses SSH
Tips menjaga keamanan server yang pertama saat melakukan login server secara remote dengan bantuan Secure Shell (SSH). 
SSH adalah protokol jaringan yang dikelngkapi dengan fitur enkripsi kriptografi sehingga lebih aman saat melakukan login server dibandingkan login secara langsung.

![Port-Standart-SSH-768x237](https://user-images.githubusercontent.com/63648786/99139585-a581c200-266c-11eb-8594-14e39ca3af08.png)

2. Merubah port standart
SSH memiliki port default 22, jadi agar tidak semua orang mengetahui port yang Anda gunakan untuk login maka sebaiknya merubah port standart. 
Dengan merubah port default akan membuat orang lain kesulitan saat mengakses server. Selain itu dengan port SSH sudah tidak standart lagi akan mencegah dari script jahat yang mencoba masuk lewat port standart yang belum diganti.
Untuk merupah port SSH standart caranya gampang, Anda tinggal masuk ke bagian file konfigurasi SSH sesuai dengan sistem operasi yang diinstall pada server. 
Selain itu perlu dicatat juga jangan sampai port yang Anda rubah bertabrakan dengan port aplikasi lain yang bisa menyebabkan error pada server.

3. Menggunakan password yang kuat
Tips menjaga keamanan yang ketiga yaitu dengan menggunakan password yang kuat. Secara default server akan memberikan password hasil generator yang kuat, tetapi memang sulit sekali diingat, solusinya Anda bisa mencatatnya. 
Password ini menjadi ancaman terbesar dalam keamanan internet, jadi jangan sampai asal membuat password seperti 12345, abcde, ~!@#$%, rahasia dan password lemah lainnya.
Untuk proteksi keamanan server tambahan, Anda bisa mengaktifkan two factor authentication, sehingga saat login akan selalu meminta kode verifikasi yang dikirimkan kepada Anda.

4. Menonaktifkan akun root
Selain menggunakan password yang kuat, ada satu hal penting yaitu menonaktifkan akun root server. Bayangkan jika ada hacker yang bisa mengakses root server, semua file yang ada pada server bisa dikuasainya dengan mudah. 
Hal ini cukup berbahaya untuk keamanan server website, solusinya bisa dengan menonaktifkan akun root server. 
Jadi untuk amannya Anda bisa memberikan permission untuk setiap orang yang login sesuai dengan keperluannya saja, tidak perlu memberikan akses full root kepada user.

![064d93_5856f7afe1ec4f0595425a27735bd44e_mv2](https://user-images.githubusercontent.com/63648786/99139634-30fb5300-266d-11eb-9891-4c61379b8389.jpg)

5. Selalu update server
Update tujuan utamanaya adalah menyempurnakan fitur-fitur yang ada dan menutup bug yang ada. 
Jadi jika sewaktu-waktu ada notifikasi update server lebih baik segera dilakukan saja, karena ini memiliki kaitan penting dengan keamanan server website.

6. Hindari download tidak jelas
Saat melakukan installasi software aplikasi server, usahakan untuk menjaga keamanan server jangan melakukan download dari sumber-sumber yang tidak jelas, besar kemungkinan software aplikasi tersebut disusupi malware yang bisa mengancam keamanan server website. usahakan download pada website-website resminya langsung, bukan dari website download software.

7. Menonaktifkan port network
Tidak semua port yang ada di server digunakan, makanya diawal tadi Anda bisa merubah  port standart dari SSH. Selain itu Anda bisa menonaktifkan port network yang tidak terpakai, karena port yang terbuka dan tidak dipakai akan menjadi target dari serangan hacker untuk menjalankan aksinya.

![Firewall-Server-768x444](https://user-images.githubusercontent.com/63648786/99139649-5e480100-266d-11eb-9e69-3a9ef9caf386.png)

8. Setting konfigurasi firewall
Firewall pada server memiliki tugas untuk mengelola dan memantau trafik yang keluar masuk pada server sesuai dengan konfigurasi security yang sudah ditentukan. Firewall berfungsi untuk memblokir akses illegal ke dalam jaringan server seperti serangan bruteforce, blokir IP, SQL Injection dan lainnya.

9. Menggunakan SFTP
SFTP atau Secure File Transfer Protocol adalah aplikasi pertukaran data yang digunakan antara server dan client dengan keunggulan lebih aman dari FTP biasa. Jika Anda belum tahu tentang kegunaan dan fungsi File Transfer Protocol silahkan baca pada pembahasan sebelumnya.

10. Setting folder read-only
Salah satu cara untuk mengamankan file dari folder adalah dengan seting read-only. Jadi Anda perlu memodifikasi default akses folder dari ‘read-write’ menjadi ‘read-only’. Hal ini cukup penting untuk menjaga keamanan server dari serangan hacker.

11. Install antivirus
Walaupun sudah ada firewall, untuk menjaga keamanan server Anda masih memerlukan adanyanya antivirus. Antivirus terbukti lebih ampuh untuk mencegah serangan malware dan virus yang mengarah pada server. Biaya yang Anda keluarkan untuk invest antivirus ini jauh lebih murah jika dibandingkan server rusak karena terkena serangan malware yang menakibatakn website down.

12. Memasang monitoring server
Server monitoring memungkinkan Anda memantau secara realtime keadaan server, jadi tidak perlu melakukan login dengan SSH untuk tahu keadaan server. Nantinya jika terjadi hal yang tidak wajar Anda bisa langsung action untuk mengetahui permasalahan yang terjadi pada server.

13. Menggunakan SSL
Nah tips menjaga keamanan server website yang terakhir adalah dengan menggunakan SSL. SSL memungkinkan komunikasi antar server dan web browser berjalan dengan aman tanpa adanya hacker yang bisa mencuri datanya. Karena SSL sekarang ini sudah menggunakan enkrispi 256 bit yang tidak mungkin bisa ditembus oleh hacker dengan waktu yang sangat singkat sekali. Jika Anda membutuhkan layanan SSL Indonesia saat ini, kami memiliki rekomendasi pembelian SSL di GudangSSL.id. Cukup dengan harga 150.000/tahun Anda sudah bisa memiliki Sectigo PositiveSSL.
