
# [22,27,16,2,18,6] -> Insertion Sort Proje 1
# 1)Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
1. [22,27,16,2,18,6] -> 22<27 olduğu için 22,27
2. [22,27|16,2,18,6] -> 16<27 ve 16<22 olduğu için 16,22,27  
3. [16,22,27|2,18,6] -> 2<27 ve  2<22, 2<16  olduğu için  2,16,22,27 
4. [2,16,22,27|18,6] -> 18<27 ve 18<22, 16<18 olduğu için 2,16,18,22,27 
5. [2,16,18,22,27|6] -> 6<27 ve 6<22, 6<18, 6<16 2<6 olduğu için 2,6,16,18,22,27 
6. [2,6,16,18,22,27]

# 2)Big-O gösterimini yazınız.

n + (n-1) + (n-2) + (n-3) + 1 = n.(n+1) / 2 = n^2+1/2 = O (n^2)

# 3)Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
Average case: Aradığımız sayının ortada olması <br>
Worst case: Aradığımız sayının sonda olması <br>
Best case: Aradığımız sayının dizinin en başında olması. <br>

[2,6,16,18,22,27] dizisinde 18 sayısı ortada olduğu için Average Case'e girer.
# 4)[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
Sırasıyla
## *-	[2,3,5,8,7,9,4,15,6]

## *-	[2,3,4,8,7,9,5,15,6]

## *-	[2,3,4,5,7,9,8,15,6]

## *-	[2,3,4,5,6,9,8,15,7]
