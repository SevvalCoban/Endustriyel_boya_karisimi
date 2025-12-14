<<<<<<< HEAD
# Genetik Algoritma ile Endüstriyel Boya Karışımı Optimizasyonu

## Proje Açıklaması

Bu proje, **Senaryo 2: Endüstriyel Boya Karışımı** problemini Genetik Algoritma (GA) kullanarak çözmektedir. Bir fabrika, iki tür pigment karışımıyla ideal renk yoğunluğunu yakalamak istemektedir.

## Problem Tanımı

### Amaç Fonksiyonu
$$y = 5x_1 + 2x_2 - x_1x_2$$

Bu fonksiyon renk kalitesi puanını temsil eder ve **maksimize edilmek** istenir.

### Değişkenler
- **x₁**: Pigment A oranı (%) → [0, 100]
- **x₂**: Pigment B oranı (%) → [0, 100]

### Kısıtlar
1. **x₁ + x₂ = 100** (Karışım toplamı %100 olmalı)
2. **x₁ ≥ 30** (A pigmenti asgari %30 kullanılmalı)

## Çözüm Yaklaşımı

Bu problem, doğal seçilim ve genetik operasyonları taklit eden **Genetik Algoritma** yöntemi ile çözülmüştür.

### Genetik Algoritma Bileşenleri

1. **Popülasyon Tanımı**: Her birey [x₁, x₂] formatında bir çözüm adayını temsil eder
2. **Uygunluk Fonksiyonu**: Amaç fonksiyonu direkt olarak fitness değeri olarak kullanılır
3. **Seçilim**: Turnuva seçilimi uygulanır
4. **Çaprazlama (Crossover)**: Ağırlıklı ortalama ile yeni bireyler oluşturulur
5. **Mutasyon**: Rastgele değişikliklerle genetik çeşitlilik sağlanır
6. **Elitizm**: En iyi bireyler bir sonraki nesle aktarılır

## Kurulum ve Çalıştırma

### Gereksinimler

Bu proje aşağıdaki Python kütüphanelerini gerektirir:

```bash
numpy
matplotlib
pandas
```

### Kurulum

1. Projeyi klonlayın veya indirin
2. Gerekli kütüphaneleri yükleyin:

```bash
pip install numpy matplotlib pandas
```

### Çalıştırma

1. Jupyter Notebook'u başlatın:

```bash
jupyter notebook
```

2. `genetik_algoritma_boya_karisimi.ipynb` dosyasını açın
3. Tüm hücreleri sırayla çalıştırın (Cell → Run All)

## Dosya Yapısı

```
ödev1/
│
├── genetik_algoritma_boya_karisimi.ipynb  # Ana notebook dosyası
└── README.md                               # Bu dosya
```

## Algoritma Parametreleri

- **Popülasyon Boyutu**: 50
- **Nesil Sayısı**: 100
- **Crossover Oranı**: 0.8
- **Mutasyon Oranı**: 0.1
- **Elitizm Oranı**: 0.1

## Sonuçlar

Notebook çalıştırıldığında:

1. **Optimal Çözüm**: Genetik algoritma tarafından bulunan en iyi pigment karışım oranları
2. **Görselleştirmeler**:
   - Fitness değerlerinin evrimi grafiği
   - Amaç fonksiyonunun 3D ve 2D görselleştirmeleri
   - Kısıtlar ve optimal çözüm görselleştirmesi
3. **Analiz**: Bulunan çözümün teorik optimal çözümle karşılaştırılması

## Özellikler

- ✅ Kısıtları sağlayan çözümler üretir
- ✅ Detaylı görselleştirmeler içerir
- ✅ Her adımda açıklamalar ve yorumlar bulunur
- ✅ Test fonksiyonları ile doğrulama yapılır
- ✅ Matematiksel analiz ve yorumlar içerir

## Notlar

- Algoritma, rastgele sayı üretimi için seed değeri kullanır (sonuçların tekrarlanabilir olması için)
- Tüm kısıtlar otomatik olarak kontrol edilir ve sağlanır
- Notebook içinde her adım detaylı olarak açıklanmıştır

## Lisans

Bu proje eğitim amaçlıdır.

=======
# End-striyel_boya_kar-m-
>>>>>>> c1cde135c371c207211eb82b4d08f86c38385801
