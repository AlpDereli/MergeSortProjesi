# MergeSortProjesi

## 1)
                                                     [16,21,11,8,12,22] 
                                               [16,21,11]        [8,12,22]
                                            [16,21]   [11]      [8,12]  [22]
                                          [16] [21]   [11]      [8] [12] [22]
                                          [16,21]   [11]        [8,12]  [22]
                                              [11,16,21]         [8,12,22]
                                                     [8,11,12,16,21,22]

## 2) 
Her kontrol için eleman sayısı-1 defa işlem yapılır (n-1). O işlemlerin BigO'su = O(n) olur. Bu işlem n defa olduğu için 2^x = n (log2(n) = x) olur.

Buradan da merge sortun BigO'sunu =  O(n*log2(n)) olarak buluruz.
