Bu projede, oldukça dengesiz (unbalanced) bir veri setinde fraud tespiti yapılmıştır. Veri setindeki sahte işlem oranı çok düşük olduğu için, modelleme sürecinde dengeleme teknikleri kullanılmıştır.
Sonuçlar, veri setinin yapısı göz önüne alındığında ulaşılabilecek en iyi seviyededir. Analizde, SMOTE, class_weight ayarı veya benzeri dengeleme yöntemleri kullanılmış; modelin azınlık sınıfa olan duyarlılığı artırılmıştır.

Not: Bu projenin orijinal veri dosyası (large_dataset.csv) yaklaşık 97 MB boyutunda olduğu için GitHub’ın dosya yükleme limiti nedeniyle repoya eklenmemiştir.
Veri dosyasının temel yapısı ve içerdiği sütunlar aşağıda özetlenmiştir.
Analizler ve kodlar, bu veri seti temel alınarak hazırlanmıştır.
----
This project focuses on fraud detection using a highly unbalanced dataset. Since the proportion of fraudulent transactions is very low, balancing techniques were applied during modeling.
The results achieved are among the best possible for this data structure. In the analysis, SMOTE, class_weight adjustment or similar balancing methods were used to increase the sensitivity of the model to the minority class.

Note: The original dataset (large_dataset.csv) is approximately 97 MB in size and has not been uploaded to this repository due to GitHub’s file size limitations.
The structure and key columns of the dataset are summarized below.
All analyses and code in this project are based on this dataset.
