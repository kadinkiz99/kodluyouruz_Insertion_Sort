# kodluyouruz_Insertion_Sort
Patikadev Insertion Sort ödevi için hazırlanmıştır.

[22,27,16,2,18,6] 

1) Yukarıda verilen dizinin Sort türüne göre aşamaları.
 ```
 - Dizinin ilk elemanı ile diğer elemanlarını karşılaştır . 
 - Daha küçük bir eleman var ise yer değiştir. 
 - 22 elemanından küçük 2 elemanı var 2 ve 22 nin yerlerini değiştir. 
   Son Hali : [2,27,16,22,18,6] 
 - Daha sonra diğer eleman olan 27 ve diğer elemanları karşılaştır. 
 - 27 elemanından küçük olan 6 bulundu 6 ve 27 nin yerlerini değiştir. 
   Son Hali : [2,6,16,22,18,27] 
 - Bir sonraki eleman olan 16 ile diğer elemanları karşılaştır. 
 - 16 dan daha küçük eleman olmadığı için sıralamada değişiklik yapılmaz. 
 - Bir sonraki eleman olan 22 ile kalan elemanları karşılaştır. 
 - 22 den daha küçük 18 elemanı var , yerlerini değiştir . 
  Son Hali:  [2,6,16,18,22,27] 
 - Bir sonraki eleman olan 22 ve 27 sıralı olarak bulunduğundan işlem yapılmaz. 
 - Ve artık dizi sıralanmış olarak hazırdır :) 
 
 ```

2) Big-O gösterimini yazınız.
```
O (n^2)
```
Time Complexity:
Average case: Aradığımız sayının ortada olması,
Worst case: Aradığımız sayının sonda olması, 
Best case: Aradığımız sayının dizinin en başında olması.

3) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
```
[2,6,16,18,22,27]  dizini son haline göre Average case dir 

```
4) [7,3,5,8,2,9,4,15,6] dizisinin Insertion sort'a göre ilk 4 adımını yazınız.

```
    =>   [7,3,5,8,2,9,4,15,6] 
      
     1) [2,3,5,8,7,9,4,15,6]
     2) [2,3,4,8,7,9,5,15,6]
     3) [2,3,4,8,7,9,5,15,6]
     4) [2,3,4,5,7,9,8,15,6]
     5) [2,3,4,5,6,9,8,15,7]
     6) [2,3,4,5,6,7,8,15,9]
     7) [2,3,4,5,6,7,8,15,9]
     8) [2,3,4,5,6,7,8,9,15]

```



