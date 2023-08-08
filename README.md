#<i> belajar css di vscode </i># 

<br>

## duplicate baris : Alt + Shift + Menurun

## membuat tag sekaligus : p*3 

## membuat tag sekaligus tulisan : p{tulisan}
## jika digabung : p*3{tulisan}

## membuat nomor berurutan : {$} 
## contoh : p*3{tulisan $}
## note : 
	p : tag
	*3 : jumlah
	{tulisan} : isi
	{$} : Satuan
	{$$} : Puluhan


## ul (unordered list) list tidak  terurut
## li (list item) isi 
## ol (ordered list) list terurut

## bikin link : a enter

## membuat list sekaligus :    ul>li*5>a{Link $}

## memberikan warna di text : berikan tag <font color="merah"> merah </font> 

## memperbesar font di html : size="20"


## contoh css internal : 
 <style>
        h1{
            color: aqua;
        }
  </style>


## contoh css inline :
<h1 style="color: salmon; font-family: arial;">Contoh</h1>


## penjelasan css internal
     Tag Pembuka ---> <style>
       	Selector --->   h1{
   	Properti --->     color: aqua; <--- Value
    Gaya Tulisan --->	  font-family: arial;
  Ukuran Tulisan --->	  font-size: 50px ;
			   }
     Tag Penutup ---> </style>

## manual komentar code : /*
## shortcut komentar/nonaktifkan code : ctrl + /


## saat menggunakan selector id kita meberikan tanda #(pagar) di style css
## saat menggunakan selector class kita memberikan tanda .(titik) di style css
## cara mewarnai tulisan menggunakan selector style, contoh : <p style="color: blue;">Contoh</p>

Note : 
	class : bisa digunakan berulang-ulang
	id : hanya sekali digunakan (rekomendasi) gunakan id saat menggunakan javascript

## membuat tulisan miring di css (jangan lupa berikan class di html) : font-style: italic;
## membuat tulisan besar/kapital di css (jangan lupa berikan class di html) : text-transform: uppercase;
## membuat tulisan kecil di css (jangan lupa berikan class di html) : text-transform: lowercase;
## membuat tulisan tebal di css (jangan lupa berikan class di html) : font-weight: bold;


## menggabung tag html dan selector tambahan untuk menentukan warna didalam tag yg sama,cara nya tambahkan element yang di butuhkan di akhir selector css
contoh : 

	h1 {
	  color: blue;
	   }

	.judul1 h1 {
            color: cadetblue;
        	   }

	.judul2 h1 {
            color: cadetblue;
        	   }

	<h1 class="judul1">Judul 1</h1>
	<h1 class="judul2">Judul 2</h1>



## memberikan warna di link : buat dan berikan warna untuk tag <a>

## memberikan warna yang berbeda di tag a di luar listnya : berikan li pada selector a di css

Note :
	kalau selector menggunakan spasi artinya didalam (bacanya dari kanan)
	kalau selector menggunakan titik artinya memiliki (memiliki class)

contoh : h3 .paragraft2 {
		     color: red;
		        }

	dibacanya : carikan saya element apapun yang punya class paragraft2 yang berada di dalam h3

contoh : h3.paragraft2 {
		     color: red;
		       }

	dibacanya : carikan saya element H3 yang punya class paragraft2


contoh : ul li a {
		color: red;
		 }

	dibacanya : cariin a yang ada di dalam li dan yang ada di dalam ul (kebalikan)

Note : 
	ul : list titik
	ol : list nomor

## membuat warna terpisah dalam 1 kalimat (menggunakan span)
	contoh : <h3 class="judul2">Candra <span class="paragraft4">Kirana</span></h3>


Note :
	<p> : paragraft
	<h> : heading
	
	Apa itu DIV dan SPAN? (tag yang tidak mempunyai nilai)
		Element div (block) digunakan sebagai "divider" atau pemisah. Div banyak digunakan untuk mengelompokan sekumpulan element. 
		Sedangkan span digunakan sebagai container untuk inline element.
