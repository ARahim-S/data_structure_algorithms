# data_structure_algorithms
Data Structures and Algorithms

---
# PROJECT - 1 
[22,27,16,2,18,6] -> Insertion Sort

## Selection Sort
[22,27,16,2,18,6]
En küçük değeri en başa koyar --> (n)
[2,22,27,16,18,6] --> (n-1)
En baştaki hariç bu sefer diğerlerine bakar
[2,6,22,27,16,18]
Bu sefer de en baştaki 2 değer hariç diğer kalanlar arasından en küçüğe bakar --> (n-2)
[2,6,16,22,27,18]
Bu sefer de en baştaki 3 değer hariç diğer kalanlar arasından en küçüğe bakar --> (n-3)
[2,6,16,18,22,27]
Bu sefer de en baştaki 4 değer hariç diğer kalanlar arasından en küçüğe bakar --> (n-4)
[2,6,16,18,22,27]
Listemiz sıralanmış oldu.
***Big-O notation ise O(n)' dir. 18 average case kapsamına girer.***
---
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
1.[2,7,3,5,8,9,4,15,6]
2.[2,3,7,5,8,9,4,15,6]
3.[2,3,4,7,5,8,9,15,6]
4.[2,3,4,5,7,8,9,15,6]


