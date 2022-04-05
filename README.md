# Insertion-sort

Kodluyoruz Front-End Eğitimi kapsamında yapmış olduğum Insertion Sort projesi.

www.patika.dev

Proje 1

1. [22,27,16,2,18,6] -> Insertion Sort

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

  [2, 27, 16, 22, 18, 6] <br>
  [2, 6, 16, 22, 18, 27] <br>
  [2, 6, 16, 18, 22, 27] <br>

- Big-O gösterimini yazınız.

  Big-O = n+(n-1)+(n-2)+...+1 <br>
  = n\*((n+1)/2) <br>
  = n^2+n/2 <br>
  = n^2 <br>

- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

  Average case kapsamına girer çünkü 18 sayısı ortaya daha yakındır.

2. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[2, 3, 5, 8, 7, 9, 4, 15, 6] <br>
[2, 3, 4, 8, 7, 9, 5, 15, 6] <br>
[2, 3, 4, 5, 7, 9, 8, 15, 6] <br>
[2, 3, 4, 5, 6, 9, 8, 15, 7] <br>
