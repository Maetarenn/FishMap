🐟 FishMap

FishMap, dünya genelindeki balık türlerinin gerçek bilimsel veriler kullanılarak harita üzerinde görselleştirilmesini amaçlayan, tamamen frontend tabanlı bir web projesidir.

Proje, OBIS (Ocean Biodiversity Information System) açık verilerini kullanarak balık türlerinin coğrafi dağılımını ve yoğunluklarını interaktif bir harita üzerinde göstermeyi hedefler.

🚀 Özellikler

🌍 Dünya genelinde balık gözlemleri

🗺️ Etkileşimli harita (Leaflet + OpenStreetMap)

🔍 Balık türünü yazarak arama (seçenek listesi yok)

📊 Gerçek verilere dayalı yoğunluk analizi

🌊 Bölgesel filtreleme (Dünya, Karadeniz, Ege, Akdeniz)

📡 Açık veri kaynağı – API key gerektirmez

🎨 Modern ve sade UI (Tailwind CSS)

🧠 Veri Kaynağı

Bu projede kullanılan tüm biyolojik gözlem verileri:

OBIS – Ocean Biodiversity Information System
🔗 https://obis.org

OBIS, dünya genelinde deniz canlılarına ait açık ve ücretsiz bilimsel veriler sunar.

🛠️ Kullanılan Teknolojiler

HTML5

Tailwind CSS

Vanilla JavaScript

Leaflet.js

OpenStreetMap

OBIS Public API

⚙️ Nasıl Çalışır?

Kullanıcı balık türünü yazarak girer (örn: hamsi)

Sistem, balık adını bilimsel (Latin) adına çevirir

OBIS API üzerinden ilgili türün gözlem verileri çekilir

Veriler harita üzerinde noktasal olarak gösterilir

Gözlem sayısına göre yoğunluk seviyesi hesaplanır

📌 Örnek Balık Türleri

(Şu an tanımlı olanlar)

Hamsi → Engraulis encrasicolus

Lüfer → Pomatomus saltatrix

Palamut → Sarda sarda

Orkinos → Thunnus thynnus

Somon → Salmo salar

🧪 Projenin Amacı

Bu proje:

Eğitim

Açık veri farkındalığı

Deniz biyolojisi ve harita tabanlı görselleştirme

amaçlarıyla geliştirilmiştir.

Ticari bir kullanım hedeflemez.

⚠️ Notlar

Veriler gerçek gözlem noktalarıdır, tahmin değildir.

Yoğunluk hesaplaması gözlem sayısına dayalıdır.

Proje tamamen client-side çalışır.
