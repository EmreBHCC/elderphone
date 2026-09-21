# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Proje Durumu

Bu depo şu anda boş. Henüz kaynak kod, build/test yapılandırması ya da bir README bulunmuyor, bu yüzden bu dosyada komutlar veya mimari hakkında somut bilgi verilemiyor.

Proje ilerledikçe bu dosyayı şunlarla güncelleyin:

- **Komutlar**: build, lint, test (tek bir testi çalıştırma dahil), dev sunucusu başlatma gibi sık kullanılan komutlar.
- **Mimari**: birden fazla dosyaya bakmadan anlaşılamayacak üst düzey yapı — modüller arası veri akışı, katmanlar, önemli tasarım kararları.

## Depo Dokümantasyon Dosyaları

Bu depoda aşağıdaki takip dosyaları bulunur. Bir görev sırasında ilgili durum ortaya çıktığında bu dosyalar **okunmalı** ve **güncellenmelidir** — sadece varlıklarını bilmek yetmez, aktif olarak kullanılmalıdır.

- **`ARCHITECTURE.md`** — Projenin mimarisi: bileşenler, veri akışı, tasarım kararları. Mimariyi etkileyen bir değişiklik yapılmadan önce okunmalı; yeni bir mimari karar alındığında güncellenmelidir.
- **`ROOTS.md`** — Oluşturulan/oluşturulacak dosyaların yolları, amacı, nasıl yapıldığı ve kullanılan araçlar. Yeni bir dosya oluşturulduğunda buraya bir satır eklenmelidir.
- **`RULES.md`** — Projede uyulması gereken kurallar ve kararlar. Bir görev başlamadan önce okunmalı; kod/işlem bu kurallara uymalıdır. Kullanıcı yeni bir kural belirlediğinde buraya eklenmelidir.
- **`LESSONS.md`** — Alınan dersler ve yapılmaması gerekenler. Bir hata yapıldığında veya kullanıcı bir yaklaşımı reddettiğinde/onayladığında buraya kaydedilmeli; yeni bir işe başlamadan önce ilgili derslerin tekrarlanmaması için gözden geçirilmelidir.
- **`CHANGELOG.md`** — Yapılan değişikliklerin tarih sırasıyla kaydı. Anlamlı bir değişiklik (dosya oluşturma, düzenleme, kararlar) tamamlandığında tarih, değişiklik ve nedeniyle birlikte buraya eklenmelidir.
- **`NOTES.md`** — Serbest notlar, fikirler, hatırlatmalar. Geçici veya henüz karara bağlanmamış bilgiler burada tutulur.

Kural: Bu dosyalardan birine yazılacak bir bilgi ortaya çıktığında (yeni kural, alınan ders, mimari karar, yeni dosya, önemli değişiklik), işlemi tamamlamadan önce ilgili dosyayı güncelle. Bilgiyi sadece sohbet yanıtında bırakma.

## Temel Çalışma Kuralları

Bu kuralların tam listesi ve gerekçeleri [RULES.md](RULES.md) içinde tutulur; buradaki özet sadece hatırlatma amaçlıdır:

- Yazılan her kod için test yazılmalı.
- Hiçbir kod, çalıştırılıp doğrulanmadan tamamlanmış sayılmamalı.
- Performans, tasarım ve implementasyon kararlarında öncelikli kriterdir.
- Kullanıcı arayüzü sade, göz yormayan ama şık olmalı.
- Temel md dosyaları (aşağıdaki liste) her zaman güncel tutulmalı ve birbirine geri bağlantı vermelidir.

## İlgili Dosyalar

[ARCHITECTURE.md](ARCHITECTURE.md) · [ROOTS.md](ROOTS.md) · [RULES.md](RULES.md) · [LESSONS.md](LESSONS.md) · [CHANGELOG.md](CHANGELOG.md) · [NOTES.md](NOTES.md)
