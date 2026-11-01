KT FITNESS – ÖĞÜN TAKİPLİ GÜNCEL SÜRÜM

DOSYALAR
index.html, style.css, app.js, manifest.json, sw.js

GÜNCEL ÖZELLİKLER
- Siyah/gri/turuncu mobil uyumlu arayüz
- Haftalık ağırlık antrenmanı planı ve egzersiz başına kilo kaydı
- Antrenman, kardiyo, karın ve günlük makro hedefi tamamlandı işaretleri
- Su takibi ve kişisel su hedefi
- Günlük öğün planı: sabah, öğle, ara öğün ve akşam; saat, yiyecek açıklaması ve günlük tamamlandı tikleri
- Tarihe göre son 7 günlük öğün takip geçmişi
- Su/öğün/antrenman bildirim denemeleri (uygulama açıkken)
- Cihaz içi kural tabanlı gelişim değerlendirmesi
- Kilo/çevre ölçümleri ve fotoğraflar
- JSON yedekleme ve geri yükleme
- Çevrimdışı PWA önbelleği

GÜNCELLEME
GitHub deposundaki aynı isimli dosyaları bu ZIP içindekilerle değiştirin. Dosyaları ZIP olarak değil, ZIP'ten çıkarıp tek tek depo kök dizinine yükleyin. Commit edin. GitHub Pages aynı adres üzerinden güncellenecektir.

ÖNEMLİ SINIRLAMALAR
- Veriler tarayıcının yerel depolamasında saklanır; GitHub'a yüklenmez. Tarayıcı verileri silinirse kayıtlar kaybolabilir. Düzenli JSON yedeği alın.
- Fotoğraflar JSON yedeğine dahil değildir; fotoğrafları ayrıca saklayın.
- iPhone web uygulamalarında arka planda kesin saatli yerel bildirim garantisi yoktur. Bu sürüm hatırlatmaları uygulama açıkken kontrol eder. Güvenilir arka plan bildirimleri için ayrıca sunucu/push altyapısı gerekir.
- “Akıllı değerlendirme” bu sürümde çevrimdışı, kural tabanlı özet üretir; gerçek üretken yapay zekâ değildir. Gerçek AI entegrasyonu için güvenli bir sunucu/API ve olası kullanım maliyeti gerekir.
