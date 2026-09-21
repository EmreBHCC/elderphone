# RULES.md

Bu dosya, projede uyulması gereken kuralları ve kararları listeler. Yeni bir kural belirlendiğinde buraya eklenir.

## Format

- **Kural:** ne yapılması/yapılmaması gerektiği. **Neden:** gerekçesi. **Kapsam:** nereyi ilgilendirdiği.

## Kurallar

- **Kural:** Yazılan her kod için test yazılmalı. **Neden:** Değişikliklerin doğruluğunun kanıtlanması ve regresyonların önlenmesi. **Kapsam:** Tüm kod değişiklikleri.
- **Kural:** Yazılan hiçbir kod çalıştırılmadan/doğrulanmadan tamamlanmış sayılmamalı; boşuna öylece bırakılmamalı. **Neden:** Çalışmayan veya doğrulanmamış kodun "tamam" olarak bırakılması güven kaybına ve gizli hatalara yol açar. **Kapsam:** Tüm kod değişiklikleri, tamamlanma iddiasından önce.
- **Kural:** Performans her zaman öncelikli bir tasarım kriteri olarak değerlendirilmeli. **Neden:** Kullanıcı deneyimi ve sistem verimliliği için kritik. **Kapsam:** Mimari kararlar ve implementasyon detayları.
- **Kural:** Kullanıcı arayüzüne öncelik verilmeli; arayüz sade, göz yormayan ama şık olmalı. **Neden:** Kullanılabilirlik ve kullanıcı memnuniyeti. **Kapsam:** Tüm arayüz/UI çalışmaları.
- **Kural:** Temel md dosyaları (`CLAUDE.md`, `ARCHITECTURE.md`, `ROOTS.md`, `RULES.md`, `LESSONS.md`, `CHANGELOG.md`, `NOTES.md`) her zaman güncel tutulmalı ve ilgili yerlerde birbirine geri bağlantı (link) verilmeli. **Neden:** Dokümantasyonun dağılmadan, tutarlı ve izlenebilir kalması. **Kapsam:** Tüm dosya/karar/değişiklik işlemleri.
- **Kural:** Her commit Emre'nin kimliğiyle atılır; `Co-Authored-By: Claude` satırı aksi açıkça söylenmedikçe asla eklenmez. **Neden:** Katkı grafiğinde ajan görünmemeli. **Kapsam:** Bu repodaki tüm git commit'leri.

## İlgili Dosyalar

[CLAUDE.md](CLAUDE.md) · [ARCHITECTURE.md](ARCHITECTURE.md) · [ROOTS.md](ROOTS.md) · [LESSONS.md](LESSONS.md) · [CHANGELOG.md](CHANGELOG.md) · [NOTES.md](NOTES.md)
