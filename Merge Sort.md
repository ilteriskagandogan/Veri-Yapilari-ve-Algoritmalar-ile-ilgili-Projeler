# Proje 2: Merge Sort

* [16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

## CEVAP

1.Adım: 6 elemandan dolayı 3 elemanlı olmak üzere 2 ye bölüyoruz. 
[16,21,11][8,12,22]

2.Adım: 3 lü grupları tekrar bölüyoruz. 
[16,21][11][8,12][22]

3.Adım: 2 li grupları 1 eleman olacak şekilde bölüyoruz. 
[16][21][11][8][12][22]

4.Adım: Birleştirme işlemini aynı sayılar ile başlıyoruz ama küçük olan solda olacak şekilde.
[16,21][11][8,12][22]

5.Adım: 3 lü gruplar oluşturuyoruz.
[11,16,21][8,12,22]

6.Adım: ilk haline çeviriyoruz fakat en küçükten en büyüğe doğru sıralanmış oldu.
[8,11,12,16,21,22]


Big O notion => O(nlogn)
