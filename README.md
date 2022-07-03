# Insertion-Sort-Projesi
Patika.dev  Veri Yapıları ve Algoritmalar > Insertion Sort Projesi

Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## 1. Cevap

```

[22,27,16,2,18,6]

[2,27,16,22,18,6] -> 2 ile 22 yer değiştirir.
[2,6,16,22,18,27] -> 6 ile 27 yer değiştirir.
"[2,6,16,22,18,27] -> 3. sıradaki eleman en küçük. Dokunmadan devam et."
[2,6,16,18,22,27] -> 18 ile 22 yer değiştirir ve sonlanır.
"[2,6,16,18,22,27] -> 5. sıradaki eleman en küçük. Dokunmadan devam et."
[2,6,16,18,22,27] -> 6. sıradaki eleman en büyük ve bitir.
```

## 2. Cevap
```
O(n²) = O(6²) = O(36)

```
## 3. Cevap
```
Average case:2,
Worst case:16,18,
Best case: 27.
```
## 4. Cevap

```
Averge case
```
## 5. Cevap
```
[2,3,5,8,7,9,4,15,6] -> 7 ile 2 yer değiştirir.
[2,3,5,8,7,9,4,15,6] -> 2. sıradaki 3 rakamı en küçük, dokunmadan devam et.
[2,3,4,8,7,9,5,15,6] -> 5 ile 4 yer değiştirir.
[2,3,4,5,7,9,8,15,6] -> 8 ile 5 yer değiştirir.

```
