# Merge-Sort-Projesi
# [16,21,11,8,12,22] -> Merge Sort
# Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
# ÇÖZÜM: öncelikle diziyi ikiye bölelim.
# [16,21,11]  ;   [8,12,22]
# sonra bu üçlü grupları 2şer ve 1erli tekrar bölüyoruz.
# [16,21] ; [11] ve [8,12] ; [22]
# daha sonra tek elemana indirgeyene kadar bölmeye devam ediyoruz.
# [16][21][11][8][12][22]
# [11,16,21]; [8,12,22] sonrasında geri toplayarak sıraya sokarız.
# [8,11,12,16,21,22] şeklinde sıralanır.
# Big-O gösterimini yazınız.
# ÇÖZÜM:
# O(nlogn) ve n=6; O(6log6) olarak ifade edilir.
# https://www.patika.dev
