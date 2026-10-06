# Sürüm Yayınlama Kontrol Listesi

Bu depo yalnızca DersZil Widget'ın genel dağıtımı için kullanılır. Kaynak kod geliştirme deposu ayrı ve özeldir.

## Yeni sürüm yayınlama

1. Özel geliştirme deposunda Windows x64 self-contained derlemesini tamamla.
2. ZIP paketinin adını sürümle uyumlu hale getir:
   - Örnek: `DersZilWidget-v1.5.1-win-x64.zip`
3. Bu depoda **Releases → Draft a new release** sayfasını aç.
4. Yeni tag oluştur:
   - Örnek: `v1.5.1`
5. Başlık:
   - Örnek: `DersZil Widget v1.5.1`
6. Sürüm notlarını CHANGELOG.md içeriğine göre yaz.
7. ZIP paketini Release assets bölümüne yükle.
8. **Publish release** ile yayımla.
9. Yayın sonrası şu adresin çalıştığını kontrol et:
   - `https://github.com/ersurer1-design/DersZil-Widget/releases/latest`
10. Önceki DersZil sürümünde **Güncellemeleri Denetle** diyerek yeni sürümün algılandığını doğrula.

## Not

Uygulama GitHub'ın `/releases/latest` API'sini kullandığı için tag adının `v1.5.1`, `v1.6.0` gibi geçerli bir sürüm numarası olması önemlidir.
