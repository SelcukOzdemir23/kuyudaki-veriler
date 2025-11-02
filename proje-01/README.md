# Proje: ABD'de Sünnet Oranlarının Coğrafi Dağılımı

**Tarih:** 2025-11-02

---

## 1. Amaç ve Kapsam

Bu analizin temel amacı, ABD eyaletleri arasındaki sünnet oranlarının coğrafi dağılımını ve bu dağılımın sosyo-ekonomik göstergelerle olan potansiyel ilişkisini ortaya çıkarmaktır.

## 2. Veri Kaynağı

* **Veri Seti:** "US Circumcision Rates by State"
* **Kaynak Linki:** [Buraya veri kaynağının linki gelecek]
* **Açıklama:** Bu veri seti, ABD'nin farklı eyaletlerindeki erkek sünnet oranlarını içermektedir.

## 3. Temel Bulgular ve Görselleştirme

Analiz sonucunda ulaşılan en çarpıcı bulgu, sünnet oranlarının batı ve kuzeydoğu eyaletlerinde daha düşük, orta batı ve güney eyaletlerinde ise daha yüksek olduğudur.

Bu bulguyu en iyi özetleyen görsel aşağıdadır:

![Dağılım Haritası](assets/dagilim_haritasi.png)

## 4. Kullanılan Teknolojiler ve Kütüphaneler

Bu analizi çalıştırmak için gereken temel bağımlılıklar `requirements.txt` dosyasında belirtilmiştir.

* `pandas`
* `matplotlib`
* `seaborn`

## 5. Nasıl Çalıştırılır? (Tekrarlanabilirlik)

1.  Bu proje klasörünün içindeyken bir sanal ortam oluşturun: `python -m venv venv`
2.  Aktif edin: `source venv/bin/activate` (Mac/Linux) veya `venv\Scripts\activate` (Windows)
3.  Bağımlılıkları yükleyin: `pip install -r requirements.txt`
4.  `notebooks/` klasöründeki Jupyter Notebook dosyalarını sırayla çalıştırın.
