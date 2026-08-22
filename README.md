# Single Page CV Project

Bu proje, yalnızca HTML kullanılarak hazırlanmış tek sayfalık bir özgeçmiş uygulamasıdır. Herhangi bir paket kurulumu, derleme işlemi veya sunucu tarafı teknoloji gerektirmez.

## Proje yapısı

```text
SinglePageCVProject/
├── index.html    # Özgeçmiş sayfası
├── favicon.png   # Tarayıcı sekmesinde gösterilen favicon
└── README.md     # Proje açıklaması ve çalıştırma talimatları
```

## Gereksinimler

Projeyi çalıştırmak için güncel bir web tarayıcısı yeterlidir:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

## Projeyi çalıştırma

### 1. Doğrudan tarayıcıda açma

Projeyi bilgisayarına indirdikten veya klonladıktan sonra proje klasöründeki `index.html` dosyasına çift tıkla. Sayfa varsayılan tarayıcında açılacaktır.

### 2. Visual Studio Code ile çalıştırma

Proje klasörünü Visual Studio Code ile aç:

```bash
code .
```

Ardından `index.html` dosyasını aç. Live Server eklentisi kuruluysa dosyaya sağ tıklayıp **Open with Live Server** seçeneğini kullanabilirsin.

### 3. Yerel HTTP sunucusu ile çalıştırma

Bilgisayarında Python kuruluysa proje klasöründe aşağıdaki komutu çalıştır:

```bash
python -m http.server 5500
```

Daha sonra tarayıcıdan şu adresi aç:

```text
http://localhost:5500
```

Sunucuyu durdurmak için terminalde `Ctrl + C` tuşlarına bas.

## Özelleştirme

- Kişisel bilgiler, eğitim ve deneyim alanları `index.html` içinden düzenlenebilir.
- Tarayıcı sekmesindeki ikon `favicon.png` dosyası değiştirilerek güncellenebilir.
- Renkler, ilgili HTML elemanlarının `style` özelliklerinden değiştirilebilir.

## Kullanılan teknolojiler

- HTML5
