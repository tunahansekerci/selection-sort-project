# selection-sort-project

[22,27,16,2,18,6] -> Insertion Sort

Yukarıdaki sayı dizisinin sort türüne göre sıralanma aşamaları;


- Dizinin ikinci elemanı başlangıç elemanı olarak seçilir.
- [27]

- Daha sonra 27 ile 22 kıyas edilir. 22 < 27 olduğu için sıralama aynı şekilde kalır.
- [22,27,16,2,18,6] - Son Durum

- Dizinin üçüncü elemanı 16 kontrol edilir. 16 < 27 ve 16 < 22 olduğu için dizinin en başına kaydırılır.
- [16,22,27,2,18,6]

- Dizinin dördüncü elemanı 2 kontrol edilir. 2 < 27 ve 2 < 22 ve 2 < 16 olduğu için dizinin en başına kaydırılır.
- [2,16,22,27,18,6]

- Dizinin beşinci elemanı 18 kontrol edilir. 18 < 27 ve 18 < 22 olduğu için dizinin üçüncü sırasına kaydırılır.
- [2,16,18,22,27,6]

- Dizinin son elemanı 6 kontrol edilir. 6 < 27 ve 6 < 22 ve 6 < 18 ve 6 < 16 olduğu için dizinin ikinci sırasına kaydırılır.

- Dizinin Son Hali 
- [2,6,16,18,22,27]

Big-O gösterimini yazınız.

-Big-O=(n^2)

- Time Complexity:
- Average Case
--------------------------------

- [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı

- 1 - [2,3,5,8,7,9,4,15,6]
- 2 - [2,3,4,8,7,9,5,15,6]
- 3 - [2,3,4,5,7,9,8,15,6]
- 4 - [2,3,4,5,6,9,8,15,7]
