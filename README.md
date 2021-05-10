# Sentiment-Analysis-With-Natural-Language-Processing
Gensim kütüphanesine bağlı doc2vec kullanılarak gerçekleştirilmiştir.

Projenin amacı alınan veri kümesinin duygu analizini yaparak verinin hangi duyguyu içerdiğini çıktı olarak kullanıcıya sunmasıdır. 
Makine öğrenmesi yöntemine dayalıdır. Geçmiş gözlemlerden duyguları tahmin etmeyi öğrenen makine öğrenimi algoritmalarını kullanılmaktadır.
Bu algoritma yaklaşımı için, karşılık gelen etiketleriyle birlikte örnek bir veri kümesine (analiz etmek istediğiniz verilere benzer) ihtiyacımız vardır.
Eğitim süreci sırasında model, metin verilerini vektörlere dönüştürür. 
Daha sonra her vektörü önceden tanımlanmış etiketlerden biriyle ilişkilendirmek için bir model tanımaktadır. 
Yeterli miktarda ilgili veri beslendikten sonra, makine öğrenmesi ile girilen veriler sınıflandırılmaktadır.

Projede kullanılan veri seti Cornell üniversitesinin İngilizce IMDB film yorumları verilerinden alınmıştır. Veri setinde aşağıda listelenen dosyalar bulunmaktadır.
-> test-neg.txt: 12500 olumsuz film yorumları içeren test verisi 
-> test-pos.txt: 12500 olumlu film yorumları içeren test verisi 
-> train-neg.txt: 12500 olumsuz film yorumları içeren eğitim verisi 
-> train-pos.txt: 12500 olumlu film yorumları içeren eğitim verisi 
-> train-unsup.txt: 50000 etiketsiz film yorumları verisi
 
