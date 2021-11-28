# Q-Learning ile Yol Planlaması

**ÖZET: 
Q-Learning algoritması kullanarak engeller matrisinde ajanın oluşturacak arayüz ile kullanıcıdan alınan başlangıç ve bitiş koordinatları kullanarak en kısa ve en az maliyetle bir yol bulması ve bunu başka bir arayüz ile veri görselleştirilmesi amaçlanmıştır.
Proje “Python” dilinde “Numpy”, “Matplotlib” ve “Tkinter” kütüphanelerinden yararlanılarak yazılmıştır.**

**
GENEL BİLGİLER: 
Ajan Q-Learning algoritmasını 
kullanarak engel sütunlarından kaçması 
ve beyaz alanlardan geçerek doğru yol 
alması gerekiyor. Ajanımız belirtilen 
beyaz kareden başlayıp kırmızı kutulara 
çarpmadan bitiş kısmına en 
kısa(maliyetle) yoldan ulaşarak başarılı 
sayılmaktadır.
Q-learning pekiştirmeli bir öğrenme 
algoritmasıdır. Ortam hakkında hiçbir 
şeyin bilinmediği durumlarda, Qlearning algoritması ortamı brute-force 
şeklinde, her ortam için olası tüm 
aksiyonları takip ederek, problem 
çözümü için en karlı yolu 
bulmaya çalışır. Q-learning 
algoritmasının girdileri kazanç matrisi 
olarak adlandırılan R matrisidir. Bu 
matrisin satır ve sütunları ortamları 
temsil etmekte, R[i][j] değeri ise i 
durumundan j durumuna geçtiğinde elde 
edilen anlık kazanç değeridir. Eğer i 
durumunda j durumuna bir geçiş yoksa 
R[i][j] değeri -1, geçiş var ancak j 
durumu hedef durum değilse değeri 0, j 
hedef durum ise değeri kullanıcı 
tarafından belirlenen bir kazanç 
değeridir. Q-learning algoritmasının 
çıktısı ise öğrenmenin kalitesini 
gösteren Q matrisidir. Q-learning iteratif 
bir algoritmadır ve tüm değerleri 
başlangıçta 0 olan Q matrisi optimum 
değerlere yakınsadığı da sona erer. 
Algoritma her iterasyonda rastgele bir 
durumdan öğrenmeye baslar, A’ya göre 
durum değiştirir ve Q matrisini 
günceller. A’ya göre hedef duruma 
ulaşıldığında iterasyon sona erer. A’ya 
göre bir durumdan birden fazla duruma 
geçiş olabilir. Böyle bir durumda, olası 
geçişler den biri rastgele seçilir. Eğer 
seçilen durum hedef duruma 
ulaştırmıyorsa, durum rastgele olacak 
durum olarak belirlenir. Hedef duruma 
ulaşılana kadar iterasyon devam eder. 

**
## Proje çıktı örnek görselleri:


![Image of Yaktocat](https://github.com/Umayyhan/FirebaseProjects/blob/main/images/Ekran%20görüntüsü%202021-11-15%20222336.png)
