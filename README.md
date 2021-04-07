# CrowdZone-

Ekip / Team:
Fırat Ülgen
Naz İrem Baz
Yeşim İpek

Proje Özeti:

CrowdZone,  yüksek nüfuslu kentlerin kalabalığının kontrolü üzerine çalışan bir yoğunluk analizi projesidir. CrowdZone projesinin öncelikli amaçları Pandemi için risk yaratan kalabalık noktaların tespiti ve insanların ilgi gösterdiği yerlerin tespiti şeklindedir.  İstanbul özelinde çalışmalar gerçekleştirilmiştir. Bu noktada proje ile kalabalığın güvenli şekilde yönetilmesi, yoğun geçen toplu taşıma  zaman aralıklarının tespiti ile plan optimizasyonuna yardımcı olunması, ilgi odağı yerlerin tespitiyle belediye hizmetlerinin isabetli şekilde konumlandırılması (örneğin Halk Ekmek) katkılarını İstanbul’a kazandırmak hedeflendi.  

Proje sürecinde iki görüntü işleme modeli değerlendirildi. Modellerde elde etmek istenilen amaç, görüntülerdeki insanların model tarafından doğru algılanması ve lokalizasyon tespitidir. Sonuç olarak yoğunluk haritası ve kalabalıktaki insan sayısı hesabı için farklı, ilgi odağı yerlerinin tespiti için farklı evrişimsel sinir ağları modelleri geliştirildi. IBB Şehir ve IBB Mobese kameralarından topladığımız kalabalık meydan görüntülerini iki modelde de tahminleyerek meydanların yoğunluk analizini gerçekleştirmiş bulunduk.

Project Summary : 

CrowdZone is a project that focuses on analyzing the density where it aims to control the crowd in highly-populated cities. CrowdZone is primarily aimed to  identify the risk points for the pandemic and to determine places where people show great interest. Analyzes and studies have been carried out, mainly based in Istanbul. Therefore, contributions to Istanbul can be listed in three points: Arrangements in places and streets to ensure safety against pandemic ; Optimizing transportation planning by detecting peak times on public transportation lines ; Finding the best locations for municipality services (for example Halk Ekmek) depending on the popular areas.

Two different image processing models have been evaluated during the process. Aims behind those models training are person class detection and their location detection for density maps. Consequently, different convolutional neural network models have been developed either for the population density map and for the determination of interest points. With the developed models, the crowd countings and density maps  of highly-populated squares in Istanbul were predicted.

MAE Metric : 0.44 (CNN Model)

İstiklal Street --
Aprox. real number of people : 49
Predicted number of people : 41.48
<img width="686" alt="Screen Shot 2021-04-07 at 09 13 51" src="https://user-images.githubusercontent.com/75167252/113819183-a1705100-9781-11eb-9f28-9062d8b68277.png">
 


References :
* For Crowd Counting CNN model : Crowd Counting Github Project by Harrianto Sunaryan, Iyas Yustira, Muhammad Farrel M, Rinda Nur Hafizha

* For YOLOV4 model: İstanbul Poi Github Project of Enis Getmez
