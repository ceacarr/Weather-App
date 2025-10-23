React Hava Durumu Uygulaması (Weather App)
Bu proje, React ve Vite kullanılarak geliştirilmiş, OpenWeatherMap API'den gerçek zamanlı hava durumu verilerini çeken basit ve dinamik bir hava durumu uygulamasıdır.
Uygulama, hava durumuna bağlı olarak arka plan rengini dinamik olarak değiştirebilme özelliğine sahiptir.

-Özellikler
Gerçek Zamanlı Veri Çekme: OpenWeatherMap API ile güncel hava durumu verilerini (sıcaklık, nem, rüzgar hızı) gösterir.
Dinamik Tema: Hava durumuna (güneşli, yağmurlu, karlı, gece) göre tüm sayfanın arka plan rengini otomatik olarak değiştirir.
Arama Fonksiyonu: Kullanıcının istediği şehri arayabilmesi için basit bir arama çubuğu içerir.
Modern Teknoloji: React, Vite ve temiz CSS (Tailwind kullanılmadan) ile geliştirilmiştir.

- Kullanılan Teknolojiler
React 
Vite 
JavaScript (ES6+)
CSS3
OpenWeatherMap API 




weather-app/
├── public/
├── src/
│   ├── assets/              # Simgeler, resimler vb.
│   ├── components/
│   │   ├── Weather.jsx      # Ana iş mantığı ve API çağrısı
│   │   └── Weather.css
│   ├── App.jsx              # Ana bileşen
│   ├── main.jsx             # React uygulamasının başlangıç dosyası
│   └── index.css            # Genel (body) CSS stilleri ve dinamik temalar
├── .env                     # API anahtarının bulunduğu dosya
├── package.json
└── vite.config.js
