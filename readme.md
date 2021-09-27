Pada tingkat paling dasar, situs web terdiri dari dokumen HTML dan CSS. Browser membuat representasi dokumen yang dikenal sebagai Document Object Model (DOM). Dokumen ini memungkinkan Javascript untuk mengakses dan memanipulasi elemen dan style situs web

DOM Document adalah keseluruhan objek yang ada di laman web Anda. Jika Anda ingin mengakses objek apa pun di halaman web Anda, Anda harus selalu mulai dengan dokumen tersebut. Karena ada banyak properties dan method penting yang bisa Anda gunakan untuk mengakses dan memodifikasi situs web Anda.


DOM Selector

1. Method getElementById
Selector DOM yang berfungsi untuk mengakses element html berdasarkan atribut id

```html
<!DOCTYPE html>
<html lang="en">
<head>
   <title>DOM - getElementById</title>
</head>
<body>
<h1 id="judul">halaman judul</h1>
   <script>
      let judul = document.getElementById('judul');
      judul.innerHTML = 'Ubah Halaman Judul';
   </script>
</body>
</html>
```

2. Method getElementsByTagName
Selector DOM untuk mengakses elemen html berdasarkan nama tag, dimana akan menyeleksi semua tag yang telah ditentukan dan menghasilkan HTML Collection atau sederhananaya kumpulan element html yang setiap elementnya memiliki index, dimana nilai index html collection dimulai dari angka 0.

```html
<!DOCTYPE html>
<html lang="en">
<head>
   <title>DOM - getElementsByTagName</title>
</head>
<body>
<h1>judul</h1>
<h1>judul 2</h1>
   <script>
      let h1 = document.getElementsByTagName('h1');
      h1[0].innerHTML = 'Ubah Halaman Judul 1';
      h1[1].innerHTML = 'Ubah Halaman Judul 2';
   </script>
</body>
</html>
```

3. Method getElementsByClassName
selector yang digunakan untuk mengakses elemen html berdasarkan atribut class, 

Selector DOM untuk mengakses document html baik itu tag, atribut id maupun atribut class, penulisan selectornya mirip ketika kita menggunakan selector di css,

```html
<!DOCTYPE html>
<html lang="en">
<head>
   <title>DOM - getElementsByTagName</title>
</head>
<body>
<h1>judul</h1>
<h1>judul 2</h1>
   <script>
      let h1 = document.getElementsByTagName('h1');
      h1[0].innerHTML = 'Ubah Halaman Judul 1';
      h1[1].innerHTML = 'Ubah Halaman Judul 2';
   </script>
</body>
</html>
```



halo
'


halo juga