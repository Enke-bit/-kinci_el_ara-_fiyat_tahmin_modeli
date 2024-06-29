# Araç Fiyat Tahmini Projesi

## Genel Bakış

Bu proje, ikinci el araçların satış fiyatlarını tahmin etmeyi amaçlamaktadır. Proje kapsamında kullanılan veri seti, araçların üretim yılı, güncel fiyatı, sürülen kilometre, yakıt türü, satıcı türü, vites türü ve önceki sahip sayısı gibi çeşitli özelliklerini içermektedir. Bu projede kullanılan model, regresyon görevleri için güçlü bir topluluk öğrenme yöntemi olan Random Forest Regressor'dır.

## Veri Seti

Bu projede kullanılan veri seti aşağıdaki sütunlardan oluşmaktadır:
- `Car_Name`: Araç adı
- `Year`: Üretim yılı
- `Selling_Price`: Araç satış fiyatı
- `Present_Price`: Araç güncel fiyatı
- `Kms_Driven`: Araçla sürülen kilometre
- `Fuel_Type`: Yakıt türü (Benzin/Dizel/CNG)
- `Seller_Type`: Satıcı türü (Bayi/Bireysel)
- `Transmission`: Vites türü (Manuel/Otomatik)
- `Owner`: Önceki sahip sayısı

## Kullanılan Teknolojiler

Bu projede aşağıdaki teknolojiler ve kütüphaneler kullanılmıştır:
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Elde Edilen Sonuçlar

Proje sonucunda elde edilen Mean Absolute Error (MAE) değeri: `0.5872` dir. Rastgele seçilen bir veri için tahmin edilen ve gerçek fiyatlar aşağıdaki gibidir:

- Seçilen Örnek İndeksi: 46
- Tahmin Edilen Fiyat: 8.204
- Gerçek Fiyat: 6.25

Bu sonuçlar, modelin fiyat tahmininde oldukça iyi bir performans sergilediğini göstermektedir.

## Projeye Katkı ve Destek

Projeyi beğendiyseniz ve katkıda bulunmak isterseniz, lütfen projeyi fork edin ve pull request gönderin. Her türlü katkı ve destek için minnettar oluruz. Ayrıca, projeyi yıldızlayarak destek olabilir ve başkalarının da faydalanmasını sağlayabilirsiniz.

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına bakabilirsiniz.

## Gelecek Çalışmalar

Bu projede gelecekte yapılması planlanan çalışmalar:
- Daha fazla veri ile modeli geliştirmek
- Diğer makine öğrenimi algoritmaları ile karşılaştırma yapmak
- Modelin performansını artırmak için hiperparametre optimizasyonu
- Kullanıcı dostu bir arayüz oluşturmak

Bu projenin daha da geliştirilmesi ve yeni özellikler eklenmesi için her türlü geri bildirime açığız.

Teşekkürler!