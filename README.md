```
Sahrul Ridwansyah
TI.22.A2
312210063
```
#Pembuat paragraf

# 1.membuat paragraf

![image](https://github.com/sahrul180304/lab1web/assets/115526901/8f0ce4c4-c150-4544-b4fc-706c1554b119)

# 2.menambahkan judul

![image](https://github.com/sahrul180304/lab1web/assets/115526901/62396db5-b63d-4ead-a368-89b3cb4cc28f)

# 3.memformat text

![image](https://github.com/sahrul180304/lab1web/assets/115526901/a6272aea-73cb-4457-8a19-2f499e15a799)

# 4.menambahkan gambar

![image](https://github.com/sahrul180304/lab1web/assets/115526901/4a517404-f7b8-4d00-8fd6-ae55402b23c3)

# 5.menambahkan hyperlink

![image](https://github.com/sahrul180304/lab1web/assets/115526901/d862d66c-5a41-4acf-8b47-4691bfbd8e1b)


# 1. Apa perbedaan dari tag `<p>` dengan tag `<br>`, berikan penjelasannya!
   
   jawaban:
   
   `<p>` digunakan untuk membuat paragraf, sedangkan `<br>` digunakan untuk memberi jarak lebih ke antar paragraf
   
# 2. Apa perbedaan atribut title dan alt pada tag `<img>`, berikan penjelasannya!
   
   jawaban:
   
   perbedaan utama antara keduanya adalah bahwa alt adalah teks alternatif yang digunakan untuk tujuan
   aksesibilitas dan akan ditampilkan jika gambar tidak dapat dimuat, sementara title adalah teks tooltip
   yang memberikan informasi tambahan tentang gambar saat kursor mouse mengarah ke gambar tersebut.

   ```
   Contoh Penggunaan alt: `<img src="gambar.jpg" alt="Ini adalah gambar logo upb">`
   ```

   ```
   Contoh Penggunaan title: `<img src="gambar.jpg" alt="logo upb" title="Foto logoupb">`
   ```

# 3. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar
proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!

jawaban:

Mengisi Kedua Atribut width dan height: Ini adalah cara terbaik untuk menjaga proporsi gambar. 
Dalam kebanyakan kasus, Anda harus mengisi baik width maupun height. Ketika kedua atribut ini diisi, 
gambar akan diperkecil atau diperbesar sesuai dengan ukuran yang Anda tentukan, dan proporsinya akan tetap sama.

```
contoh: `<img src="gambar.jpg" alt="Gambar" width="300" height="200">`
```

Mengisi Salah Satu Atribut width atau height: Jika Anda hanya mengisi salah satu dari kedua atribut ini,
maka gambar akan diubah ukuran sesuai dengan atribut yang diisi, dan aspek rasio gambar mungkin akan terganggu.
Ini dapat membuat gambar terlihat terdistorsi atau tidak proporsional.

```
contoh: `<!-- Ini akan membuat gambar terlihat terdistorsi -->`
`<img src="gambar.jpg" alt="Gambar" width="300">`

`<!-- Ini juga akan membuat gambar terlihat terdistorsi -->`
`<img src="gambar.jpg" alt="Gambar" height="200">`
```

# 4. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top,_parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?

jawaban:

- _blank: Ketika Anda menggunakan target="_blank", tautan akan dibuka dalam tab atau jendela baru (pop-up),
 tergantung pada konfigurasi browser pengguna. Ini akan memisahkan halaman yang mengandung tautan dari halaman
 yang ditautkan. Ini sering digunakan untuk membuka tautan eksternal atau tautan yang mengarah ke situs web yang berbeda.

```
contoh : `<a href="https://www.contoh.com" target="_blank">`Tautan ke Contoh`</a>`
```

- _self: Ini adalah nilai default jika Anda tidak menentukan atribut target. Ketika Anda menggunakan target="_self",
 tautan akan membuka halaman baru dalam jendela atau tab yang sama di mana tautan tersebut berada. Ini adalah perilaku standar untuk tautan.

```
contoh : `<a href="halaman.html" target="_self">`Tautan ke Halaman`</a>`
```

- top: Ketika Anda menggunakan target="_top", tautan akan membuka halaman baru di jendela atau tab teratas `(top-level)`,
 menggantikan semua bingkai `(frames)` yang ada. Ini berguna jika Anda memiliki halaman yang menggunakan bingkai `(frames)`
 dan ingin mengarahkan tautan untuk membuka halaman di luar bingkai tersebut.

```
contoh : `<a href="halaman.html" target="_top">`Tautan ke Halaman Utama`</a>`
```

- parent: Ketika Anda menggunakan target="_parent", tautan akan membuka halaman baru di jendela atau tab
yang berisi bingkai (frame) yang memuat tautan tersebut. Ini berguna jika Anda memiliki halaman yang
menggunakan bingkai (frames) dan ingin mengarahkan tautan untuk membuka halaman di bingkai (frame) yang
sama dengan tautan tersebut.

```
contoh : `<a href="halaman.html" target="_parent">`Tautan ke Halaman Induk`</a>`
```



