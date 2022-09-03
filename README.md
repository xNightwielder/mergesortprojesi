# Proje 2
[16,21,11,8,12,22] -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.

# Soru 1

- [16,21,11]    |    [8,12,22]
- [16,21] [11]    |    [8] [12,22]
- [16] [21]   [11]    |    [8]   [12] [22] 
- [16,21]   [11]    |    [8]   [12,22]
- [11,16,21]    |    [8,12,22]
- [8,11,12,16,21,22]

# Soru 2

- Big-O N = O(n*log n)