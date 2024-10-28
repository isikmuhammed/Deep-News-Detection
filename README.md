# DeepNewsDetection – Sahte Haber Tespit Modeli

**Proje Açıklaması:**
DeepNewsDetection, haber içeriklerinin doğruluğunu analiz etmek için çeşitli makine öğrenimi modellerini kullanan bir sahte haber tespit sistemidir. Proje, Logistic Regression, Decision Tree, Gradient Boosting, ve Random Forest sınıflandırma algoritmalarını kullanarak haber metinlerini analiz eder ve "Gerçek Haber" ya da "Sahte Haber" olarak sınıflandırır.

**Proje Özellikleri:**
- **Veri Ön İşleme:** Metin temizleme, etiketleme ve öznitelik mühendisliği aşamalarını içerir.
- **Model Eğitimi:** Metin verilerinin ön işlenmiş versiyonu üzerinden eğitim yapılır. Bu aşamada dört farklı model denenmiş ve karşılaştırılmıştır.
- **Model Performansı:** Her bir model için doğruluk skorları ve sınıflandırma raporları değerlendirilmiştir.
- **Test Aşaması:** Eğitilen model, girilen yeni haber metinleri üzerinde çalıştırılarak manuel test yapılmıştır.

**Kullanılan Teknolojiler:**
- **Python Kütüphaneleri:** NumPy, Pandas, Scikit-Learn, Matplotlib, Seaborn
- **Makine Öğrenimi Algoritmaları:** Logistic Regression, Decision Tree, Gradient Boosting, Random Forest

**Nasıl Çalıştırılır:**
1. Gerekli kütüphaneleri yükleyin
2. Veri dosyalarını yükleyin ve veri temizleme işlemlerini gerçekleştirin.
3. `deepnewsdetection.py` dosyasını çalıştırarak modeli eğitin ve değerlendirme sonuçlarını alın.
4. Test etmek istediğiniz metni girerek modelin sınıflandırma sonuçlarını görün.

**Sonuçlar:**
Eğitim sonucunda, model çeşitli sınıflandırma algoritmaları kullanılarak değerlendirilmiş ve en uygun model seçilmiştir. Bu proje, sahte haber tespit sistemleri için işlevsel bir çözüm sunmaktadır ve haberlerin doğruluğunu kontrol eden sistemlere entegre edilebilir.

