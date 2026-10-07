# 🏀 Potaya Smaç

Flappy Bird tarzında basit bir tarayıcı oyunu. Ekrandaki basketbol topuna
tıklayarak (veya dokunarak / boşluk tuşuyla) zıplatıyorsun, amaç topu
havada asılı duran pota benzeri çemberlerin içinden geçirmek.

Tek bir `index.html` dosyasından oluşan, kurulum gerektirmeyen saf
HTML5 Canvas + JavaScript oyunu.

## Nasıl oynanır

- **Tıkla / Dokun / Boşluk tuşu** → top zıplar
- Topu, ilerleyen çemberlerin içinden geçirmeye çalış
- Bir çemberden geçemezsen (çembere tamamen ıskalarsan) oyun biter
- **Çarpan sistemi:** çembere hiç değmeden, tam temiz geçersen çarpanın
  (x1, x2, x3 …) bir artar ve her temiz geçişte skora daha fazla puan
  eklenir. Çemberin kenarına sürtersen de geçersin ama çarpan x1'e sıfırlanır
- En yüksek skorun tarayıcında saklanır (Rekor)

## Nasıl çalıştırılır

Harici bir kurulum veya sunucu gerekmiyor. `index.html` dosyasını indirip
çift tıklayarak doğrudan tarayıcıda açabilirsin, ya da bu depoda
GitHub Pages aktifse [buradan](index.html) oynayabilirsin.

## Teknoloji

- Saf HTML5 Canvas + JavaScript (framework/kütüphane yok)
- Skor kaydı için `localStorage`

## Yapay zeka kullanımı hakkında

Bu proje, [Claude](https://claude.com) (Anthropic) ile birlikte
geliştirilmiştir. Oyunun kodu, fizik mantığı ve görselleri büyük ölçüde
yapay zeka desteğiyle oluşturuldu; fikir, yönlendirme ve test etme
tarafımdan yapıldı. Bunu burada belirtmeyi, sürecin şeffaf olması
açısından önemli buluyorum.
