# insertion-sort-odev-1

Insertion Sort Projesi

[22,27,16,2,18,6]
_____________________________

1.Soru aşamaları
  [2,27,16,22,18,6]
  [2,6,16,22,18,27]
  [2,6,16,22,18,27]
  [2,6,16,18,22,27]
  [2,6,16,18,22,27]
  
  2. Big(o) Notation
    Big(o) = (n^2) = (n*(n-1)(n-2)...) 1'den n 'e kadar olan sayıların toplamı n*(n-1)/2 dominant olann^2 olduğundan n^2'e kadar işlem yapılacaktır.
    
    3.Avarage case:ortadaki elemanı bulmak için işlem yapılacağından örneğin 4.sıradaki elemanı alacak olalım n*(n-1)(n-2)(n-3) 'e kadar işlem yapılacağındn sonucu n^2 olacaktır 
      Worst case: n^2 olacaktır 
      best case: n (n elemanlı bir dizide n eleman olacağından n kadar bakılacaktır)
      
    4. 8 elemanı diiznin ortalarında yer alacağından avarage case'e örnek olacaktır.
    
    
    [7,3,5,8,2,9,4,15,6] ilk dört adımı için 
    
      1.[2,3,5,8,7,9,4,15,6]
      2.[2,3,5,8,7,9,4,15,6]
      3.[2,3,4,8,7,9,5,15,6]
      4.[2,3,4,5,7,9,8,15,6]
  
