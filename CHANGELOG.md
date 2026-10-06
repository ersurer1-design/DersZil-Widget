# Değişiklik Günlüğü

## v1.5.2

### Modern dış kontrol şeridi
- Menü düğmeleri widget gövdesinin dışına alınarak yuvarlak köşeli, gölgeli ve temayla uyumlu ayrı bir kontrol şeridine dönüştürüldü.
- Varsayılan konum **Üst** olarak değiştirildi.
- Ayarlar → Genel → Menü tuşları alanından **Üst / Alt / Sağ / Sol** konumu seçilebilir.
- Üst/Alt konumda kontrol şeridi widget gövdesiyle aynı genişliğe hizalanır.
- Sağ/Sol konumda kontrol şeridi dikey yerleşir ve gövde içeriğini kapatmaz.
- Düğmeler normal durumda yalnızca ikon olarak kompakt görünür.
- Fare ile üzerine gelindiğinde düğme yumuşak animasyonla genişler ve **Gizle / Mini Görünüm / Üstte Tut / Tema / Kazanım / Ayarlar / Kapat** gibi menü adını gösterir.
- Kontrol şeridi fare üzerine geldiğinde belirginleşir; ayrıldığında yeniden daha sakin bir görünüme döner.
- Koyu, Açık ve Gökkuşağı temaları için kontrol şeridi ayrı olarak renklendirildi.

### Animasyonlar
- Mini ↔ Tam görünüm geçişine yumuşak boyut animasyonu eklendi.
- Menü düğmelerine genişleme, metin belirme ve hafif ölçek animasyonu eklendi.
- Widget gövdesi ve kontrol şeridine daha yumuşak gölge/derinlik efekti eklendi.

### Gerçek Mini Görünüm
- Mini görünüm yalnızca ana durum başlığı ve geri sayım bilgisini içerir; kontrol düğmeleri dış şeritte kalır.
- Gün/saat, okul adı, ders saat aralığı, alt açıklama, sonraki ders satırı, ilerleme çubuğu ve kazanım alanı Mini Görünümde gizlenir.
- Mini içerik alanı yaklaşık 300 × 150 boyutundadır.

### Dağıtım ve çalışma davranışı
- Sistem tepsisi için DersZil'e özel zil temalı simge kullanılır.
- Yeni DersZil EXE açıldığında aynı Windows oturumunda açık olan eski DersZil örneği otomatik kapatılır.
- Böylece güncelleme sonrası iki widget'ın aynı anda açık kalması engellenir.


## v1.5.1

### Dağıtım ve güncelleme
- Genel GitHub dağıtım deposuna bağlanan güncelleme denetimi eklendi.
- Uygulama artık GitHub Releases içindeki en son sürümü kontrol edebiliyor.
- Yeni sürüm bulunduğunda sürüm notlarını gösterip indirme sayfasını açmayı teklif ediyor.

### v1.5 tabanı
- İlk kurulum sihirbazı eklendi.
- "Nasıl Kullanılır?" yardım merkezi eklendi.
- 3 dakikalık hızlı başlangıç rehberi eklendi.
- .dzw yedekleme ve geri yükleme eklendi.
- Hazırlayan/Hakkında bölümüne sürüm bilgisi ve güncelleme denetimi eklendi.
- Windows 10 / Windows 11 dağıtım yapısı netleştirildi.

### Önceki geliştirmeler
- DOCX/XLSX yıllık plan okuyucu geliştirildi.
- Farklı yıllık plan tasarımlarına uyarlanabilir sütun eşleştirme eklendi.
- Aynı haftadaki tüm kazanımların birlikte gösterimi eklendi.
- Koyu, Açık ve Gökkuşağı temaları eklendi.
- Progress bar geri getirildi ve teneffüslerde de kullanılabilir hale getirildi.
- Widget serbest boyutlandırılabilir hale getirildi.
