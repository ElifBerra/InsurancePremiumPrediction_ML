# InsurancePremiumPrediction_ML

# Medical Insurance Premium Prediction
Bu proje, kişilerin sağlık verilerini kullanarak yıllık sigorta primlerini (PremiumPrice) tahmin etmeyi amaçlayan bir regresyon çalışmasıdır.
Veri seti üzerinde veri temizliği, aykırı değer analizi (outlier analysis) ve gelişmiş makine öğrenmesi algoritmaları kullanılarak model optimizasyonu gerçekleştirilmiştir.

## 🛠️ Proje İçeriği
Bu çalışma, bir veri bilimcinin uçtan uca bir regresyon projesinde izlemesi gereken tüm aşamaları kapsamaktadır:
### Veri Keşfi (EDA): 
Veri setinin yapısal incelenmesi.
### Aykırı Değer Analizi: 
IQR yöntemi ile verideki uç değerlerin tespit edilmesi.
### Özellik Ölçeklendirme: 
StandardScaler kullanılarak verilerin model için normalize edilmesi.
### Model Optimizasyonu: 
LinearRegression ile başlayan sürecin, RandomForestRegressor ile %71'den %87 başarı skoruna ($R^2$) çıkarılması.

## 📊 Analiz ve Görselleştirmeler
### Tahmin vs. Gerçek Değer
Modelin tahmin yeteneğini değerlendirmek için gerçek değerler ile modelin tahminleri karşılaştırılmıştır.
### Özellik Önemi (Feature Importance)
Sigorta primini belirleyen en kritik faktörler analiz edilmiştir. Grafik, yaşın (Age) prim üzerinde en baskın değişken olduğunu göstermektedir.
### Hata Analizi (Residual Analysis)
Modelin hata payları incelenmiş ve sistematik sapmalar tespit edilmiştir. Bu analiz, modelin belirli fiyat aralıklarındaki tahmin hassasiyetini göstermektedir.

## 📈 Sonuçlar
### İyileştirilmiş Model: 
RandomForestRegressor
### Final Başarı Skoru ($R^2$): 
0.87
### Temel İçgörü: 
Sigorta primlerini etkileyen en önemli faktör yaş (Age) değişkenidir.


<img width="906" height="407" alt="image" src="https://github.com/user-attachments/assets/441ef218-d4c7-4c19-bff3-8e331439324f" />
<img width="417" height="641" alt="image" src="https://github.com/user-attachments/assets/ddb5e3b4-7b45-4809-9aaa-8e974e558270" />
<img width="762" height="803" alt="image" src="https://github.com/user-attachments/assets/77216c18-016a-42b7-8427-d9d3fbcadca8" />
<img width="644" height="518" alt="image" src="https://github.com/user-attachments/assets/9e411995-3d0e-4e8a-8d6f-259adc281303" />
<img width="784" height="544" alt="image" src="https://github.com/user-attachments/assets/c784f5a9-6af6-43f2-ba43-ee1ad50282c6" />
<img width="852" height="444" alt="image" src="https://github.com/user-attachments/assets/28ae0168-17e9-4174-9b65-adbce9e76a97" />
<img width="602" height="226" alt="image" src="https://github.com/user-attachments/assets/5b56c0aa-8c30-40fa-bc2d-8d3f1f2fb7b9" />
<img width="911" height="699" alt="image" src="https://github.com/user-attachments/assets/79ade421-e8e0-4c0e-8201-e4e963ccedb6" />
<img width="754" height="547" alt="image" src="https://github.com/user-attachments/assets/cdab9c28-8b32-468e-9991-f4fcdeba516f" />
<img width="656" height="576" alt="image" src="https://github.com/user-attachments/assets/f57481ec-d34c-432a-8946-6874d0e0a1dd" />



