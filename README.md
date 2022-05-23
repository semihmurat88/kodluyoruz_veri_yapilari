# Veri Yapilari Alistirmalar

## Insertion Sort

[22, 27, 16, 2, 18, 6] dizisinin siralanmasi

- Adim-1 [2, 27, 16, 22, 18, 6] (n)
- Adim-2 [2, 6, 16, 22, 18, 27] (n-1)
- Adim-3 [2, 6, 16, 18, 22, 27] (n-2)

### Time Complexity

#### Worst Case : 
Her defasinda aradigimiz sayinin sonda olmasi durumunda O(n^2) olur.

#### Average Case : 
Aradigimiz sayi tam ortada ise O(logn) olur.

#### Best Case :
Aradigimiz sayi en basta ise O(n) olur.

[7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Insertion Sort algoritmasina gore ilk 4 adimi:

- Adim-1 [2, 3, 5, 8, 7, 9, 4, 15, 6]
- Adim-2 [2, 3, 4, 8, 7, 9, 5, 15, 6]
- Adim-3 [2, 3, 4, 5, 7, 9, 8, 15, 6]
- Adim-4 [2, 3, 4, 5, 6, 9, 8, 15, 7]

## Merge Sort

[16,21,11,8,12,22] -> Merge Sort

- Adim-1: [16, 21, 18] [8, 12, 22]
- Adim-2: [16] [21, 18] [8] [12, 22]
- Adim-3: [16] [21] [18] [8] [12] [22]
- Adim-4: [16] [18, 21] [8] [12, 22]
- Adim-5: [16, 18, 21] [8, 12, 22]
- Adim-6: [8, 12, 16, 18, 21, 22]

Time Complexity O(nlogn) olur.


