# Aygaz Veri Analizi Bootcamp - Customer Churn Dataset

**-----Customer Churn Dataset-----**


https://www.kaggle.com/datasets/muhammadshahidazeem/customer-churn-dataset?select=customer_churn_dataset-training-master.csv


- Müşteri kaybı veri kümesi ilgili özellikleri ve müşteri kaybı etiketleriyle birlikte 440882 müşteri kaydı koleksiyonunu içerir.

- Her kayıt bir müşteriyi temsil eder ve yaş, cinsiyet, görev süresi, kullanım sıklığı, destek çağrıları, ödeme gecikmesi, abonelik türü, sözleşme uzunluğu, toplam harcama ve son etkileşim gibi özellikleri içerir.

- Churn etiketi, müşterinin müşteriyi kaybettiğini (1) veya kaybetmediğini (0) gösterir.


**Değişkenler:**

1. Gender -> müşterinin cinsiyeti, veri tipi object ( Female - Male)
2. Subscription Type -> müşterinin abone oldugu paket türü, veri tipi object (Standart - Basic - Premium)
3.  Contract Length -> müşterinin sözleşme süresi, veri tipi object (Annual - Monthly - Quarterly)
4. Age -> müşterinin yaşını, veri tipi float
5. Tenure -> müşterinin geçirdiği süre, veri tipi float
6. Usage Frequency -> müşterinin kullanım sıklığı, veri tipi float
7. Support Calls -> müşterinin görüşme sayısı, veri tipi float
8. Payment Delay -> müşterinin ödemede geçikme sayısı, veri tipi float
9. Total Spend -> müşterinin toplam harcama miktarı, veri tipi float
10. Last Interaction -> müşterinin son etkileşiminden sonra geçen süre, veri tipi float
11.  Churn -> müşteri kaybı, veri tipi float


**Sonuçlar:**

~Cinsiyetin abonelik türü seçiminde belirgin bir fark yaratmadığı görülüyor. Bu da abonelik türlerinin cinsiyetten bağımsız olarak tercih edildiğini gösteriyor. 

~Cinsiyet, sözleşme süresi tercihlerinde farklılık yaratıyor. Erkekler yıllık sözleşme tercihi yaparken, kadınlar daha çok aylık sözleşmeleri tercih ediyor. 

~ Kadın müşterilerin daha fazla kaybolduğu gözlemi, kadın müşteri kayıplarını hedef alacak özel stratejilerin geliştirilmesi gerektiğini gösteriyor.

~ Sözleşme süresi ve abonelik türü arasında belirgin bir ilişki var. Yıllık sözleşme, daha çok Standart abonelikle tercih edilirken, aylık sözleşme Premium abonelikle tercih ediliyor.

~ Yıllık ve üç aylık sözleşme türündeki müşteriler, aylık sözleşmeli müşterilere kıyasla daha yüksek harcama yapma eğilimindedir.

~  Yıllık ve üç aylık sözleşmelerin müşterileri, daha uzun süreli müşterilerdir. Aylık sözleşme genellikle daha kısa süreli müşterilerle ilişkilidir.

~ Aylık sözleşmeli müşterilerin tamamı kaybedilmektedir, bu da aylık sözleşme türünde ciddi bir müşteri kaybı riski olduğunu gösteriyor. Yıllık ve üç aylık sözleşme türlerinde ise müşteri kaybı oranı daha dengeli.

~ Müşterilerin çoğu orta yaşlarda ve uzun süreli abonelikler tercih ediyor. Yaşın, müşteri kaybı ve diğer özelliklerle ilişkilendirilmesi faydalı olabilir.

~ Müşteri desteği çağrı sayısının fazla olması, müşteri memnuniyeti ile ilgili bir sorun olabilir. Bu da müşteri kaybını tahmin etmek için önemli bir faktör olabilir.


**İşlemler:**
1. Customer Churn Veri Seti
2. Veri Seti Hazırlığı
   2. 1. NaN değerler yaratma
3. Veri Seti İnceleme
4. Eksik Veri Analizi
5. Eksik Verilerin Silinmesi ve Doldurulması
   5. 1. Kategorik Değişken Analizi - Eksik veri Silme ve oldurma
   5. 2. Numerik Değişken Analizi - Eksik Veri Silme ve Doldurma
6. Değişken Analizleri
7. Feature Engineering
8. Sonuçlar ve Öneriler

**Kütüphaneler:**

pandas 

numpy

matplotlib

seaborn

missingno

Kaggle: https://www.kaggle.com/meltemaltnkaynak

