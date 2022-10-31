# Veri Yapıları ve Algoritmalar - Proje 1
https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/insertion-sort-proje
https://app.patika.dev/orhantr

[22,27,16,2,18,6]

1 - Sort Türüne Göre Aşamaları

    [2|,27,16,22,18,6]
    [2,6|,16,22,18,27]
    [2,6,16|,22,18,27]
    [2,6,16,18|,22,27]
    [2,6,16,18,22,27]


2 - Big-O gösterimi O(n^2)
3 - Time Complexity 

Avarage Case:[2,6,16,18,22,27]
Worst Case:[27,22,18,16,6,2] 
Best Case: [2,6,16,18,22,27]

4 - Dizi Sıralandıktan sonra avarage case sınıfına girer çünkü 18 sayısı ortalardadır.

[2,6,16,|18|,22,27]

5 - [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı:

    [2|,3,5,8,7,9,4,15,6]
    [2,3|,5,8,7,9,4,15,6]
    [2,3,4|,8,7,9,5,15,6]
    [2,3,4,5|,7,9,8,15,6]
    
