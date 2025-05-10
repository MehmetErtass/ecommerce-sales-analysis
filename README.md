# Ecommerce Sales Analysis and Forecasting

## Proje Açıklaması
Bu proje, bir e-ticaret veri setini analiz etmek ve gelecekteki satışları tahmin etmek amacıyla hazırlanmıştır. Proje, verilerin temizlenmesi, keşifsel veri analizi (EDA), RFM segmentasyonu ve satış tahmini süreçlerini içermektedir. Son olarak, satış tahminleri Power BI görselleştirmeleri ile raporlanmıştır.

## Kullanılan Teknolojiler
- **Python**: Veri işleme, analiz ve modelleme için
- **Pandas, Numpy, Matplotlib, Seaborn**: Veri analizi ve görselleştirme
- **Statsmodels, Prophet**: Zaman serisi tahminleme
- **Power BI**: Görselleştirme ve raporlama
- **Jupyter Notebooks**: Veri analizi ve modelleme

## Proje Adımları
1. **Veri Temizleme**: Online retail verisi üzerinde eksik ve hatalı verilerin temizlenmesi.
2. **Keşifsel Veri Analizi (EDA)**: Verinin temel özellikleri ve dağılımı üzerine yapılan analizler.
3. **RFM Segmentasyonu**: Müşteri segmentasyonu için RFM analizi yapılarak, kullanıcılar segmentlere ayrıldı.
4. **Satış Tahmini**: Prophet modelini kullanarak gelecek 6 ay için satış tahminleri yapıldı.
5. **Power BI Görselleştirmeleri**: Satış verileri üzerine yapılan analizlerin görselleştirilmesi ve raporlanması.

## Veri Seti
Bu projede kullanılan veri seti, bir e-ticaret mağazasının satış verilerini içermektedir. Veri, aşağıdaki özelliklere sahiptir:
- **InvoiceNo**: Fatura numarası
- **StockCode**: Ürün kodu
- **Description**: Ürün açıklaması
- **Quantity**: Satılan ürün adedi
- **InvoiceDate**: Fatura tarihi
- **UnitPrice**: Ürün birim fiyatı
- **CustomerID**: Müşteri kimliği
- **Country**: Ülke

Veri setine `data/online_retail.csv` yolundan erişilebilir.

## Nasıl Çalıştırılır?
Bu projeyi çalıştırmak için aşağıdaki adımları takip edebilirsiniz:
1. **Gerekli Kütüphaneleri Yükleyin**:
    ```bash
    pip install -r requirements.txt
    ```
2. **Veri Setini İndirin**: `data/` klasörüne `online_retail.csv` dosyasını ekleyin.
3. **Notebooks Klasöründeki Adımları Çalıştırın**:
    - `01_data_cleaning.ipynb`: Veri temizliği ve hazırlık
    - `02_eda.ipynb`: Keşifsel veri analizi
    - `03_rfm_segmentation.ipynb`: RFM segmentasyonu ve segment analizi
    - `04_sales_forecasting.ipynb`: Prophet ile satış tahmini
4. **Çıktıları Görüntüleyin**: Çıktılar `outputs/` klasöründe yer alır. Ayrıca görseller `visuals/` klasöründe mevcuttur.

## Gerekli Kütüphaneler
Aşağıdaki Python kütüphanelerine ihtiyaç duyulmaktadır:
- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- prophet
- scikit-learn
- jupyter

## Sonuçlar ve Görselleştirmeler
Proje sonunda elde edilen önemli sonuçlar şunlardır:
- **RFM Segmentasyonu**: Müşteri grupları belirlenmiş ve her segment için satış davranışları analiz edilmiştir.
- **Satış Tahminleri**: Gelecek 6 ay için yapılan satış tahminleri.
- **Power BI Görselleştirmeleri**: Satışlar, ürünler ve ülkeler bazında çeşitli görselleştirmeler sunulmuştur.

Görselleştirmelere `visuals/` klasöründen ulaşabilirsiniz.

## Lisans
Bu proje MIT Lisansı ile lisanslanmıştır.
