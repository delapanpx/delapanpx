---
title: Beralih ke Jekyll
updated: 2017-12-11
excerpt: "Setelah menggunakan blogspot, entah mengapa saya kangen banget sama Jekyll"
---

Sudah cukup banyak platform untuk ngeblog yang saya cobain, mulai dari [wordpress.com](https://wordpress.com) (subdomain wordpress, free), kemudian pindah ke [blogspot](https://blogger.com), lalu kemudian pindah ke [tumblr](https://tumblr.com), kemudian sempat nyaman ngeblog di [medium](https://medium.com), lalu sempet pindah ke [postach](https://postach.io), terus hosting sendiri [wordpress](https://wordpress.org), lalu kemudian nyobain web statis seperti [Jekyll](https://jekyllrb.com/) dan [Grav](https://getgrav.org/). Kemudian terakhir saya kembali menggunakan Blogspot cukup lama.

Setelah menggunakan blogspot, entah mengapa saya kangen banget sama Jekyll, web statis yang ternyata banyak banget yang pake, walaupun rata-rata penggunanya adalah programmer. Perbedaan dengan Grav adalah jekyll menurut saya lebih mudah dikostumisasi, dan juga minim error, maksudnya, ketika saya pake Grav CMS terus otak-atik tema dan plugin, entah kenapa tau-tau error, dan saya engga tau sama sekali letak kesalahannya.

Pada akhir 2017 ini saya kembali lagi membuka artikel-artikel tentang Jekyll ini. Kemudian saya bertekad untuk memindahkan postingan-postingan saya di [Blogspot](https://delapanpx.blogspot.co.id) ke Jekyll ini. Selain karena saya lebih nyaman menggunakan Jekyll, juga karena dalam rangka branding. Kalau Delapan Megapiksel adalah web khusus fotografi dan portofolio fotografi saya, maka Delapan Piksel ini adalah blog saya pribadi, isinya bener-bener engga khusus, yang pasti isinya adalah opini pribadi saya,

Sebagai awalan, saya langsung fork/kloning template yang bagus banget ke repository github saya, template tersebut adalah [The Plain v3.0](https://github.com/heiswayi/the-plain). Templatenya entah kenapa saya suka sekali, minimalis, dan simpel. Saya enggan menggunakan template yang modern yang mirip dengan template bawaan [Ghost](https://ghost.org). Karena tujuan saya adalah supaya pembaca nyaman membaca blog saya, maka saya menggunakan The Plain ini. Dan dengan jahatnya saya menghilangkan credit [programmer yang bikin template ini](http://heiswayi.github.io "heiswayi.github.io"), maafkan. 

Namun seperti kebiasaan saya, saya engga memakai secara gitu aja template ini, saya melakukan cukup banyak perubahan pada layout, dan settingan. Semuanya saya setup menggunakan sublime text 2, bahkan untuk menulis post juga.

### Sedikit Setup 

Buat pengguna Windows seperti saya, kamu bisa [menginstall jekyll dengan cara ini](https://davidburela.wordpress.com/2015/11/28/easily-install-jekyll-on-windows-with-3-command-prompt-entries-and-chocolatey/ "Easily install Jekyll on Windows with 3 command prompt entries and Chocolatey"). Tujuan menginstall jekyll di windows adalah supaya development bisa dilakukan offline. Cara menginstallnya mudah banget, apalagi buat pengguna windows 10 yang sudah Anniversary Update, karena bisa menggunakan command seperti di linux atau mac.

Pada template The Plain ini, sayangnya belum diatur metanya sedemikina rupa sehingga kalau melakukan sharing post ke facebook dan twitter, tampilannya jadi jelek banget. Untuk itu saya mengubah isi header template ini dengan panduan yang dijelaskan di [artikel ini](http://aramzs.github.io/jekyll/social-media/2015/11/11/be-social-with-jekyll.html "How to make your Jekyll site show up on social"). 

Saya mengubah lebar pada layout post yang tadinya 500px menjadi 600px, sama seperti lebar maksimal foto-foto yang saya upload di github ini. Selain itu saya juga mengganti tampilan separator atau tag hr menjadi seperti mirip medium. Entah kenapa saya suka sekali sama separator yang ada di medium.

Karena pada template ini saya tidak bisa menambahkan caption gambar, maka saya melakukan sedikit pengaturan, saya menggunakan tag include dan menyiapkan baris kode yang memudahkan saya memuat caption gambar, untuk lebih jelasnya bisa [membaca artikel ini](https://eduardoboucas.com/blog/2014/12/07/including-and-managing-images-in-jekyll.html "Including And Managing Images in Jekyll"). Dan juga karena pada template ini tidak ada pengaturan menampilkan menu navigasi, maka saya sedikit menambahkan pengaturan seperti yang dijelaskan pada [artikel ini](https://codegaze.github.io/2015/08/08/how-to-create-a-dynamic-navigation-menu-in-jekyll/ "Dynamic navigation for Jekyll"). Untuk mengatasi embed video dari streaming seperti youtube dan vimeo supaya hasilnya responsif, maka saya mengikuti sesuai yang ada di [artikel ini](https://eduardoboucas.com/blog/2016/12/21/responsive-video-embeds-jekyll.html "Creating responsive Video Embeds in Jekyll").  

### Credit
- [Easily install Jekyll on Windows with 3 command prompt entries and Chocolatey](https://davidburela.wordpress.com/2015/11/28/easily-install-jekyll-on-windows-with-3-command-prompt-entries-and-chocolatey/)
- [How to make your Jekyll site show up on social](http://aramzs.github.io/jekyll/social-media/2015/11/11/be-social-with-jekyll.html)
- [Including And Managing Images in Jekyll](https://eduardoboucas.com/blog/2014/12/07/including-and-managing-images-in-jekyll.html)
- [Dynamic navigation for Jekyll](https://codegaze.github.io/2015/08/08/how-to-create-a-dynamic-navigation-menu-in-jekyll/)
- [Creating responsive Video Embeds in Jekyll](https://eduardoboucas.com/blog/2016/12/21/responsive-video-embeds-jekyll.html)
- [Using Jekyl 2017 - Mademistakes](https://mademistakes.com/articles/using-jekyll-2017/)
- [Sumber belajar jekyll yang berguna dari Mademistakes](https://mademistakes.com/articles/)



