1. Kepanjangan dari HTML adalah Hyper Text Markup Language yang merupakan sebuah fondasi dasar dalam pembuataan halaman WEB 
HTML menjelaskan struktur halaman Web
HTML terdiri dari serangkaian elemen
Elemen HTML berkomunikasi dengan browser cara menampilkan konten
Elemen HTML memberi label pada bagian konten seperti Home, Aboutme, Contactme,


<title>menentukan judul untuk halaman HTML</title>(ditampilkan di bilah judul browser atau di tab halaman)
<h1>Heading</h1>
<p>Paragraf</p>
mendefinisikan judul besar
mendefinisikan paragraf

![Screenshot 2024-04-05 174354](https://github.com/ndan47/praktikum-web-1/assets/164461477/c90fb6f0-9150-4eef-b5a2-da3aae3c685d)

<img src="https://en.wikipedia.org/wiki/File:Iron_Man_(circa_2018).png" 
  alt="Ironman" width="500" height="333">
mendefinisikan gambar
![Screenshot 2024-04-05 185047](https://github.com/ndan47/praktikum-web-1/assets/164461477/6865f5fb-98a2-424f-aec7-bb717a524b39)

<table style="width:100%">
  <tr>
    <th>Person 1</th>
    <th>Person 2</th>
    <th>Person 3</th>
  </tr>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
</table>
mendefinisikan tabel

![Screenshot 2024-04-05 193644](https://github.com/ndan47/praktikum-web-1/assets/164461477/51362fb9-adbc-4563-9d7a-9674fbd975ad)


Atribut HTML
Tag mendefinisikan hyperlink. Atribut hrefmenentukan URL halaman yang dituju.
Tag digunakan untuk menyematkan gambar di halaman HTML. Atribut sr cmenentukan jalur ke gambar yang akan ditampilkan.
Tag juga harus berisi atribut widthand height, yang menentukan lebar dan tinggi gambar:
Atribut yang diperlukan alt untuk  tag menentukan teks alternatif untuk suatu gambar, jika gambar karena alasan tertentu tidak dapat ditampilkan. Hal ini dapat disebabkan oleh koneksi yang lambat, atau kesalahan pada srcatribut, atau jika pengguna menggunakan pembaca layar.

2. Kepanjangan dari CSS adalah (Cascading Style Sheets) : CSS diibaratkan mendekorasi sebuah fondasi basic atau bahasa yang digunakan untuk menata gaya dokumen HTML.
Boxmodel.html : Sebuah kotak yang membungkus setiap elemen HTML. Terdiri dari: konten, padding, border dan margin. Konten itu isi dari box, padding:jarak area konten, border:garis yang mengelilingi konten, margin:jarak luar konten. width itu menentukan ukuran lebar, height itu menentukan ukuran tinggi
Outline.html : Garis gambar di sekeliling elemen, di luar batas, untuk membuat elemen "menonjol". Properti outline-style menentukan gaya kerangka, dan dapat memiliki salah satu nilai berikut: dotted- Mendefinisikan garis putus-putus dashed- Mendefinisikan garis putus-putus solid- Mendefinisikan garis besar yang solid Didalam outline kita juga dapat menentukan width(lebar),color(warna)
tabel.html : Dapat menentukan font, border, padding, text-align, color, dll. Agar saat kursor mengarahkan ke arah salah satu baris bisa berubah warna kalian bisa menggunakan hover di tr
text.html : Properti ini text-decoration-linedigunakan untuk menambahkan garis dekorasi pada teks. Properti color dapat menambahkan warna pada teks. Combinator CSS merupakan sesuatu yang menjelaskan hubungan antar penyeleksi. salah satu combinator : The general sibling selector memilih semua elemen yang merupakan saudara berikutnya dari elemen tertentu.

Syntax contoh : h1 {color:blue; font-size:12px;}
h1 = Selector Deklarasi
color: = property
blue; = value
font-size: = property
12px; = value


3. Kepanjangan dari JS adalah JavaScript merupakan salah satu bahasa pemrograman, dan diibaratkan dengan adanya JavaScript suatu WEBSITE itu hidup atau di ibaratkan suatu bentuk rumah terdapat pintu maupun jendela agar bisa diakses
   Pro[erti-properti dalam JavaScript
    
    innerText = mengubah text dalam tag
    textContent = mengubah text dalam tag html
    document.getElementById = untuk id
    document.getElementsByTagName; = untuk tag
    document.getElementsByClassName; = untuk kelas
    document.querySelector('#title'); = untuk id
    document.querySelector('title'); = untuk kelas
    document.querySelector('div'); = untuk id
    console.log("Hello World"); = menampilkan tex
    innerHtml = mengakses tag html
