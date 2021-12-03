# Music-Classification-with-SVM-K-NN-and-Logistic-Regression-Algorithms
SVM, K-NN ve Lojistik Regresyon algoritmaları ile librosa kütüphanesinden yararlanarak; rmse, chroma_stft, spectral_centroid, spectral_bandwidth, spectral_rolloff, zero_crossing_rate, ve mfcc (20 adet) öznitelikleri çıkarılarak  6 türe (arabesk,pop,klasik,dini,rap,rock) müzik türü sınıflandırılması yapılmıştır. 
SVM'de rbf, poly ve linear kernel'ler kullanılmıştır.
K-NN'de mesafe fonksiyonları olarak: "euclidean", "manhattan" ve "minkowski" kullanılmıştır. K için 8,9,10 değerleri kullanılmıştır.
Her bir algoritma için precision, recall, F1 Score' metrikleri elde edilmiştir.
Lojistik Regresyon'da ise C hiperparametresi 0.1 olarak belirlenerek sınıflandırma işlemleri gerçekleştirilmiştir. 
En yüksek başarım SVM ile rbf kernel kullanılarak %78.65 olarak elde edilmiştir.  
