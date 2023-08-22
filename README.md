#HTML (HyperText Markup Language) merupakan HTML adalah bahasa markup standar untuk membuat halaman Web.
#Berikut ini merupakan struktur dasar dari html yaitu :
#<!DOCTYPE html>
#<html>
#	<head>
#		<title>Page Title</title>
#	</head>
#	<body>
#		<h1>My First Heading</h1>
#		<p>My first paragraph.</p>
#
#	</body>
#</html>
#
#Tag adalah sebuah penanda awalan dan akhiran dari sebuah elemen di HTML. Tag dibuat dengan kurung siku (<...>), lalu di dalamnya berisi nama tag dan kadang juga ditambahkan dengan atribut. Ada 2 bagian Tag yaitu :
#- left angle bracket (<...>)
#- right angle bracket (</...>) atau biasa disebut closing tag
#
#Untuk membuat HTML perlu disiapkan sebuah web browser sebagai penampil hasil HTML yang dibuat, visual studio code beserta extensionnya untuk sebagai media menulis HTML nya dan mempermudah pembuatannya.
#
#Berikut ini beberapa Tag HTML pada umumnya :
#- Heading, sebagai title pada umumnya seperti pada sebuah artikel
#  <h1> <h2> <h3> <h4> <h5> <h6>
#- Paraghraf. Jika ada baris kosong / white space (spasi yang lebih dari 1) akan dianggap 1 spasi
#  <p>
#- Bold dan Italic, menebalkan dan memiringkan tulisan seperti di ms.word
#  <b> <i>
#- Underline (garis bawah), Superscript (tulisan berpangkat atas), Subscript (tulisan berpangkat bawah)
#  <u> <sup> <sub>
#- Line Break (baris baru), Horizontal Rule (garis horizontal)
#  <br> <hr>
#- Strong (penebalan teks), Emphasis (memiringakn teks), Blockquote (kutipan teks panjang), Quote (kutipan pendek)
#  <strong> <em> <blockquote> <q>
#- Abbreviation (singkatan dari), Acronym (kepanjangan dari)
#  <abbr> <acronym>
#- Cite (mendefinisikan judul a karya kreatif), Definition Element (menentukan istilah yang akan didefinisikan dalam isinya)
#  <cite> <dfn>
#- Deleted (mendefinisikan text yang telah dihapus dari dokumen), Inserted (mendefinisikan text yang telah ditambahkan ke dokumen)
#  <del> <ins>
#
#
#Berikut ini beberapa attribute HTML yang biasa digunakan :
#-  <a href=""> (menuju alamat url yang diinputkan)
#-  <p align=""> (membuat perataan teks)
#-  <abbrv title=""> (menampilkan title teks)
#
#
#List HTML
#HTML sudah menyediakan elemen untuk membuat list. Ada tiga macam jenis list yang bisa dibuat di HTML:
#
#- Ordered List adalah list yang terurut
#  <ol>
#        <li>...</li>			// <li> merupakan list item
#  </ol>
#- Unordered List adalah list yang tak terurut
#  <ul>
#        <li>...</li>
#  </ul>
#- Description List adalah list yang berisi definisi
#  <dl>
#        <dt>...</dt>
#  </dl>
#
#
#Link HTML
#Link atau Hyperlink adalah elemen HTML yang berfungsi menghubungkan suatu halaman web ke halaman web yang lain. Elemen yang bisa diklik dan nanti akan membuka halaman lain sesuai alamat URL yang diberikan.
#-  <a href="https://www.google.com"> (untuk ke halaman google)
#-  <a href="about.html"> (ke halaman sendiri/file lain)
#-  <a href="html/about.html"> (ke file di folder lain)
#-  <a href="mailto:nama@email.com"> (menuju ke email)
#-  <a href="#tes"> (ke section tertentu di halaman sendiri)
#
#
#Table HTML <table>
#Salah satu cara atau format menampilkan informasi dalam web adalah dengan tabel. Berikut ini merupakan struktur membuat table.
#<table border="1">
#        <tr>
#            <th rowspan="2" bgcolor="yellow">Bulan</th>
#            <th colspan="2" bgcolor="#00ff80">Hasil Panen</th>
#        </tr>
#        <tr>
#            <th>Padi</th>
#            <th>Kacang</th>
#        </tr>
#        <tr>
#            <td>Januari</td>
#            <td>500 Kg</td>
#            <td>231 Kg</td>
#        </tr>
#</table>
#
#-  <thead> untuk membungkus bagian kepala tabel
#-  <tbody> untuk membungkus bagian body tabel
#-  <tr> untuk baris
#-  <th> untuk judul pada header
#-  <td> untuk sel
#-  attribute colspan untuk lebar kolom
#-  attribute rowspan untuk lebar baris
#
#
#Form HTML <form>
#Salah satu cara untuk mengambil informasi dari user ialah menggunakan form.
#- Field (bagian yang dapat diisi dengan data), 
#  <input type="text" name="info" />
#  untuk type ada beberapa seperti text, password, radio (linngkaran kecil), checkbox (sebuah kotak kecil), file (untuk mengisi file), dan button
#- List (membuat beberapa item sebagai mengisi data)
#  <select name="agama">
#  	<option value="islam">Islam</option>
#  	<option value="kristen">Kristen</option>
#  	<option value="hindu">Hindu</option>
#  	<option value="budha">Budha</option>
#  </select>
#
#
#Image HTML <img>
#Untuk menampilkan gambar di HTML yaitu :
#  <img src="" height="" width="" title="" align="" alt="">
#- src, lokasi gambar
#- height dan width untuk tinggi dan lebar dari gambar
#- title, judul dari gambar
#- align, perataan letak gambar
#- alt, teks alternatif untuk gambar
#
#
#Video HTML <video>
#Untuk menambahkan video di HTML yaitu :
#  <video src="" height="" width="" poster="" controls autoplay preload="" loop>
#- src, lokasi video
#- height dan width untuk tinggi dan lebar dari video
#- poster, menentukan cover dari video
#- controls, mengaktifkan kontrol video
#- autoplay, agar video diputar otomatis
#- preload, menentukan apakah video harus dimuat saat halaman dimuat
#- loop, memutar video terus menerus
#
#
#Audio HTML <audio>
#Untuk menambahkan audio hampir sama dengan video :
#  <audio src="" controls autoplay preload="" loop>
#
#
#Division <div>
#Sebagai pembungkus beberapa tag biasa disebut box
#  <div>
#	<p>...</p>
#  </div>
#
#
#
#
#
#CSS (Cascading Style Sheets) adalah bahasa yang digunakan untuk styling HTML.
#Ada beberapa melokasikan css :
#- Inline CSS, tidak direkomendasikan karena peletakan style di dalam tag sebagai attribute
#  <h1 style="color: blue">
#- Internal CSS, melokasikan css di file yang sama dengan HTML denga berada di head HTML
#  <style>
#	h1 { color: red }
#	p { font-family: arial }
#	b { color: blue }
#  </style>
#- Eksternal CSS, melokasikan CSS di file terpisah khusus untuk menyimpan semua CSS yang akan digunakan. Untuk memanggil file CSS di HTML :
#  <link rel="stylesheet" href="style-ku.css">
#  dan di file CSS :
#	h1 { color: red }
#	p { font-family: arial }
#	b { color: blue }
#
#
#CSS Selector
#Selektor adalah kata kunci dan simbol yang digunakan pada CSS untuk menyeleksi atau memilih elemen HTML. Ada beberapa selektor di CSS:
#- Universal Selector, CSS untuk semua tag dan html secara keseluruhan
#  * { fontfamily: sans }
#- Type Selector, slector khusus tag-tag tertentu
#  h1 { color: white }
#- Class Selector, dengan membuat attribute class di sebuah tag
#  li.sarapan { color: yellow }
#- Id Selector, sama dengan class, hanya bedanya boleh digunakan 1 elemen saja
#  #senin { color: red }
#- Child Selector, CSS untuk anak dari tag parent
#  p>b{ color:red }
#- Descendant Selector, memilih tag secara bersamaan secara keseluruhan
#  p b{ color: blue }
#- Adjacent Sibling Selector, CSS untuk tag setelah tag
#  p+h2{ color:blue }
#- General Sibling Selector, memilih seluruh tag setelah tag
#  h2~p{ fontfamily: arial }
#
#
#CSS Properties dan Values
#Berikut ini strukturnya :
#  h1 {
#	color: red;
#	font-family: arial;
#  }
#- color dan font-family sebagai properties
#- red dan arial sebagai values
#
#
#CSS Cascade
#Untuk membuat aturan jikalau ada beberapa CSS yang saling bertumpukan
#- Last rules dari :
#  i{ color: red }
#  i{ color: blue } (yang digunakan adalah style yg paling terakhir)
#- Last rules dari
#  b{ color: yellow }
#  p b{ color: red !important}
#  p b{ color: green } (yang akan digunakan yang ada !important)
#- Last rules dari 
#  p{ font-size: 100% }
#  p#pendahuluan{ font-size: 75% } (mengambil yang lebih spesifik)
#
#
#Inheritance
#Mengaplikasikan tag dari properties yang sudah digunakan sebelumnya. Contohnya
#- body{ padding: 10% }			// parentnya
#- .intro{ padding: inherit }		// yang akan di inheritance
#
#
#CSS Color
#Ada beberapa cara mewarnai teks :
#- Color Name
#  h1{ color: red }
#- Hex code, menggunakan kode hexadesimal, bisa 3 digit maupun 6 digit
#  h2{ color: #ffffff}
#- RGB Value, menghasilkan warna berdasarkan konsep warna RGB pada komputer
#  p{ color: rgb(255,0,0) }
#- Color Alpha, RGB dengan menambahkan efek pudar
#  h1{ backgroundcolor: rgb(255,0,119, 0.5) }
#- HSL (Hue, Saturation, Lightness), meanbahkan warna dengan cara melihat dari sudut 
#  p.paragraf1{ backgoundcolor: hsl(250,100%,50%) } 
#- HSL Alpha, HSL dengan menambahkan efek pudar
#  p.paragraf2{ backgoundcolor: hsla(250,100%,50%, 0.5) }
#
#
#CSS Text
#Beberapa attribute CSS untuk styling text:
#- Font Family, jenis teks
#- Font Size, ukuran teks
#- Font Weight, ketebalan teks
#- Font Style, gaya penulisan teks
#- Text Decoration, biasanya untuk menghilangkan garis bawah link
#  .credit{
#	font-family: Georgia;
#	font-size: large;
#	font-weight: bold;
#	font-style: italic;
#	text-decoration: none;
#  }
#- Text Transform, mengubah bentuk teks
#- Text Align, perataan text
#- Text Shadow, bayangan teks
#- Word Spacing, jarak antar huruf/character
#- Letter Spacing, jarak antar kata
#  h1{
#	text-transform: uppercase;
#	text-align: center;
#	text-shadow: 10px 5px 5px black;
#	word-spacing: 0.5em;
#	letter-spacing: 5px;
#  }
#
#
#Pseudo Class CSS
#Digunakan untuk mendefinisikan keadaan khusus dari sebuah elemen
#- Hover, apabila dihover, atau pointer berada di posisi tag
#- Active, tag disaat klik
#- Visited, tag setelah di klik
#  a.tautan:hover{ color: red }
#  a.tautan:active{ color: green }
#  a.tautan:visited{ color: blue }
#
#Atribute lainnya :
#- min-width, nilai minimum lebar jika browser berubah ukuran
#- max-width, nilai maksimum lebar jika browser berubah ukuran
#- overflow, jikalau tag melewati ukuran tag pembungkus
#  td.deskripsi{
#	min-width: 450px;
#	max-width: 500px;
#  }
#  p.satu{ overflow: scroll }
#
#
#
#CSS Box Model 
#Merupakan height dan width dari content, padding, border, margin
#  .content{
#	width: 100px;
#	height: 40px;
#	border: 20px solid red;
#	padding: 10px;
#	margin: 40px;
#  }
#
#
#
#CSS Border
#Border untuk menentukan gaya, lebar, dan warna batas tag.
#  div{ border: 5px solid brown }
#Ada beberapa properties yang pada umumnya digunakan:
#- border-top-style: solid
#- border-top-width: 4px
#- border-bottom-width: 4px
#- border-left-width: 4px
#- border-right-style: dotted
#- border-color: red
#- border-style: solid
#- border-width: 5px 10px 15px 20px	// atas kanan bawah kiri
#- border-radius: 5px
#
#
#CSS Padding
#Padding untuk membuat ruang di sekitar content elemen/tag didalam border
#  div{ padding: 20px }
#Beberapa properties padding:
#- padding: 20px 50px // atas-bawah kiri-kanan
#- padding: 20px 50px 5px // atas kiri-kanan bawah
#- padding-top: 50px
#- padding-right: 30px
#- padding-bottom: 50px
#- padding-left: 80px
#- padding block, ruang dari perbatasannya ke kontennya dalam arah beda baris
#- padding inline, ruang dari perbatasannya ke kontennya dalam arah sebaris
#
#
#CSS Margin
#Margin untuk membuat ruang di sekitar elemen diluar border
#  div{ margin: 5px }
#Beberapa properties margin:
#- margin: 10px auto
#- margin: 10px auto 30px
#- margin: auto 10px 20px 30xp
#- margin-top: 20px
#- margin-left: 20px
#- margin-right: 20px
#- margin-bottom: 20px
#
#
#Display Element
#Posisi peletakan tag/elemen
#- display: inline	(1 baris, tidak mengikuti height width tag sebelumnya)
#- display: block	(mengikuti height width tag sebelumnya, beda baris)
#- display: inline-block	(1 baris dan mengikuti height width tag sebelumnya)
#- display: flex		(menetapkan panjang fleksibel pada item fleksibel)
#- flex-wrap: wrap	(menentukan apakah item fleksibel harus dibungkus atau tidak)
#
#
#Lists Style
#Ada beberapa cara mengubah bentuk list
#- list-style-type: lower-roman	(romawi kecil)
#- list-style-type: upper-latin	(latin kapital)
#- list-style-type: lower-latin	(latin kecil)
#- list-style-type: upper-roman	(romawi kecil)
#- list-style-type: decimal	(angka)
#- list-style-position: inside	(poin-poinnya akan berada di dalam item daftar)
#- list-style-position: outside	(poin-poinnya akan berada di luar item daftar)
#
#List Shorthand
#Cara singkat untuk membuat list style dan position menjadi 1 properties
#- list-style: inside circle decimal
#
#
#Tables Style
#Ada beberapa cara mengubah bentuk table:
#- border-spacing: 10px		// mengatur jarak antara batas sel yang berdekatan
#- border-collapse: collapse	// menetapkan apakah batas tabel harus diciutkan menjadi satu batas atau dipisahkan seperti dalam HTML standar
#- tr.hover{ backgroundcolor: green }
#
#
#Form Style
#Ada beberapa membuat form menjadi lebih menarik
#- border-radius: 5px				// membuat radius ditiap sudut
#- background-image: url("../ads/asdsd.jpg")
#- background-position: 8px
#
#
#Images style
#Ada beberapa cara mengubah style image:
#- float: right
#- float: left
#
#
#CSS Layout
#- position: static	(normal)
#- position: relative	(akan bergeser dari awal posisi awal tetapi tag setelahnya tidak berubah posisi)
#- position: absolute	(relative terhadap browser, bergeser posisinya lalu diambil posisinya oleh tag setelahnya)
#- position: fixed	(mirip dengan absolute, keluar dari flownya disaat scroll posisi elemen tetap di tempat)
#- position: sticky	(campuran static dan fixed, posisi awalnya static, saat di scroll berubah menjadi fixed sesuai ukuran)
#
#
#Z-Index
#Cara mengatasi overlap, elemen akan timbul kedepan, semakin besar nilainya semakin kedepan
#  z-index: 1
#
#
#CSS Float
#Mengalokasikan elemen tetapi elemen setelahnya akan mengikuti
#- float: left 		(berada dikiri, tag sebelumnya mengambil bagian kanannya
#- float: right		(berada dikanan, tag sebelumnya mengambil bagian kirinya)
#
#
#
#CSS Layout
#- Fixed Width Layout, Membuat layout fixed tapi tidak relative sama ukuran browser
#- Liquid Layout, Membuat layout fixed dengan tambahan float
#- Responsive Layout
#  <meta name="" content="width=device-width initial-scale=1.0"> //lebarnya akan sama dengan lebar device
#- Grid Layout
#  Ada beberapa properties yang digunakan dalam grid:
#  -> display: grid
#  -> grid-template-columns: 60px
#  -> grid-template-columns: 60px 100px
#  -> grid-template-columns: 60px 100px auto
#  -> grid-template-columns: 60px 100px auto	//ubah ke persen jika ingin relative
#  -> grid-template-rows: 60px 100px auto
#  -> gap: 10px 0px				//jarak antar grid
#  -> grid-columns-start: 1
#  -> grid-columns-end: 3
#- Responsive Layout Grid View
#- Responsive Layout Media Queries
#  @media only screen and(max-width:600px){
#	body{ background-color: blue}
#	[class*="col-"]{ width: 100% }
#  }
#
#
#Cara mengambil semua class col- menjad 1 selector:
#  [class*="col-"]{ float: left }
#
#
#Ada beberapa properties dari justify-content:
#- justify-content: space-evenly		(space kiri kanan sama)
#- justify-content: space-between	(space diantara elemen sama panjang)
#- justify-content: space-around		(kiri kanan sama, yg tenganya mengikuti)
#
#
#
#
#
#
#
#
#Bootstrap
#
#
#Instalasi bootstrap
#-tambahkan link cdn bs di head html
#-tambahkan beberapa sdcript dari bs di body html
#
