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
