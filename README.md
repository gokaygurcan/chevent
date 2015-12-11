# chevent - etkinlik takipçisi

Chevent bir gece projesi olarak, Türkiye'deki web ve yazılım etkinliklerini takip etmeyi kolaylaştırmak için oluşturulmuştur.

![Chevent](https://raw.githubusercontent.com/codeui/chevent/master/screenshot.png)

## Etkinlik Eklemek

- Bu repository'yi forklayın
- events/events.json dosyasına etkinliği ekleyin

```javascript
{
  "name": "",        // (String)  (Zorunlu)   Etkinlik ismi
  "date": "",        // (String)  (Zorunlu)   Etkinliğin gerçekleşeceği tarih (gg.aa.yyyy)
  "free": true,      // (Boolean) (Zorunlu)   Etkinlik ücretsiz ise `true`, değilse `false` girin
  "image": "",       // (String)  (Zorunlu)   Etkinliğin görseli
  "url": "",         // (String)  (Zorunlu)   Kayıt ve detaylı bilgilerin bulunduğu link
  "description": "", // (String)  (Zorunlu)   Etkinlik hakkında birkaç cümleyi geçmeyecek açıklama
  "quota": "",       // (Number)  (Opsiyonel) Etkinlikte katılımcı sınırı var mı? Varsa kaç kişi?
  "speakers": [      // (Array)   (Opsiyonel) Konuşmacı listesi ve konu başlıkları
    {
      "name": "",    // (String)  (Zorunlu)   Konuşmacının ismi
      "subject": "", // (String)  (Opsiyonel) Konu başlığı
    },
    ...
  ],
  "location": {      // (Object)  (Opsiyonel) Etkinliğin yapılacağı yere ait konum bilgisi
    "latitude": 0.0  // (Number)  (Zorunlu)   Enlem
    "longitude": 0.0 // (Number)  (Zorunlu)   Boylam
  }
},
...
```

- Pull request gönderin

## Chevent Repository'leri

- [Web](https://github.com/codeui/chevent-web)
- [Android](https://github.com/codeui/chevent-android)
- [iOS](https://github.com/codeui/chevent-ios)
- [Windows Phone](https://github.com/codeui/chevent-windows10)
- [Chrome & Opera Ext.](https://github.com/codeui/chevent-chrome)
- [Mozilla Ext.](https://github.com/codeui/chevent-mozilla)
- [CLI](https://github.com/codeui/chevent-js-cli)

## Katkıda Bulunanlar

* Eser Özvataf
* Coşku Demirhan
* Samet Aydemir
* Enes Erdoğan
* Önder Özcan
* Arda Kılıçdağı
* Vedat Mahir Yılmaz
* Rameş Aliyev
* Gökhan Karadaş
