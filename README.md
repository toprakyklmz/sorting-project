# Sorting-Project

### İnsertion sort :

Dizi : [22,27,16,2,18,6]

1.soru Aşamalar :  [2,27,16,22,18,6] (n), [2,6,16,22,18,27](n-1) , [2,6,16,18,27] (n-2)

2.soru Big-O notation : Elemanlar tek tek gezilir ve her eleman sıralandığında sıralanacaklar bir azalır eğer buna toplam formülü
uygularsak sonuç aşağıdaki gibi olur.
n + n-1 +n-2 + ....+1 = n*(n-1)/2
O(n) = n^2

3.soru Best case’de aradığımız sayı = 2 ve Big-O notation O(n) , Avarage case’de aradığımız sayı = 16 ve Big-O notation O(n^2) ,
Worst case’de aradığımız sayı = 27 ve Big-O notation O(n^2)

4.soru Sıralanmış dizi : [ 2,6,16,18,27] 18 sayısı avarage case kapsamına girer .

5. Soru [7,3,5,8,2,9,4,15,6] ilk 4 aşama aşağıda verilmiştir.

1) [2,3,5,8,7,9,15,6]   2) [2,3,5,6,7,9,15,8]  3) [2,3,5,6,7,8,15,9]  4) [2,3,4,5,6,7,8,9,15]
