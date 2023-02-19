# Merge-Sort-Projesi


Verilen dizi [16, 21, 11, 8, 12, 22]

İlk olarak, diziyi ikiye bölüyoruz: [16, 21, 11] ve [8, 12, 22]
Her bir alt diziyi aynı şekilde ikiye bölüyoruz: [16], [21, 11], [8], [12, 22]
Şimdi, sol taraftaki alt diziyi sıralıyoruz: [16]
Sağ taraftaki ilk alt diziyi ikiye bölüyoruz: [21], [11]
Her bir alt diziyi sıralıyoruz: [11, 21]
Şimdi, sağ taraftaki ikinci alt diziyi sıralıyoruz: [8]
Son olarak, sağ taraftaki son alt diziyi sıralıyoruz: [12, 22]
Artık her iki tarafı birleştirebiliriz: [16], [11, 21], [8], [12, 22]
[11, 16, 21], [8, 12, 22]
Her iki sıralanmış alt diziyi birleştiriyoruz: [8, 11, 12, 16, 21, 22]
Dolayısıyla, verilen dizi Merge Sort ile sıralandıktan sonra [8, 11, 12, 16, 21, 22] şeklinde olacaktır.

Merge Sort'un Big-O gösterimi O(n log n) dir.
