# Merge-Sort-Project
Patika.dev Merge Sort Project
Patika Dev Profile: https://app.patika.dev/aegoksu

## PROJECT 2 
[16,21,11,8,12,22] -> Merge Sort

  1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
  2. Big-O gösterimini yazınız.
  
 ### 1. ANSWER 1 ###

-Önce diziyi 2'ye bölücez: [16,21,11] [8,12,22]
-Böldüğümüz sayıları tekrar 2'ye ayırıyoruz: [16,21] [11] [8] [12,22]
-Tek eleman kalana kadar devam ediyoruz: [16] [21] [11] [8] [12] [22]

  [16,21,11,8,12,22]
   /     /   \     \
[16,21] [11] [8] [12,22]
 /   \    |    |   \   \ 
[16] [21] [11] [8] [12] [22]

-Şimdi de sıralı hale getirerek ayırdığımız şekilde birleştiriyoruz.

[16] [21] [11] [8] [12] [22]
  \    /   |    |    \  /
  [16,21] [11] [8] [12,22]
      \    /     \     /
    [11,16,21]  [8,12,22]
          \        /
      [8,11,12,16,21,22]
      
  ### 2. ANSWER 2 ###

     O(nlogn)
     
     Merge sort'da nlogn olduğu için açık ara performans olarak insertion sorttan daha iyi diyebiliriz.
