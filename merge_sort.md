# Proje-2
## [16,21,11,8,12,22] -> Merge Sort
  
1. Yukardaki dizinin sort türüne göre aşamalarını yazınız.
- Başlangıçta olan dizimizi ikiye bölüyoruz. Bölünen dizileri tekrar ikiye bölüyoruz. Tek eleman kalana kadar işleme devam ediyoruz.  

       
|                                                     |  |  |  |  |  |  |  |  |  |  |  |  |
|-----------------------------------------------------|- |- |- |- |- |- |- |- |- |- |- |- |
|Dizimizi ikiye bölerek yeniden yazıyoruz.            |  |  |  |16|21|11|8 |12|22|  |  |  |
|                                                     |  |  |  |  |  |  |  |  |  |  |  |  |
|Sol ve sağdaki diziler tekrar ikiye bölüyoruz.       |  |  |16|21|11|  |  |8 |12|22|  |  |
|                                                     |  |  |  |  |  |  |  |  |  |  |  |  |
|Tek eleman kalana kadar bir kez daha ikiye bölüyoruz.|  |16|21|  |11|  |  |8 |  |12|22|  |
|                                                     |  |  |  |  |  |  |  |  |  |  |  |  |
|                                                     |16|  |21|  |11|  |  |8 |  |12|  |22|

- Bölme işlemi bittikten sonra, tek eleman olan dizileri ikili ikili birleştiriyoruz. Sıralı dizi elde edinceye kadar bu işleme devam ediyoruz.

|                                                     |  |  |  |  |  |  |  |  |  |  |  |  |
|-----------------------------------------------------|- |- |- |- |- |- |- |- |- |- |- |- |
|                                                     |16|  |21|  |11|  |  |8 |  |12|  |22|
|                                                     |  |  |  |  |  |  |  |  |  |  |  |  |
|İkili ikili sıralayarak birleştiriyoruz.             |  |16|21|  |11|  |  |8 |  |12|22|  | 
|                                                     |  |  |  |  |  |  |  |  |  |  |  |  |
|Tekrar ikili ikili sıralayarak birleştiriyoruz.      |  |  |11|16|21|  |  |8 |12|22|  |  |
|                                                     |  |  |  |  |  |  |  |  |  |  |  |  |
|Son birleştirmede dizimizi elde ediyoruz.            |  |  |  |8 |11|12|16|21|22|  |  |  |
|                                                     |  |  |  |  |  |  |  |  |  |  |  |  |


2. Big-O gösterimini yazınız.
Recursive bir fonksiyon olduğu için sürekli kendini ikiye bölmektedir. Her bölünmüş dizinin Merge işlemi için dizinin uzunluğu olan n işlem yapılır. 
     - O(n*(logn)) --> O(6*(log6)) olur.

[Patika profilim](https://app.patika.dev/ozanege)
