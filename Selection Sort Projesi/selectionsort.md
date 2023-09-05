# Proje 1
## [22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
## Aşamalar
* dizide en küçük eleman bulunur.
* ilk sıradaki eleman ile yer değiştirilir.
* ilk eleman hariç diğer elemanlardan en küçüğü bulunur.
* ikinci eleman ile yer değiştirilir.
* ...
## Big-O gösterimini yazınız.
n + n-1 + n-2 + n-3 + n-4 + n-5 = n.(n+1) / 2 = O(n^2)
## Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
average case
## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
[7,3,5,8,2,9,4,15,6] [2,3,5,8,7,9,4,15,6] [2,3,4,8,7,9,5,15,6] [2,3,4,5,7,9,8,15,6]