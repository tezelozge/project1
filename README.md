# project1
[22,27,16,2,18,6] ---> Insertion Sort

[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,22,18,27]
[2,6,16,18,22,27]
[2,6,16,18,22,27]

Array içerisindeki eleman sayısı n=6 ve her işlem sayısı n-1 ile başlayıp birer azalarak devam ettiği için;
O(n^2) ---> n=6 ; O(6^2)=O(36)

Worst case: Aradığımız sayının sonda olması
Average case: Aradığımız sayının ortada olması
Best case: Aradığımız sayının dizinin en başında olması

[7,3,5,8,2,9,4,15,6]

[2,3,5,8,7,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
