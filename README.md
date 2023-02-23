# Insertion-Sort
Patika.dev Insertion Sort Projesi

[22,27,16,2,18,6] -> Insertion Sort  Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması 
Best case: Aradığımız sayının dizinin en başında olması.    

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Cevaplar

1- 
Sıralanmış dizi = [2,6,16,18,22,27]
Önce ilk arrayin ilk indexi için tüm diziyi arayacak ve ilk indexteki sayıdan küçük mü diye her biriyle karşılaştıracak dizinin sonuna geldiğinde en küçük olan sayıyı başa atıyacaktır. Ardından her bir array indexi için bu işlemi gerçekleştirecektir. Big O gösterimi : O(n^2)
18 sayısını average case kapsamında değerlendirilebilir, açıklaması ise 4. indexi incelerken  2,6 ve 16 çoktan sıralanmış olduğundan sadece 22,18 ve 27 sayıları arasından index için karşılaitırma yapıalcaktır, 18 sayısı bu dizinin ortasında bulunmaktadır.

2-
[7,3,5,8,2,9,4,15,6]
min=7
is 2<7 ? yes
min=2
[2,3,5,8,7,9,4,15,6]
min=3
is 6<3? no
[2,3,5,8,7,9,4,15,6]
min=5
is 4<5 ? yes
[2,3,4,8,7,9,5,15,6]
min=8
is 5<8? yes
[2,3,4,5,7,9,8,15,6]









