# GlobalAI-Data-Analyst-Project

https://www.kaggle.com/code/fundatatl/aygaz-data-analysis    


Projede aşağıdaki araçlar ve kütüphaneler kullanılmıştır:

Python: Veri analizi ve görselleştirme için temel programlama dili.
Pandas: Veri manipülasyonu ve temizleme.
NumPy: Matematiksel işlemler ve veri işleme.
Matplotlib: Temel veri görselleştirme.
Seaborn: İleri düzey ve estetik görselleştirme.
Jupyter Notebook: Analiz adımlarını düzenlemek ve belgelerle birleştirmek için.



Yapılan Adımlar
1. Veri Yükleme ve Keşif
Veri seti projeye dahil edilip ilk olarak yapısı incelendi.
df.head() ile veri setinin ilk 5 satırı incelenerek kolon yapısı ve veri formatı analiz edildi.
2. Veri Temizleme
Eksik değerler kontrol edilerek uygun stratejilerle dolduruldu veya çıkarıldı.
Gereksiz kolonlar kaldırıldı.
Verideki tarih bilgisi, zaman serisi analizine uygun hale getirildi.
3. Keşifsel Veri Analizi (EDA)
İstatistiksel Özellikler: df.describe() kullanılarak temel istatistikler çıkarıldı.
Zaman Serisi Analizi: Satışların dönemsel trendlerini analiz etmek için çizgi grafikleri oluşturuldu.
Ürün Performansı: Ürün bazında satış miktarları ve gelir dağılımları analiz edildi.
Korelasyon Analizi: Farklı değişkenler arasındaki ilişkiyi görmek için korelasyon matrisi oluşturuldu.
4. Veri Görselleştirme
Satış Trendleri: Matplotlib ve Seaborn ile çizgi grafikleri ve sütun grafikleri oluşturuldu.
Ürün Kategorileri: Hangi ürünlerin daha fazla satıldığını göstermek için pasta grafikleri kullanıldı.
Outlier Tespiti: Boxplot'lar ile uç değerler tespit edildi.
Sonuçlar ve İçgörüler
Öne Çıkan Bulgular:
Dönemsel Satışlar:
Satışlarda belirli aylarda artış olduğu, özellikle yaz aylarında satışların zirve yaptığı gözlemlendi.
Ürün Performansı:
Bazı ürünler düzenli olarak diğerlerine göre daha yüksek gelir sağladı, bu ürünlerin daha fazla pazarlanması önerilebilir.
Anormallikler:
Bazı tarihlerde alışılmadık derecede yüksek satış miktarları tespit edildi. Bu anormallikler, kampanyalar veya özel günler ile ilişkili olabilir.
Öneriler:
Mevsimsel satış artışlarına yönelik stok planlaması yapılabilir.
Çok satan ürünler için pazarlama stratejileri yoğunlaştırılabilir.
Uç değerlerin nedenlerini anlamak için daha detaylı analiz yapılabilir.
