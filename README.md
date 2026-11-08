# Birim Küp | 3B Uzamsal Algı Eğitim Tahtası

Birim Küp ile 3 Boyutlu Düşünme Eğitim Programı kapsamında geliştirilen web tabanlı öğretmen uygulamasıdır.

https://mehmetdoqan.github.io/3BUzamsalAlgi/

## 🎯 Projenin Amacı

Çocukların fiziksel birim küplerle gerçekleştirecekleri etkinlikleri desteklemek ve üç boyutlu uzamsal algı becerilerini geliştirmeye yönelik görev modelleri hazırlamak.

## ✨ Özellikler

- 5×5 dijital çalışma tahtası
- 1×1×1 cm birim küp sistemi
- 5 farklı küp rengi
- Küpleri üst üste yerleştirme
- 10 seviye ve her seviyede 20 görev
- Her görev için bağımsız küp modeli
- Görev değişikliklerini otomatik olarak tarayıcı hafızasında saklama
- Tüm görevleri JSON formatında kaydetme ve yükleme
- Koordinat Oyunu

## 📁 Dosya Yapısı

```text
repository/
├── index.html
├── level.json
└── README.md
```

## 🚀 Kullanım

Uygulama GitHub Pages üzerinden çalıştırılabilir.

1. Repository içerisine `index.html` ve `level.json` dosyalarını yükleyin.
2. GitHub Pages özelliğini etkinleştirin.
3. Oluşan web sayfasını açın.

Uygulama açıldığında `level.json` dosyasını otomatik olarak yüklemeye çalışır.

JSON dosyası bulunamazsa 10 seviye ve 200 boş görev oluşturulur.

## 💾 Veri Kaydetme Sistemi

- Yapılan değişiklikler tarayıcının yerel hafızasına otomatik kaydedilir.
- Her görev kendi modelini bağımsız olarak saklar.
- **JSON'a Kaydet** işlemi tüm seviyeleri ve görevleri tek bir JSON dosyasına aktarır.
- **JSON Yükle** işlemi daha önce kaydedilmiş görevleri geri yükler.

**Önemli:** GitHub Pages üzerinden JSON dosyası doğrudan değiştirilemez. İndirilen yeni `level.json` dosyası repository içerisine yüklenerek eski dosyanın yerine geçirilmelidir.

## 🧩 Eğitim Yaklaşımı

Dijital uygulama öğretmen tarafından yönetilir. Öğretmen dijital tahtada üç boyutlu modeller oluşturur ve bu modelleri öğrencilere sunar. Öğrenciler ise fiziksel tahta ve birim küpleri kullanarak modelleri oluşturmaya çalışır.

## 🛠️ Teknolojiler

- HTML
- CSS
- JavaScript
- JSON
- Browser Local Storage

---

**Proje:** Birim Küp ile 3 Boyutlu Düşünme Eğitim Programı  
**Uygulama:** Birim Küp 3B Uzamsal Algı Eğitim Tahtası
