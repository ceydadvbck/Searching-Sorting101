# Searching-Sorting101

Practising Data Structures and Algorithms. Thank you Patika.dev for providing understandable free Turkish courses with excellent teachers. 
The tutorial I follow :https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar

Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
[22,27,16,2,18,6] 22 ile 2 nin yeri değiştirilir.
[2,27,16,22,18,6] 27 ile 6 nın yeri değiştirilir.
[2,6,16,22,18,27] 16 zaten kalanların arasında en küçük olduğu için yeri değiştirilmez.
[2,6,16,22,18,27] 22 ile 18 in yeri değiştirilir.
[2,6,16,18,22,27] Dizimiz Insertion Sort'a uygun olarak sıralandı. 

2. Big-O gösterimini yazınız. 
O(n^2)

3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Average Case : O(n^2)
Worst Case: O(n^2)
Best Case : O(n)

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Dizinin ortasında kaldığı için Avarage Case Kapsamına girer

5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
[7,3,5,8,2,9,4,15,6] 7 ile 2 yer değiştirir.
[2,3,5,8,7,9,4,15,6] 3 olduğu yerde kalır.
[2,3,5,8,7,9,4,15,6] 5 ile 4 yer değiştirir.
[2,3,4,8,7,9,5,15,6] 5 ile 8 yer değiştirir.


