# Insertion Sort Odevi
- [Patika Profil Linkim](https://app.patika.dev/ozanege)

## Proje 1
- [22,27,16,2,18,6] -> Insertion Sort  

1. Yukardaki verilen dizinin sort türüne göre aşamalarını yazınız.

    - İlk önce bütün öbeği inceleriz; en küçük sayı ile en baştaki sayıyı yer değiştiririz.
      - [2,27,16,22,18,6] -> 2 ile 22 yer değiştiyor.
    - 2'den sonra gelen en küçük sayıyı buluyoruz ve ikinci sırada olan sayı ile yer değiştiriyoruz.
      - [2,6,16,22,18,27] -> 6 ile 27 yer değiştiriyor.
    - Aynı kuralı dizimiz sıralanana kadar sürdürüyoruz.
      - [2,6,16,18,22,27] -> 18 ile 22 yer değiştiriyor.
      - [2,6,16,18,22,27] -> 5. sıradaki sayı en küçük olduğu için yer değiştirme olmaz.
      - [2,6,16,18,22,27] -> 6. sıradaki eleman en büyük olur ve dizi öbeğimiz küçükten büyüğe sıralanmış olur.    

2. Big-O gösterini yazınız. 

    - İlk turda n elemanımız olsun ve biz en küçüğü bulmak için n elemanını kontrol ederiz. Sonrasında ise geri kalan elemanları kontrol ederiz yani n-1 elamana bakarız. Böyle devam eder ve n+(n-1)+(n-2).. şeklinde ilerler. Yani 1'den n'e kadar olan sayıların toplamından (n.(n-1))/2 gelir buradan da Big-O Notation'umuz O($n^2$) olur yani O($6^2$) yani O(36)'dır.  


3. Time Complexity: 
   - Avarage Case: Aradığımız sayının ortada olması.
     - 16,18
   - Worst Case: Aradığımız sayının sonda olması.
     - 27
   - Best Case: Aradığımız sayının dizinin en başında olması.         
     - 2

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
   - 18

  - [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
    - [2,3,5,8,7,9,4,15,6]
    - [2,3,5,8,7,9,4,15,6]
    - [2,3,4,8,7,9,5,15,6]
    - [2,3,4,5,7,9,8,15,6]

    [Patika](https://app.patika.dev/)