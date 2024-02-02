#Selection Sort Projesi
```
Soru: [22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

```
**Insertion Sort** [22,27,16,2,18,6]
```
Step  1: [22,16,27,2,18,6]
Step  2: [16,22,27,2,18,6]
Step  3: [16,22,2,27,18,6]
Step  4: [16,2,22,27,18,6]
Step  5: [2,16,22,18,27,6]
Step  6: [2,16,18,22,27,6]
Step  7: [2,16,18,22,6,27]
Step  8: [2,16,18,6,22,27]
Step  9: [2,16,6,18,22,27]
Step 10: [2,6,16,18,22,27]
```

**BigO:**  ```O(n^2)```

**Case:** ```Average Case```

**Selection Sort** [7,3,5,8,2,9,4,15,6]
```
Step  1: [2,3,5,8,7,9,4,15,6]
Step  2: [2,3,4,8,7,9,5,15,6]
Step  3: [2,3,4,5,7,9,8,15,6]
Step  4: [2,3,4,5,6,9,8,15,7]
```
