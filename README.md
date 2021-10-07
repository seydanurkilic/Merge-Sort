# Merge-Sort

[16,21,11,8,12,22] #

Öncelikle ikiye ayıracağız. 

1.ayrım [16,21,11]     <br>                                               [8,12,22] <br>
     (bunu da 2'ye) 
[16,21] //   [11]                                                [8,12]    [22] <br>
(bunu da 2'ye)
                                                                [8]   [12]    [22](zaten tek kalmıştı)
[16]   [21]   [11](zaten tek kalmıştı)

- (şimdi sıralıyoruz küçükten büyüğe)

[11,16,21]                                                 [8,12,22]
- (en son ikisini sıralayarak birleştiriyoruz.)

[8,11,12,16,21,22]

- O(logn)


