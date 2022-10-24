 [Patika.dev](https://www.patika.dev/tr) 

 # -Merge Sort prj-

 [16,21,11,8,12,22]

 ## 1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

 ```
 {divide}
 
 1-)  [16,21,11][8,12,22]

 2-)  [16,21] [11]  [8,12] [22]
 
 3-)  [16] [21] [11] [8] [12] [22]
 
 {divide}
 
 {conquer}

4-) [16,21] [8,11] [12,22]

5-) [8,16,21]  [11,12,22 ]

6-) [ 8,11,12,16,21,22 ]
 
 {conquer}


 ```

 ## 2. Big-O gösterimini yazınız.
 


 ```
Average case : O(n*logn)

Worst case   : O(n*logn)

Best case    : O(n*logn)

6 elemanlı: O(6log6)

 ```