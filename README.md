# Merge-Sort-Projesi

[16,21,11,8,12,22] -> Merge Sort

# Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
merge de  tek bir eleman kalana kadar ikiye bölüyoruz. Ardından parçaları küçükten büyüğe sıralayıp birleştiriyoruz.

                [16,21,11,8,12,22]
         
          [16,21,11]                             [8,12,22]
   
     [16,21]        [11]                   [8,12]           [22]
  
    [16]   [21]     [11]                  [8]   [12]        [22]  
   
      [16,21]       [11]                    [8,12]          [22]
  
          [11,16,21]                              [8,12,22]
     
                    [8,11,12,16,21,22]
                    
# Big-O gösterimini yazınız.

 O(n.logn)

www.patika.com
