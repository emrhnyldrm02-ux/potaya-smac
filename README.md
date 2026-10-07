# 🏀 Potaya Smaç

Dokun-dokun-zıpla tarzında oynanan bir basketbol oyunu. Top yerçekimiyle
sürekli düşer; her dokunuşunda yukarı doğru sabit bir sıçrama yapar ve
otomatik olarak ileri doğru süzülür. Önünden gelen çemberlerin ortasından
geçerek puan topla, ıskalarsan suya düşersin.

Tek bir `index.html` dosyasından oluşan, kurulum gerektirmeyen saf
HTML5 Canvas + JavaScript oyunu.

## Nasıl oynanır

- Ekrana **dokun / tıkla** — top yukarı doğru sabit bir hızla zıplar,
  dokunmazsan yerçekimiyle düşmeye devam eder
- Önünden gelen çemberin tam ortasından, hiç değmeden geçersen
  **çarpanın** (x1, x2, x3 …) bir artar ve skora daha fazla puan eklenir
- Çemberin kenarına sürtersen de geçersin ama çarpan x1'e sıfırlanır
- Çemberi tamamen kaçırırsan (içinden geçemezsen) suya düşersin,
  "SPLASH" ekranı gösterilir ve oyun biter
- En yüksek skorun tarayıcında saklanır (Rekor)

## Nasıl çalıştırılır

Harici bir kurulum veya sunucu gerekmiyor. `index.html` dosyasını indirip
çift tıklayarak doğrudan tarayıcıda açabilirsin, ya da bu depoda
GitHub Pages aktifse [buradan](index.html) oynayabilirsin.

## Teknoloji

- Saf HTML5 Canvas + JavaScript (framework/kütüphane yok)
- Sürekli yerçekimi + dokunuşta sabit yukarı itiş fiziği, otomatik ileri
  kaydırmalı dünya ve kamera takibi
- Skor kaydı için `localStorage`

## Yapay zeka kullanımı hakkında

Bu proje, [Claude](https://claude.com) (Anthropic) ile birlikte
geliştirilmiştir. Oyunun kodu, fizik mantığı ve görselleri büyük ölçüde
yapay zeka desteğiyle oluşturuldu; fikir, yönlendirme ve test etme
tarafından yapıldı. Bunu burada belirtmeyi, sürecin şeffaf olması
açısından önemli buluyorum.
