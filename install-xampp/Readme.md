# Cara Install XAMPP di Linux Ubuntu 20.04
1. Download dulu xampp [Di Sini](https://www.apachefriends.org/download.html) pilih XAMPP For Linux dan pilih versinya
2. Buka terimal dengan perintah ```Ctrl+Alt+T```
3. Masuk ke directory Downloads dengan peritah ```cd Downloads/```
4. Cek xampp hasil downloads dengan perintah ```ls```
5. Ketikan perintah ```chmod +x xampp-linux-x64-8.0.1-1-installer.run```
6. Ketikan perintah ```sudo  ./xampp-linux-x64-8.0.1-1-installer.run```
7. Lalu akan muncul tampilan windows installer xampp tinggal tekan tombol next dst..
8. Selesai..

# Cara untuk menjalankan XAMPP di Linux
1. Buka terminal dengan perintah ```Ctrl+Alt+T``` 
2. Ketikan perintah ``` sudo /opt/lampp/lampp start ```
3. Local Server sudah bisa digunakan

# Cara untuk menghentikan XAMPP di Linux
1. Buka terminal dengan perintah ```Ctrl+Alt+T``` 
2. Ketikan perintah ``` sudo /opt/lampp/lampp stop ```

# Fix error Apache tidak mau berjalan
1. Install net-tools dengan perintah ```sudo apt-get install net-tools```
2. Lalu jalankan kembali dengan perintah ``` sudo /opt/lampp/lampp start ```
3. Jika muncul error seperti ini ```AMPP: Starting Apache...fail. XAMPP:  Another web server is already running.```
4. Maka stop terlebih dahulu dengan perintah ```sudo /etc/init.d/apache2 stop```
5. Lalu jalankan kembali dengan perintah No.2

# Cara Uninstall XAMPP
1. Buka terminal dan masuk sebagai super user dengan perintah ```sudo su``` dan masukkan passwordnya
2. Masuk ke direktori file lampp dengan perintah ``` cd /opt/lampp ```
3. Uninstall dengan perintah ```./uninstall```
4. Lalu pilih yes
5. Selesai