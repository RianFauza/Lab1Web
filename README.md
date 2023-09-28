# Lab1Web
# 1. Membuat Paragraf
![Screenshot (26)](https://github.com/RianFauza/Lab1Web/assets/115771479/f9dc0ae8-c2c3-4315-9009-4c4800135e08)

# 2. Menambahkan Judul
![Screenshot (27)](https://github.com/RianFauza/Lab1Web/assets/115771479/1292cb8c-fe19-42af-a4ec-5029f5f6abd7)

# 3. Memformat Teks
![Screenshot (30)](https://github.com/RianFauza/Lab1Web/assets/115771479/5949f02a-2b28-4db7-9594-cba5407301ef)

# 4. Menyisipkan Gambar
![Screenshot (31)](https://github.com/RianFauza/Lab1Web/assets/115771479/fe8287c0-5091-457d-9fbd-7d1fd57a2426)

# 5. Menambahkan Hyperlink
![Screenshot (32)](https://github.com/RianFauza/Lab1Web/assets/115771479/bfbf2c7d-a855-46f2-8f78-9fdd44b97bd8)

# Jawab Pertanyaan

# 1. apa perbedaan dari tag `<p>` dengan tag `<br>`, berikan penjelasannya!
   
  Tag HTML `<p>` dan `<br>` memiliki fungsi yang berbeda dalam struktur dan tampilan halaman web:

   1. Tag `<p>` (Paragraph):
      - Tag `<p>` digunakan untuk membuat paragraf teks pada halaman web.
      - Ini adalah elemen blok, yang berarti bahwa setiap elemen `<p>` biasanya dimulai pada baris baru dan memiliki jarak atas dan bawah bawaan yang mengelilingi teks di dalamnya.
      - Tag `<p>` juga secara otomatis menambahkan ruang kosong (margin) di atas dan di bawahnya, yang memisahkan paragraf dari elemen HTML lainnya.

     Contoh penggunaan tag `<p>`:
     ` <p> Ini adalah contoh paragraf pertama.</p> `
     `<p>Ini adalah contoh paragraf kedua.</p> ` 

   2. Tag `<br>` (Line Break):
      - Tag `<br>` digunakan untuk membuat pemisah baris tunggal dalam teks atau elemen lainnya.
      - Ini adalah elemen inline, yang berarti bahwa itu tidak menciptakan paragraf baru atau ruang kosong di atas atau di bawahnya.
      - Tag `<br>` hanya memindahkan teks atau elemen di bawahnya ke baris baru tanpa menambahkan jarak ekstra.
        
     Contoh penggunaan tag `<br>`:   
     ` Ini adalah teks pertama.`<br>`Ini adalah teks kedua. `

Jadi, perbedaan utama antara keduanya adalah bahwa `<p>` digunakan untuk membuat paragraf teks dengan jarak atas dan bawah yang lebih besar, sementara `<br>` digunakan untuk membuat pemisah baris tunggal tanpa menambahkan ruang ekstra.


# 2. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!

  Atribut "title" dan "alt" pada tag <img> digunakan untuk tujuan yang berbeda dan memiliki fungsi yang berbeda:

   1. Atribut "alt" (Alternative Text):
     - Atribut "alt" digunakan untuk memberikan teks alternatif yang menjelaskan gambar tersebut.
     - Fungsinya adalah memberikan deskripsi singkat tentang gambar kepada pengguna yang mungkin tidak dapat melihat gambar tersebut. Ini adalah contoh praktik terbaik dalam aksesibilitas web.
     - Ketika gambar tidak dapat dimuat atau jika seseorang menggunakan pembaca layar, teks alternatif ini akan dibacakan kepada pengguna, membantu mereka memahami konten gambar tersebut.
     - Atribut "alt" juga berperan penting dalam optimasi mesin pencari (SEO) karena membantu mesin pencari memahami konten gambar.

     Contoh penggunaan atribut "alt":  
      ` (img src="LOGO_UPB.png" alt="Sebuah gambar berisi LOGO UPB") `

   2. Atribut "title":
      - Atribut "title" digunakan untuk memberikan informasi tambahan tentang gambar ketika pengguna mengarahkan kursor mouse ke gambar tersebut.
      - Ini memberikan tooltip atau petunjuk teks yang muncul saat pengguna mengarahkan kursor ke gambar tanpa mengkliknya.
      - Atribut "title" digunakan untuk memberikan keterangan tambahan atau konteks terkait gambar, seperti penjelasan singkat tentang gambar atau kredit untuk sumber gambar

     Contoh penggunaan atribut "title":
     ` <img src="LOGO_UPB.png" alt="Sebuah gambar berisi LOGO UPB" title="Universitas Pelita Bangsa"> `
     
Jadi, perbedaan utama antara kedua atribut ini adalah bahwa "alt" digunakan untuk memberikan teks alternatif yang berguna dalam hal aksesibilitas dan SEO, sementara "title" digunakan untuk memberikan informasi tambahan dalam bentuk tooltip saat pengguna mengarahkan kursor ke gambar.

# 3. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!

  Untuk mengatur ukuran gambar dalam HTML, dapat menggunakan atribut "width" (lebar) dan "height" (tinggi). Untuk mempertahankan proporsi gambar yang baik, disarankan untuk mengisi salah satu dari kedua atribut ini sambil membiarkan yang lainnya kosong. Jika Anda mengisi kedua atribut "width" dan "height" dengan nilai yang berbeda, gambar mungkin akan terdistorsi dan tidak proporsional.

  1. Mengisi Hanya Atribut "width" atau "height" (Tidak Mengisi Keduanya):
     - Jika Anda hanya mengisi salah satu atribut, seperti "width" dan tidak mengisi "height", browser akan secara otomatis menghitung tinggi gambar agar sesuai dengan proporsi aslinya. Ini akan menjaga proporsi gambar dan mencegah distorsi.

     Contoh: ` <img src="gambar.jpg" alt="Sebuah gambar" width="300"> `
     
     Dalam contoh di atas, tinggi gambar akan disesuaikan otomatis agar sesuai dengan proporsinya.
     
  2. Mengisi Keduanya dengan Nilai yang Sama:
     - Jika Anda ingin gambar memiliki lebar dan tinggi yang tetap, Anda dapat mengisi keduanya dengan nilai yang sama. Ini akan membuat gambar menjadi kotak (persegi).

     Contoh: ` <img src="gambar.jpg" alt="Sebuah gambar" width="300" height="300"> `

     Dalam contoh di atas, gambar akan ditampilkan dalam bentuk persegi dengan lebar dan tinggi 300 piksel.

  3. Mengisi Keduanya dengan Nilai yang Berbeda:
     - Jika Anda mengisi kedua atribut "width" dan "height" dengan nilai yang berbeda, gambar dapat terdistorsi dan tidak akan mempertahankan proporsi aslinya.

     Contoh: ` <img src="gambar.jpg" alt="Sebuah gambar" width="300" height="200"> `

     Dalam contoh di atas, gambar mungkin terlihat terdistorsi jika aspek rasionya tidak sama dengan yang asli.

Untuk memastikan gambar tetap proporsional, Anda dapat mengisi salah satu atribut (biasanya "width") dan membiarkan yang lainnya kosong atau tidak diisi. Ini akan memungkinkan browser untuk menghitung nilai yang sesuai untuk atribut yang tidak diisi, menjaga gambar tetap terlihat baik.

# 4. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?

  Atribut "target" pada elemen <a> (link) digunakan untuk mengontrol perilaku navigasi saat pengguna mengklik link. Nilai atribut "target" dapat bervariasi dan memiliki efek yang berbeda:

  1. _blank:
     - Ketika Anda menggunakan "target="_blank"", link akan membuka halaman atau tautan baru dalam tab atau jendela browser yang baru.Ini membuat pengguna tetap berada di halaman asli sementara membuka tautan dalam tab/jendela yang terpisah.
     - Ini umumnya digunakan untuk membuka tautan eksternal atau tautan yang tidak ingin menggantikan halaman asli.

     Contoh: ` <a href="https://www.contoh.com" target="_blank">Kunjungi Contoh.com</a> `

  2. _top:
     - Ketika Anda menggunakan "target="_top"", link akan membuka halaman baru dalam jendela atau tab yang sama seperti halaman asli, tetapi jika halaman tersebut ada dalam bingkai (frame), maka link akan membuka halaman baru di jendela/tab paling atas, keluar dari semua bingkai.
     - Ini berguna ketika Anda ingin keluar dari bingkai dan memuat halaman secara independen.

     Contoh: ` <a href="halaman-baru.html" target="_top">Buka Halaman Baru di Jendela Utama</a> `

  3. _parent:
     - Ketika Anda menggunakan "target="_parent"", link akan membuka halaman baru dalam jendela atau tab yang sama seperti halaman asli, tetapi jika halaman tersebut ada dalam bingkai (frame), maka link akan membuka halaman baru di bingkai induk dari halaman asli.
     - Ini berguna ketika Anda ingin memuat halaman baru di dalam bingkai yang lebih tinggi dalam hirarki bingkai.

     Contoh: ` <a href="halaman-baru.html" target="_parent">Buka Halaman Baru di Bingkai Induk</a> `

  4. _self:
     - Ini adalah perilaku default dari elemen `<a>` jika Anda tidak menggunakan atribut "target". Ketika Anda menggunakan "target="_self"", link akan membuka halaman baru dalam jendela atau tab yang sama seperti halaman asli. Ini mengganti halaman asli dengan halaman yang ditautkan.
     - Ini digunakan ketika Anda ingin menggantikan halaman saat ini dengan halaman baru.

     Contoh: ` <a href="halaman-baru.html" target="_self">Buka Halaman Baru</a> `

Dengan menggunakan atribut "target" ini, Anda dapat mengontrol dengan cermat cara halaman web terbuka saat pengguna mengklik tautan.








     








  








        


