# \#Insertion Sort

## *Question 1*

#### [ 22, 27, 16, 2, 18, 6 ] diziyi insertion sort ile sırala ve adımlarını yazdır.

```
 22, 27, 16, 2, 18, 6   -   n

 16, 22, 27, 2, 18, 6   -   n-1

 2, 16, 22, 27, 18, 6   -   n-2

 2, 16, 18, 22 ,27 ,6   -   n-3

 2, 6, 16, 18, 22, 27   -   1
```

## *Question 2*

#### Big O Notation'ı nedir?
- *O(n2)*

## *Question 3*
#### 18 sayısı hangi case kapsamına girer? 

*Average Case : Aranan sayının ortada olması durumu*

*Worst Case : Aranan sayının sonda olması durumu*

*Best Case : Aranan sayının başta olması durumu*

- **Time Complexity** 
    - Average Case




## *Question 4*
#### [ 7, 3, 5, 8, 2, 9, 4, 15, 6 ] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

```
7, 3, 5, 8, 2, 9, 4, 15, 6   -   n

3, 7, 5, 8, 2, 9, 4, 15, 6   -   n-1

3, 5, 7, 8, 2, 9, 4, 15, 6   -   n-2

2, 3, 5, 7, 8, 9, 4, 15, 6   -   n-3

2, 3, 4, 5, 7, 8, 9, 15, 6   -   n-4

2, 3, 4, 5, 6, 7, 8, 9, 15   -   1
```
    


# \#Merge Sort
## *Question 1*
#### [ 16, 21, 11, 8, 12, 22 ] dizisini Merge Sort'a göre yazınız.

```
                            16, 21, 11, 8, 12, 22
                            /                   \
                        16 21 11              8 12 22
                       /        \           |       |
                    16 21        11        8 12      22
                   /      \       \         /  \      \
                 16        21      11      8    12    22
                   \     /        /         \  /      /
                    16 21       11         8 12     22
                       \       /               \   /
                        11 16 21              8 12 22
                            \                   /
                              8 11 12 16 21 22 
```


## *Question 2*

#### Big O Notation'ı nedir?
- *O(n\*log n)*



# \#Binary Search Tree

## *Question 1*
#### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.


```
                                  --5--
                                 /     \
                                3        7
                               / \      / \
                              1   4    6   9
                             / \          /   
                            0   2        8  

Steps:
    - Right
        - 5'in sağında 7 bulunur.
        - 7'nin sağında 9 bulunur.
        - 3'ün sağında 4 bulunur.
        - 1'in sağında 2 bulunur.

    - Left
        - 5'in solunda 3 bulunur.
        - 1'in solunda 0 bulunur.
        - 7'nin solunda 6 bulunur.
        - 9'un solunda 8 bulunur.
     
```


