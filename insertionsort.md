# Insertion Sort Projesi

[22,27,16,2,18,6] -> İnsertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2.Big-O gösterimini yazınız.

3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

5.[7,3,5,8,2,9,4,15,6] dizisinin Insertion sort'a göre ilk 4 adımını yazınız.

## Solution 1

1. [2,27,16,22,18,6]
2. [2,6,16,22,18,27]
3. [2,6,16,18,22,27]

## Solution 2

n + (n-1) + (n-2) + (n-3) + ... + 1 = n(n+1) / 2 
Big O Notation *O(n^2)*

## Solution 3

Best Case = 1  
Average Case = n/2  
Worst Case = n  

## Solution 4

18 sayısı 3. iterasyonda sıralanmıştır.  
Average case = 3  
18 average case'e girer.  

## Solution 5

[7,3,5,8,2,9,4,15,6]

1. [2,3,5,8,7,9,4,15,6]
2. [2,3,4,8,7,9,5,15,6]
3. [2,3,4,5,7,9,8,15,6]
4. [2,3,4,5,6,9,8,15,7]


