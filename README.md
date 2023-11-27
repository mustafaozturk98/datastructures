# datastructures
# soru 1 

    [22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

# aşamalar
>[22,27,16,2,18,6] <br>
>[2,27,16,22,18,6] 2 başa geldi<br>
>[2,6,16,22,18,27] 6 ile 27 değişti<br>
>[2,6,16,18,22,27] 22 ile 18 değişti <br>

> big O notation O(n^2) <br>
> 18 average case kapsamındadır 

### [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

>[7,3,5,8,2,9,4,15,6] max 15 min 2  <br>
>[2,3,5,8,7,9,4,15,6] min element başa geldi <br>
>[2,3,5,8,7,9,4,15,6] min 3 olduğu için aynu kaldı<br>
>[2,3,4,8,7,9,5,15,6] min 4 değişti <br>
>[2,3,4,5,7,9,8,15,6] min 5 depişti <br>

# soru 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

>[16,21,11] [8,12,22] <br>
>[16] [21,11] [8] [12,22]<br>
>[16] [21] [11] [8] [12] [22]<br>
>[16] [11,21] [8] [12,22]<br>
>[11,16,21] [8,12,22]<br>
>[8,11,12,16,21,22]<br>

Big- O gösterni O(nlogn)

# soru 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.



Root x = 6
<br>
>                            6  
>                         /   \ 
>                         5    7 
>                      /        \ 
>                    1           8 
>                 /   \           \ 
>               0     3             9 
>                  /   \       
>                2     4       
                                
>Step 1:     7 > 6 için root'un sağında 7 bulunur.<br>
>Step 2:     5 < 6 için root'un solunda 5 bulunur.<br>
>Step 3:     1 < 6 için 1 root'un soluna eklenir.<br>
>Step 4:     8 > 6 için 8 root'un sağına eklenir.<br>
>Step 5:     3 < 6 için 3 root'un soluna eklenir.<br>
>Step 6:     0 < 6 için 0 root'un soluna eklenir.<br>
>Step 7:     9 > 6 için 9 root'un sağına eklenir.<br>
>Step 8:     4 < 6 için 4 root'un soluna eklenir.    <br>                    
>Step 9:     2 < 6 için 2 root'un soluna eklenir.      <br>         

