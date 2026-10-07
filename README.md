# 🏀 Potaya Smaç

Topu geri çekip bırakarak oynanan bir "dunk shot" tarzı tarayıcı oyunu. Her
atışta top bir yay çizerek bir sonraki havada asılı çembere uçar; kamera
yukarı doğru tırmanarak seni takip eder.

Tek bir `index.html` dosyasından oluşan, kurulum gerektirmeyen saf
HTML5 Canvas + JavaScript oyunu.

## Nasıl oynanır

- Topu **tutup geri çek ve bırak** — tuttuğun yönün tersine, bir sapan gibi
  fırlar ve yerçekimiyle yay çizerek bir sonraki çembere uçar
- Çemberin tam ortasından, hiç değmeden geçersen **çarpanın** (x1, x2, x3 …)
  bir artar ve skora daha fazla puan eklenir
- Çemberin kenarına sürtersen de geçersin ama çarpan x1'e sıfırlanır
- Bir çemberi tamamen kaçırırsan (içinden geçemezsen) oyun biter ve skorun gösterilir
- En yüksek skorun tarayıcında saklanır (Rekor)

## Nasıl çalıştırılır

Harici bir kurulum veya sunucu gerekmiyor. `index.html` dosyasını indirip
çift tıklayarak doğrudan tarayıcıda açabilirsin, ya da bu depoda
GitHub Pages aktifse [buradan](index.html) oynayabilirsin.

## Teknoloji

- Saf HTML5 Canvas + JavaScript (framework/kütüphane yok)
- Basit parabolik atış fiziği (yerçekimi + sürükle-bırak ile hız vektörü)
- Skor kaydı için `localStorage`

## Yapay zeka kullanımı hakkında

Bu proje, [Claude](https://claude.com) (Anthropic) ile birlikte
geliştirilmiştir. Oyunun kodu, fizik mantığı ve görselleri büyük ölçüde
yapay zeka desteğiyle oluşturuldu; fikir, yönlendirme ve test etme
tarafımdan yapıldı. Bunu burada belirtmeyi, sürecin şeffaf olması
açısından önemli buluyorum.
