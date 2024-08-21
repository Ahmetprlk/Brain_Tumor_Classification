Bu proje, beyin tümörlerini sınıflandırmak için derin öğrenme yöntemlerini kullanarak bir model geliştirmeyi amaçlamaktadır. Projede, beyin tümörü olup olmadığını belirlemek için VGG19 mimarisine dayanan bir konvolüsyonel sinir ağı (CNN) kullanılmaktadır. Model, iki ana adımda eğitim almıştır: ilk olarak, önceden eğitilmiş VGG19 modelinin ağırlıklarıyla transfer öğrenme kullanılarak bir model oluşturulmuş, ardından bu model üzerinde belirli katmanları yeniden eğiterek performans iyileştirmesi yapılmıştır.

Veriler
Proje, beyin tümörü bulunan ("yes") ve beyin tümörü bulunmayan ("no") görüntüleri içeren iki veri kümesi kullanılarak eğitilmiştir. Görüntüler, çeşitli veri artırma teknikleriyle genişletilmiştir, bu sayede modelin genelleme yeteneği artırılmıştır.

Model
İki ana model eğitilmiştir:

Model 01: VGG19 tabanlı bir modeldir. Bu model, ağırlıkları önceden eğitilmiş VGG19 modelinden alarak transfer öğrenme yapılmıştır.
Model 02: İlk modelin ağırlıkları üzerinde belirli katmanların yeniden eğitilmesiyle oluşturulmuştur. Bu, modelin daha fazla özelleştirilmesini sağlar.
Her iki model de sınıflandırma performansını artırmak için çeşitli eğitim teknikleri ve optimizasyon yöntemleri kullanılarak eğitilmiştir.
