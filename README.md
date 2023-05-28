# data_structure_algorithms
Data Structures and Algorithms

---
# PROJECT - 1
<br>
[22,27,16,2,18,6] -> Insertion Sort
<br>
## Selection Sort
<br>
[22,27,16,2,18,6]
<br>
En küçük değeri en başa koyar --> (n)
<br>
[2,22,27,16,18,6] --> (n-1)
<br>
En baştaki hariç bu sefer diğerlerine bakar
<br>
[2,6,22,27,16,18]
<br>
Bu sefer de en baştaki 2 değer hariç diğer kalanlar arasından en küçüğe bakar --> (n-2)
<br>
[2,6,16,22,27,18]
<br>
Bu sefer de en baştaki 3 değer hariç diğer kalanlar arasından en küçüğe bakar --> (n-3)
<br>
[2,6,16,18,22,27]
<br>
Bu sefer de en baştaki 4 değer hariç diğer kalanlar arasından en küçüğe bakar --> (n-4)
<br>
[2,6,16,18,22,27]
<br>
Listemiz sıralanmış oldu.
<br>
***Big-O notation ise O(n^2)' dir. 18 average case kapsamına girer.***
<br>
---
<br>
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
<br>
1.[2,7,3,5,8,9,4,15,6]
<br>
2.[2,3,7,5,8,9,4,15,6]
<br>
3.[2,3,4,7,5,8,9,15,6]
<br>
4.[2,3,4,5,7,8,9,15,6]
<br>

---
# PROJECT - 2
---
<br>
[16,21,11,8,12,22] -> Merge Sort
<br>
Öncelikle diziyi ikiye ayıyoruz
<br>
[16,21,11] -- [8,12,22]
<br>
Bir daha ayırıyoruz
<br>
[16] [21,11] -- [8] [12,22]
<br>
Bir daha parçalıyoruz
<br>
[16] [21] [11] -- [8] [12] [22]
<br>
[16] [11,21] -- [8] [12,22]
<br>
[11,16,21] -- [8.12.22]
<br>
[8,11,12,16,21,22]
<br>
***Time complexity -- O(logn)' dir.***
---
# PROJECT - 3
---
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
<br>
Root x = 3
<br>
Sağında büyükler solunda küçükler yer alır
<br>
Sağındakiler - 7,5,8,6,7,4
Solundakiler - 1,0,2


