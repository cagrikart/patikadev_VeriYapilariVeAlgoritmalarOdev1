# patikadev_VeriYapilariVeAlgoritmalarOdev1
patika dev başlangıç seviye java kampının veri yapıları ve algoritma kısmının Insertion Sort Projesidir 

insertion Sort nedir ? 
  Insertion sort(Araya sokma sıralaması) algoritmasında problemimiz verilen sırasız bir diziyi sıralamak üzerine kurulu. 
  Algoritma her seferinde dizinin üzerinde ileri doğru ilerleyerek, dizinin bir elemanını alıp geriye doğru elemanlar ile bir bir sıralar ve her bir sıralamasında, eğer sıraladığı elemandan daha küçükse o elemanla yer değiştirerek bir geriye atar.
Big-O Notation Nedir ? 
  Bir algoritmanın performansını ve time complexity'sini hesaplamak için kullanılır.
Time complexity Nedir ? 
  Time complexity bir algoritmanın çalışması için gerekli olan süredir. Ancak buradaki süre, saniyeleri hesaplayarak değil, kaç tane işlem gerçekleştirdiğine göre hesaplanmaktadır.
  Uygulama tarafından gerçekleştirilen işlem sayısı, veri setinin büyüklüğüne ve o veri setindeki elemanlarına sırasına göre belirlenir.
  
 [22,27,16,2,18,6] -> Insertion Sort
  Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

    2 ile 22 yer değiştiriyor 
      [2,27,16,22,18,6]  
    6 ile 27 yer değiştiriyor.
      [2,6,16,22,18,27] 
    Sıradaki eleman en küçük. Dokunmadan devam et.
      [2,6,16,22,18,27] 
    5. eleman 6. elemandan daha küçük devam et 
      [2,6,16,18,22,27] 
    6.eleman en büyük elaman doğru 
      [2,6,16,18,22,27] 
  Big-O gösterimini yazınız.
     O(n²) = O(6²) = O(36)
  Time Complexity:
     Average case: Aradığımız sayının ortada olması,
     Worst case: Aradığımız sayının sonda olması,
     Best case: Aradığımız sayının dizinin en başında olması.
  
  Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
     Averge case
  
  [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
	  [2,3,5,8,7,9,4,15,6]
  	[2,3,5,8,7,9,4,15,6]
 	  [2,3,4,8,7,9,5,15,6]
 	  [2,3,4,5,7,9,8,15,6]]








 
