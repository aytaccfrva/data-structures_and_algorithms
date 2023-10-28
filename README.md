# Data Structures and Algorithms 

## Project 1 (Selection Sort Project)

### Question 1:

[22,27,16,2,18,6] -> Insertion Sort

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.

### Answer:

[22,27,16,2,18,6]

[2,27,16,22,18,6]

[2,27,16,22,18,6]

[2,6,16,22,18,27]

[2,6,16,18,22,27]

- Big-O notation: O(n^2)

### Question 2:

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

1.Average case: Aradığımız sayının ortada olması

2.Worst case: Aradığımız sayının sonda olması

3.Best case: Aradığımız sayının dizinin en başında olması.


### Answer:

Average Case. Because 18 is the 3rd element of the array.

### Question 3:

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

### Answer:

[2,3,5,8,7,9,4,15,6]

[2,3,5,8,7,9,4,15,6]

[2,3,4,8,7,9,5,15,6]

[2,3,4,5,7,9,8,15,6]


## Project 2 (Merge Sort Project)

[16,21,11,8,12,22] -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

- Big-O gösterimini yazınız.

### Answer:

![merge-sort](/assets/merge.png)

Big-O notation: O(nlogn)

## Project 3 (Binary Search Tree Project)

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

### Answer:

root=6

           6
          / \
        5     7
       /       \
      1         8
     / \         \
    0   3         9
       / \
      2   4


