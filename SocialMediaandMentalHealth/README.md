# Proje: Sosyal Medya ve Zihinsel Sağlık Analizi

**Tarih:** 2025-11-09

---

## 1. Amaç ve Kapsam

Bu projenin temel amacı, sosyal medya kullanım alışkanlıkları, yaşam tarzı faktörleri (egzersiz gibi) ve bireylerin zihinsel sağlık göstergeleri (stres, mutluluk, uyku kalitesi) arasındaki ilişkiyi analiz etmektir. Analiz, hangi alışkanlıkların zihinsel sağlığı olumlu veya olumsuz etkilediğini ortaya koymayı hedefler.

## 2. Veri Kaynağı

*   **Veri Seti:** `Mental_Health_and_Social_Media_Balance_Dataset.csv`
*   **Açıklama:** Veri seti, kullanıcıların yaş, cinsiyet, günlük ekran süresi, kullandıkları platform, uyku kalitesi, stres seviyesi, egzersiz sıklığı ve mutluluk endeksi gibi bilgilerini içeren anket tabanlı verilerden oluşmaktadır.

## 3. Yapılan Analizler ve Temel Bulgular

Analiz, `notebooks/` klasöründeki Jupyter Notebook dosyaları aracılığıyla gerçekleştirilmiştir. Sütun adları Türkçeleştirilerek daha anlaşılır analizler yapılmıştır.

### Temel Bulgular:

1.  **Korelasyon Analizi:**
    *   Haftalık egzersiz sıklığı ile stres seviyesi arasında negatif bir korelasyon tespit edildi (**-0.39**). Bu, **daha fazla egzersizin daha az stresle ilişkili olduğunu** göstermektedir.
    *   Ekran süresi ile mutluluk endeksi arasında da negatif bir ilişki gözlemlendi.

2.  **"Dijital Detoks" Etkisi:**
    *   Sosyal medyaya ara verilen gün sayısı arttıkça **mutluluk endeksinin yükseldiği** ve **stres seviyesinin düştüğü** gözlemlendi. Bu, dijital detoksun zihinsel sağlık üzerinde olumlu bir etkisi olduğunu güçlü bir şekilde desteklemektedir.

3.  **"Riskli" ve "Sağlıklı" Yaşam Tarzı Profilleri:**
    *   Yüksek ekran süresi, düşük uyku kalitesi ve az egzersiz yapanlar **"Riskli Profil"** olarak tanımlandı.
    *   Düşük ekran süresi, yüksek uyku kalitesi ve düzenli egzersiz yapanlar **"Sağlıklı Profil"** olarak tanımlandı.
    *   İki profil karşılaştırıldığında, **"Sağlıklı Profil"** grubunun **stres seviyesinin belirgin şekilde daha düşük** ve **mutluluk endeksinin çok daha yüksek** olduğu ortaya çıktı. Bu, yaşam tarzı seçimlerinin zihinsel sağlık üzerindeki kritik etkisini vurgulamaktadır.

4.  **Cinsiyet ve Zihinsel Sağlık:**
    *   Cinsiyet grupları arasında mutluluk ve stres seviyelerinin dağılımları incelenerek farklılıklar analiz edildi.

## 4. Kullanılan Teknolojiler ve Kütüphaneler

Proje, Python dilinde ve Jupyter Notebook ortamında geliştirilmiştir. Analiz ve görselleştirme için kullanılan temel kütüphaneler şunlardır:

*   `pandas`
*   `matplotlib`
*   `seaborn`

## 5. Nasıl Çalıştırılır? (Tekrarlanabilirlik)

1.  Bu proje klasörünün içindeyken bir sanal ortam oluşturun: `python -m venv venv`
2.  Sanal ortamı aktif edin: `source venv/bin/activate` (Mac/Linux) veya `venv\Scripts\activate` (Windows)
3.  Gerekli kütüphaneleri yükleyin: `pip install pandas matplotlib seaborn jupyter`
4.  Jupyter Notebook'u başlatın: `jupyter notebook`
5.  `notebooks/` klasöründeki `01_veri_temizligi_ve_analiz.ipynb` ve `02_gorsellestirme_ve_sonuc.ipynb` dosyalarını sırayla çalıştırın.