# Veri Yapıları ve Algoritma-Proje2
## https://patika.dev Eğitim Patikası- Veri Yapıları ve Algoritmalar - Merge Sort-Proje2
- 1).[16,21,11,8,12,22 ] Dizisinin Merge Sorta göre aşamaları;
- [16,21, 11] + [8, 12,22] <!-- Array önce ortadan ikiye ayrılır-->
- [16 ] + [ 21,11] + [8 ] + [12 ,22]
- [16 ] + [11, 21] + [8 ] + [12, 22] <!-- YApı her bir kutucuğun küçükten büyüğe göre sıralanmasıyla yeniden oluşturulur-->
- [11, 16,21] + [8,12, 22]
- [8,11,12,16, 21,22]
- 2) Big O Gösterimi = O(n*(logn)) => O(6*(log6))
