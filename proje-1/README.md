# Selection Short projesi:
## [22,27,16,2,18,6] (n)

## 1- short türüne göre sıralanışı:

### 22|27 16 2 18 6 (n-1) 1. işlemde 0. indexi sıralanmış kabul eder. 
### 22 27|16 2 18 6 (n-2) 
### 22 16 27|2 18 6 -> (swap) 16 22 27| 2 18 6 (n-3)
### 16 22 2 27|18 6->(swap) 16 2 22 27|18 6-> 2 16 22 27|18 6 (n-4)
### 2 16 22 18 27|6 ->(swap) 2 16 18 22 27|6 (n-5)
### 2 16 18 22 6 27| ->(swap) 2 16 18 6 22 27| ->2 16 6 18 22 27| ->2 6 16 18 22 27| (n-6)

## 2-big-o notation:
### n.(n-1)/2=n^2-n/2 => o(n^2)

## Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?

### 18 sayısı dizinin ortasında olduğu için avarage case kapsamına girer.

## [7,3,5,8,2,9,4,15,6] selection short'a göre ilk 4 adımı?

### [2,3,5,8,7,9,4,15,6] (1. adım)
### [2,3,4,8,7,9,4,15,6] (2.adım)
### [2,3,4,5,7,9,8,15,6] (3. adım)
### [2,3,4,5,6,9,8,15,7] (4. adım)
