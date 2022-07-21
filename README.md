# patica_project_1_insertion_sorting_project
[22,27,16,2,18,6] 0. index ten başlayarak tarama yapar. en küçük değerin 2 olduğunu belirleyince 2 başa alır ve 22 ile yer değiştirir.

[2,27,16,22,18,6] 1. index ten başlayarak tarama yapar. en küçük değerin 6 olduğunu belirleyince 6 1. indexe taşınır ve 27 6 ile yer değiştirir.

[2,6,16,22,18,27] 2. index ten başlayarak tarama yapar. en küçük değerin 16 olduğunu belirleyince değişiklik yapmadan aynen bırakır

[2,6,16,22,18,27] 3. index ten başlayarak tarama yapar. en küçük değerin 18 olduğunu belirleyince 18 3. indexe taşınır ve 22 18 ile yer değiştirir.

[2,6,16,18,22,27] 4. index ten başlayarak tarama yapar. en küçük değerin 22 olduğunu belirleyince değişiklik yapmadan aynen bırakır

[2,6,16,18,22,27]

# Big-O
n + (n-1) + (n-2) + ... + 1

1 den n e kadar sayıların toplamı = (n * (n + 1))/2

= (n^2 + n)/2

Dominant notation O(n^2)

# Time Complexity
Arama yapılan sayı dendiğine göre, sorting işlemi yapıldıktan sonra searching yapıldığı görülüyor. Bu durumda searching algoritmasının belirtilmesi gerekir.

linear searching kullanılırsa time complexity O(n) olur. Aranan ifadenin başta, ortada veya sonda olması durumu katsayı olarak geldiğinden time complexity içinde gösterilmez. Ancak süreyi etkiler.

[patika.dev](https://www.patika.dev/tr)

# Sıralandıktan sonra 18 sayısı 
Average case durumuna girer.

# [7,3,5,8,2,9,4,15,6]
[2,3,5,8,7,9,4,15,6] 1. Adım

[2,3,5,8,7,9,4,15,6] 2. Adım

[2,3,4,8,7,9,5,15,6] 3. Adım

[2,3,4,5,7,9,8,15,6] 4. Adım


