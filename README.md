Selection-Sort-Projesi


[22,27,16,2,18,6] Insertion Sort
[22,27,16,2,18,6] ->[2,27,16,22,18,6]-> [2,27,16,22,18,6] ->[2,6,16,22,18,27]-> *[2,6,16,22,18,27] ->[2,6,16,22,18,27]-> 
[2,6,16,22,18,27] ->[2,6,16,18,22,27]-> [2,6,16,18,22,27] ->[2,6,16,18,22,27]

2- Big-0 Gösterimi 0(n^2)
Son dizide '[2,6,16,18,22,27]' 18 ortada olduğundan dolayı Average Case'dir.

3- Selection Sort [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre;
[7,3,5,8,2,9,4,15,6] ->[2,3,5,8,7,9,4,15,6]-> 2 ve 7 yer değiştirir [2,3,5,8,7,9,4,15,6] ->[2,3,4,8,7,9,5,15,6]-> 4 ve 5 yer değiştirir. [2,3,4,8,7,9,5,15,6] ->[2,3,4,5,6,9,8,15,7]--> 8 ve 5 yer değiştirir. [2,3,4,5,6,9,8,15,7] ->[2,3,4,5,6,7,8,15,9]-> 7 ve 9 yer değiştirir. [2,3,4,5,6,7,8,15,9] ->[2,3,4,5,6,7,8,9,15]--> 9 ve 15 yer değiştirir.
