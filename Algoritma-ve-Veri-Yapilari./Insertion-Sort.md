## Proje 1

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


Answers:
1) [22,27,16,2,18,6] --> [22,27,16,2,18,6] --> [16,22,27,2,18,6] --> [2,16,22,27,18,6] --> [2,16,18,22,27,6] --> [2,6,16,18,22,27]

2) n elemanli listede karsilastirma yapmak icin ic ice iki dongu kullandigimizdan n*n islemden big o notation O(n^2) olur.

3) 
- Onceden siralanmis bir liste elimize gelirse inner loop asla calismayacagindan kod n tane islem yapar bu seneryomuz best case olur. Best case --> O(n)
- Avarage ve Worst Case icin O(n^2) gecerli. 

4) 18 elemani neredeyse sonda oldugundan worst case olarak degerlendirilebilir.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1) [3,7,5,8,2,9,4,15,6]
2) [3,5,7,8,2,9,4,15,6] 
3) [3,5,7,8,2,9,4,15,6]
4) [2,3,5,7,8,9,4,15,6]
