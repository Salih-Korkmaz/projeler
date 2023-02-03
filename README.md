# Projeler

1.Soru:[22,27,16,2,18,6] Dizisinin Short aşamalarını yazınız.
En küçük eleman bulunur ve dizide sıralanarak yerleri değiştirilir.

Cevap:
[22,27,16,2,18,6](n)
[2,27,16,22,18,6](n-1)
[2,6,16,22,18,27](n-2)
[2,6,16,18,22,27](n-3)

2.Soru: Big-O gösterimini yazınız.

Cevap:[n(n+1)/2=> (n^2+n)/2 den Big O Notation: O(n^2)

3. Soru Time Complexity -> Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
Dizi Sıralandıktan sonra diziye bakıldığında aranan 18 elamanı ortada olduğu için Average Case kapsamına girer.

Selection Sort
Soru: [7,3,5,8,2,9,4,15,6] Dizisinin Selection Sort'a göre ilk 4 adımı?

Cevap: 
 1-> [2,3,5,8,7,9,4,15,6]
 2-> [2,3,4,8,7,9,5,15,6]
 3-> [2,3,4,5,7,9,8,15,6]
 4-> [2,3,4,5,6,9,8,15,7]

 Binary Search Tree
 
 1. 
 [7,5,1,8,3,6,0,9,4,2] dizisinin Binary - Search - Tree aşamalarını yazın.
 
  Örnek: Root X'dir. Root'un sağında y bulunur. Solunda z bulunur vb bilgiler
  
                       5 => Root noktası
                     3      7
                    2  4 6 8 
                   1         9
                  0
                  
 - 5 ten büyük olan 7 sayısı sağ tarafa 3 sayısı ise küçük olduğundan sol tarafa yazılır.
 - 3 noktasında ise 4 sayısı büyük olduğu için sağ 2 sayısı küçük olduğu için sol kısma yazılır.
 - 7 noktasında ise 6 sayısı küçük olduğu için sol kısma 8 sayısı büyük olduğu için sağ kısma yazılır.
 - Diğer sayısal veriler bu şekilde devam etmektedir.
       
       
       
       
       
       
       
      
      
      
      
 
 
