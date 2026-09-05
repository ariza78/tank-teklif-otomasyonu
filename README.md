# 🚀 Tank İmalatı Yapay Zeka Teklif Otomasyonu

Bu depo, paslanmaz ve siyah sac tank imalatı süreçlerinde teknik verileri toplama, maliyet/BOM analizi çıkarma ve nihai teklif dosyası oluşturma adımlarını yöneten yapay zeka sistem talimatlarını içerir.

---

## 🔄 ÇALIŞTIRMA ADIMLARI (ÇALIŞMA AKIŞI)

### 1. Adım: Teknik Veri Toplama
1. `prompts/01_teknik_veri_toplama.txt` dosyasının içeriğini kopyalayın.
2. Yapay zekaya yapıştırın.
3. Yapay zekanın sırayla soracağı soruları yanıtlayın.
4. Süreç sonunda üretilen **Teknik Özet ve BOM Listesi** çıktısını kopyalayın.

### 2. Adım: Maliyet Araştırması ve BOM Analizi
1. Yeni bir sohbet başlatın.
2. `prompts/02_maliyet_ve_bom_analizi.txt` dosyasının içeriğini kopyalayıp yapay zekaya verin.
3. Yapay zeka hazır olduğunu belirttiğinde, **1. Adımdan aldığınız çıktıyı** yapıştırın.
4. Süreç sonunda üretilen **Maliyet Analiz Tablosu** verisini kopyalayın.

### 3. Adım: Kâr Oranı ve Resmi Teklif Oluşturma
1. Yeni bir sohbet başlatın.
2. `prompts/03_teklif_ve_kar_hesabi.txt` dosyasının içeriğini kopyalayıp yapay zekaya verin.
3. Yapay zeka hazır olduğunu belirttiğinde, **2. Adımdan aldığınız maliyet tablosunu** yapıştırın.
4. Yapay zekanın soracağı **Kâr Oranı (%)** bilgisini girin.
5. Oluşan **Nihai Teklif Metni** çıktısını müşterinize iletin.

