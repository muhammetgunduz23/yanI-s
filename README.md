# BINARY-SEARCH-TREE-PROJESIPatika.dev

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
                                                               7
                               /
                              5
                            /
                           1
3.AŞAMA= 4.sırada olan 8 sayısı 7'den büyük olduğu için onu root'ın sağ tarafına ekliyoruz.
                                 7
                               /   \
                              5     8
                            /
                           1
4.AŞAMA= 5.sırada olan 3 sayısı 7 ve 5'ten küçüktür ancak 1'den büyüktür bu yüzden 1 sayısının hemen sağ tarafına ekliyoruz.
                                 7
                               /   \
                              5     8
                            /
                           1
                             \
                               3
5.AŞAMA= Dizide 6.sırada olan 6 sayısı 7'den büyüktür ancak 5'ten büyük olduğu için hemen 5'in sağına ekliyoruz.
                                 7
                               /   \
                              5     8
                            /   \
                           1      6
                             \
                               3 
6.AŞAMA= 0 sayısı 7,5 ve 1 sayılarından küçüktür. Bu yüzden 1'in soluna ekliyoruz.
                                 7
                               /   \
                              5     8
                            /   \
                           1      6
                         /   \
                        0     3
7.AŞAMA= 9 değeri 7 ve 8 sayılarından büyüktür. Bu yüzden direkt 8 sağına yazarız.
                                 7
                               /   \
                              5     8
                            /   \     \
                           1      6     9
                         /   \
                        0     3
8.AŞAMA= 4 sayısına baktığımızda 7 ve 5 sayılarından küçük olduğunu görürüz ancak 1 ve 3 sayısından büyüktür. Bu sebeple 3'ün hemen sağına ekleriz.
                                 7
                               /   \
                              5     8
                            /   \     \
                           1      6     9
                         /   \
                        0     3
                                \
                                  4
9.AŞAMA= 2 sayısı 7 ve 5 sayılarından küçüktür. 1 sayısından büyük olmasına rağmen 3 sayısından küçüktür. Bu yüzden 3 sayısının hemen soluna yazabiliriz.
                                 7
                               /   \
                              5     8
                            /   \     \
                           1      6     9
                         /   \
                        0     3
                            /   \
                           2     4
Böylelikle binary search tree tamamlanmış olur.
