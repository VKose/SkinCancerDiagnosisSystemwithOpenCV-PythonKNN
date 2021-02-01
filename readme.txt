ABCD yöntemi matematiksel işlemlerle desteklenerek bilgisayarın anlayacağı hale getirilmiştir. 
ISIC'den alınan örnek veri setindeki 10 farklı konumdaki verilerin sonuçlarının
ortalamasına göre başarı durumu yorumlanmıştır.

Lezyonun hastalıklı veya sağlıklı olduğunu tespit etmek için KNN en yakın komşu algoritmasına 
gönderilecek veriler için merkezden sınıra olan düzensiz uzunluklara ait nokta sayısı, 
türev ile bulunmuş sınırdaki yüksek sıçrama yapan nokta sayısı, lezyon renginin standart sapması, 
çapı, benzerlik oranı, kontur sayısı gibi öznitelikler kullanılmıştır.

Tek başına doğruluk (accuracy) oranı yetersiz kalmaktadır. Bu nedenle, kesinlik yani 
hastalıklı tahmin edilenlerin kaçının hastalıklı olduğu, duyarlılık yani hastalıklı olanların 
doğru tespit oranı ve f1 score hassasiyeti ile sağlamlık oranı belirlenmiştir. 


Projenin Çalıştırılması:

1) Lezyon bölgelerine ait görüntüler "foto" klasörüne eklenir.
2) Hair_Filtering.py dosyası çalıştırılarak görüntüler üzerinde işlem yapılarak  "foto2" klasörüne kaydedilir.
3) Main.py dosyası çalıştırılarak "foto2" klasöründeki fotoğrafların öznitelikleri lezyon.csv dosyasına yazılır.
4) knn.py dosyası çalıştırılarak lezyon.csv dosyasından veriler ile knn algoritması tahmin yapmaktadır. 

Running the Project:

1) Images of lesion areas are added to the "foto" folder.
2) Hair_Filtering.py file is run and processed on the images and saved in the "foto2" folder.
3) The Main.py file is run and the attributes of the photos in the "foto2" folder are written to the lezyon.csv file.
4) By running the knn.py file, the knn algorithm estimates with the data from the lezyon.csv file.