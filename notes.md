# Dua Takip — Beyin Fırtınası

## Ne yapıyoruz?
Günlük sabah/akşam dualarını takip eden tek sayfa web uygulaması.

## Kullanıcı kim?
LumoSalab kendisi — kişisel kullanım, mobil öncelikli.

## Temel özellikler
- Sabah duaları listesi (önceden tanımlı)
- Akşam duaları listesi (önceden tanımlı)
- Her dua satırında: dua adı + tıklanabilir sayaç
- Günlük hedef belirleme (kaç defa okunacak)
- İlerleme çubuğu (toplam / hedef)
- Veri localStorage'da kalıcı
- Günlük sıfırlama butonu

## Mimari kararlar
- Tek HTML dosyası (inline CSS + JS) — basit tut
- Framework yok, vanilla JS yeterli
- Karanlık tema, minimalist
- Mobil uyumlu (responsive)
- Dua verileri JS içinde sabit dizi olarak

## Dua listesi (başlangıç)
### Sabah duaları
1. Sübhanallah (33x)
2. Elhamdülillah (33x)
3. Allahu Ekber (33x)
4. La ilahe illallah (1x)
5. Ayetel Kürsi (1x)
6. Sabah duası (1x)

### Akşam duaları
1. Sübhanallah (33x)
2. Elhamdülillah (33x)
3. Allahu Ekber (33x)
4. La ilahe illallah (1x)
5. Ayetel Kürsi (1x)
6. Akşam duası (1x)

## Tasarım notları
- Arka plan: koyu (#0d1117 gibi)
- Yazı: açık gri/beyaz
- Sayaç butonları: büyük, parmakla tıklanabilir
- İlerleme çubuğu: yeşil gradient
- Bölüm ayracı: sabah / akşam
