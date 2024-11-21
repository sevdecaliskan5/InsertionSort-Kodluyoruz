# Insertion Sort

**Proje 1**
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

# Insertion Sort Aşamaları:
Başlangıç dizisi: [22, 27, 16, 2, 18, 6]

Ilk eleman 22 olarak kabul edilir ve karsilastirmaya 27'den baslanir. 27 22'den buyuk oldugu icin siralam degismez. Daha sonra 16'ya gecilir. 16 hem 22 hem de 27'den kucuk oldugu icin en basa yazilir. Yeni siralama [16,22,27,2,18,6] seklinde olur. Daha sonra 2 icin ayni sistem uygullanir ve yeni dizi [2,16,22,27,18,6] seklinde olur. Islem bu sekilde devam eder ve yeni dizi [2,16,18,22,27,6] haline gelir. En son ise [2,6,16,18,22,27] halini alir.

# Time Complexity Durumu (18 Sayısı İçin):
Verilen dizi sıralandıktan sonra 18 sayısı, Average Case durumuna girer çünkü 18, dizide ortada bir konumda yer alacaktır.

**Average Case:** Aradığımız sayının ortada olması.
Dizi sıralandıktan sonra: [2, 6, 16, 18, 22, 27]. Bu durumda 18, dizinin ortasında yer alır.

------------------------------------------------------------------------------------------------

# Selection Sort

**Proje 2** 
(7, 3, 5, 8, 2, 9, 4, 15, 6) ->  -> Selection Sort

# Selection Sort Aşamaları:
Başlangıç dizisi: [7, 3, 5, 8, 2, 9, 4, 15, 6]

Selection Sort methodunda ilk olarak tum veriler taranir ve en kucuk olan secilir. Dizimizdeki en kucuk sayi 2 oldugu icin 2'yi en sola aliriz ve oradaki 7'yi 2'nin eski yerine koyarız. Yani yeni dizimiz [2,3,5,8,7,9,4,15,6] seklinde olur. Daha sonra en kucuk 2. sayiya bakariz. Bu da dizimizde 3'e karsilik geliyor. 3 dogru yerde oldugu icin bi degisiklik yapmayacagiz. Dizimiz ikinci asamada da [2,3,5,8,7,9,4,15,6] bu siralamada olacak. Daha sonra 3. asamada en kucuk 3. sayimizi buluyoruz bu da dizimizde 4'e karsilik geliyor. Bu sayiyi da 3'un sagina yerlestiriyoruz(5 ile yer degistiriyoruz) Yeni dizimiz [2,3,4,8,7,9,5,15,6] seklini aliyor. Sorudaki 4. asamada da yine ayni sistemi uyguluyoruz ve yeni dizimizin sekli [2,3,4,5,7,9,8,15,6] halini aliyor. 
