# merge_sort

[16,21,11,8,12,22] -> Merge Sort

1.Write the stages of the above array according to the sort type.
CEVAP:
[16,21,11]            |             [8,12,22]
[16,21] | [11]        |         [8,12]  | [22]
[16] | [21] | [11]    |         [8] | [12] | [22]
[16,21] | [11]        |         [8,12] | [22]
[11,16,21]            |         [8,12,22]
[8,11,12,16,21,22]
-------------------------------
2.Show the big o notation

n/2 + n/4 + ... + 1
2^x = logn
O(n*logn)
