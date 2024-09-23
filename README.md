# kodluyoruzfrontend

En Çok Kullanılan Etiketler
<html> -> Her şeyi kapsar.
<head> -> Görünmeyen kodlar.
<body> -> Sayfanın içeriğinin olduğu kısım.
<Title> -> Sekme kısmında yazacak isim.
<meta> -> Sayfanın belli özelliklerini yazmaya yarar.
<h> -> Başlık,h1,h2,h3,h4.
<p> -> Paragraf.
<Strong> / <B> ->  kalın yazar.
<script> -> javascript kodlarını yazmamızı sağlar.
<img> -> resim eklemek için kullanılır.
<iframe> -> Belge içinde belge göstermeye yarar.
<!-- --> -> Yorum Satırı   
Control Ö seçilen satırı yorum satırı yapar.
<Style> -> Etiketi satır içerisinde özellik eklmemize yarar.
<link> -> Başka sayfalardan dökümanları sayfamıza eklememize yarar.
<ol type="I"> -> Sıralı Listeleme.
<ul> -> Sırasız Listemele.
<li> -> Liste elemanı.
<a> -> Yönlendirme(link).
<!DOCTYPE html> -> HTML5 icin gerekir.


**************************************************

ÖRNEK GÖRSEL KULLANIMI
<img src=resim.jpg width="300"> 
Not: Bunu link şeklinde yazabiliriz de. Javascript ile alert şeklinde de
yazılabilir. Border,align,width,height gibi özellikler eklenebilir.


**************************************************

ÖRNEK LİNK KULLANIMI
<a href="mailto:info@kodluyoruz.org"> Kodluyoruz'a mail atınız. </a>
<a href="#sonbolum">Sayfa Sonu</a> Aynı sayfa içinde bir yere gitmemizi sağlar. 


**************************************************

Not: Blok ve Inline elementler vardır. Bazı etiketler tüm satırı kaplarken bazıları 
inlinedır sadece oldugu kadarını kaplar.


**************************************************

ID VE CLASS
Id uniquetir. Sadece bir tane olur. # işareti ile de css dosyasında özelliklerini girebiliriz. Id isimlendirmelerinde boşluk olamaz.Tire
veya camelcase ile yazılır. data-id veya data-section gibi farklı kullanımları da vardır. Daha iyi organize etmek için kullanılır.

Class birden fazla olabilir. '.' İşareti ile özelliklerini gireriz.
İsimlendirilmelerinde boşluk olabilir. 


**************************************************

SEMANTİC WEB ETİKETLERİ
Header,nav,section,article,footer.



************************************************

CSS İÇİN ÖNEMLİ BİLGİ

Inline --> satır içinde yazılan style özelliğidir. 
Internal ---> Head içinde yazılan style özelliğidir.
External ---> css dosyası içinde yazılan style özelliğidir. 

Inline > Internal > External (Ezme sırası)


display: none;
/* Elemanı sayfadan tamamen kaldırır */

display: block;
/* Elemente blok seviyesi elementlerin (<div>, <header>, <h1> gibi) görünüm özelliğini kazandırır. */

display: inline;
/* Elemente <span>, <a>, <img> elementlerinde olduğu gibi, satır içi yerleşim özelliği kazandırır. Element satırı tamamen kaplamaz, içeriği kadar yer kaplar. */

display: inline-block;
/* Elementleri satır içi element gibi yan yana dizmek için kullanılır. */

display: flex;
/* Element inline element gibi davranır ve bunun yanında flexbox modeline uygun görünüme sahip olur. */

display: grid;
/* Element, blok level bir element gibi davranır ve grid model görünümüne uygun davranır. */
