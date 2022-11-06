# BINARY-SEARCH-TREE-PROJESIPatika.dev

Patika.dev

Patika.dev ve Kodluyoruz marmara üniversitesi yazılıma başlangıç eğitiminin üçüncü projesi

Proje 3

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız. Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
CEVAP= Algoritmada en üstte bulunan node'a root deriz. Bu dizide root'u 7'dir. Root değerinden daha küçük olan elemanlar ya da node'lar root sayısının yani 7 sayısının sol tarafında bulunacaklar. Root değerinden büyük olan node'lar ise root'ın sağ tarafında bulunacaklar.

Yukarıdaki dizinin aşamaları şöyledir;

1.AŞAMA= İlk değer olan 7'yi root seçmiştik. Burada hemen bir yanındaki 5 değeri root'tan küçük olduğu için sol tarafa yazılır.
                                   7
                                 /
                               5
2.AŞAMA= 3.sırada olan 1 sayısı 7'den küçük olduğunu görüyoruz. Daha sonrasında 5'den de küçük olduğu için hemen onu 5'in sol altına ekleyip, yazıyoruz.