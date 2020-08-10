# Modul1_NodeJS
#
## PENGEERTIAN NODE JS

> Node.js adalah platform perangkat yang berjalan pada sisi-backend (server) dan aplikasi jaringan dengan menggunakan Engine ‘V8’, dan memberikan kemampuan untuk menghasilkan situs web yang berjalan dengan dinamis. Node.js dibuat berdasarkan runtime Javascript, dan dapat dijalankan oleh berbagai  macam sistem operasi. Node.js pun memiliki banyak pustaka HTTP yang dapat membuat menjalankan server tanpa program server web seperti Apache, dan lain-lain.

#
## INSTALASI NODE JS
### Gimana Caranya ??
- [x] Buka Situs Resmi Node JS  [Klik Disini ](https://nodejs.org/en/).
- [x] Setelah itu silahkan unduh installer Node.js (Disarankan unduh yang versi LTS) 
- [x] Jika sudah terdownload Silahkan Di install seperti biasa
#
## NODE JS VERSION TEST
Setelah proses install selesai, anda pun dapat menjalankan Node.js sekarang! Untuk memastikan Node.js telah ter-install dengan benar, silahkan buka CLI anda, dan ketikan kode ini: “node --version” (tanpa tanda petik).  Jika versi Node.js tampil (seperti dibawah), maka Node.js telah ter-install dengan benar.


![Alt text](https://github.com/Syihabuddinsanni/Modul1_NodeJS/blob/master/SS/Node%20Version.PNG)

#
## BASIC NODE JS WEB APPLICATION
Ini adalah aplikasi web Node.js yang menggunakan EJS sebagai rendering template websitenya. Dan kitapun telah memasuki kawasan NPM , dan juga kawasan tingkat lanjut di pemrograman web Node.js.

1. Buat Folder Baru 
2. Kemudian Jalankan Terminal yang sudah di ganti direktorinya Ke Folder baru tadi 
#### Gimana cara ganti direktorinya ?
    CD : Berfungsi Untuk Masuk Ke direktori yang dituju
    ls : Untuk Menampilkan Direktori yang ada
    cd + nama direktori = Masuk Ke direktori yang dituju :v

Lalu ketikan Commands berikut Tanpa [ " ]
#
     "npm init --yes"
#


    
![Alt text](https://github.com/Syihabuddinsanni/Modul1_NodeJS/blob/master/SS/Npm%20init%20yes.PNG)

#
Nah Setelah itu, Secara Otomatis file bernama "package.json" terbuat.

![Alt text](https://github.com/Syihabuddinsanni/Modul1_NodeJS/blob/master/SS/Package%20Json.PNG)
### apa fungsi "package.json" ??
> Fungsinya yaitu sebagai manifesto dari Node.js dan mengandung _mentada_ projek Node.js tersebut
#

3. Selanjutnya kita akan melakukan instalasi terhadap _dependencies_ tersebut dengan menjalankan code berikut
Tanpa [ " ]

    "npm install ejs express semantic-ui-css --save"

   
