# Proje 1: Selective Sort

* [22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

* [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
---
## [22,27,16,2,18,6]

Bu dizinin en küçük elemanı bulunur ve en baştaki ile yer değiştirilir. Daha sonra ikinci elemana geçilir.
En küçük eleman 2, 22 ile yerdeğiştirir. 

->[2,27,16,22,18,6]

Birinci eleman hariç diğer elemanlar arasında en küçük olan 6, 27 ile yer değiştirir.

->[2,6,16,22,18,27]

1. ve 2. eleman göz ardı edilir ve 3. elemana gelir sıra. 3. eleman en küçük olduğundan yer değiştirmesine gerek kalmaz

->[2,6,16,22,18,27]

Daha sonraki en küçük eleman 18 olduğundan 22 ile yer değişitirir.

->[2,6,16,18,22,27]

5. elemana gelir sıra. Zaten 5. ve 6. arasında en küçük 5. olduğundan dokunulmaz.

->[2,6,16,18,22,27]

En son elemana dokunulmaz ve dizinin son hali; [2,6,16,18,22,27] şeklindedir.


Big O notion => O(n^2)

Dizi sıralandıktan sonra 18 sayısı Average case e girer.

## [7,3,5,8,2,9,4,15,6]

1. Adım: 2 ile 7 yer değiştirir.
2. Adım: 3 yerinde kalır.
3. Adım: 4 ile 5 yer değiştirir.
4. Adım: 5 ile 8 yer değiştirir.
