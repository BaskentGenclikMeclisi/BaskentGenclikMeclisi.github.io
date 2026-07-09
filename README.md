# BGM Oryantasyon Oyunu

Başkent Gençlik Meclisi'nin eğlenceli kişilik oyunu: 10 soruluk bir grup sohbetine katıl, cevaplarına göre meclisteki rolünü öğren, sonucunu arkadaşlarınla paylaş!

## Özellikler

- Baştan sona grup sohbeti kurgusu (mesaj balonları, "yazıyor…" animasyonları)
- 11 farklı rol, nadir rol rozeti, konfetili sonuç açıklaması
- İndirilebilir sonuç kartı (Instagram story boyutunda), WhatsApp ve genel paylaşım butonları
- Mobil öncelikli tasarım, tamamen istemci tarafında — sunucu/veritabanı gerekmez

## Kullanım

Tek dosyalık bir web sayfasıdır; `index.html`'i herhangi bir statik sunucuda yayınlamak yeterlidir.

- **Avatarlar:** Rol fotoğraflarını `avatars/` klasörüne kararlaştırılan adlarla koyun (ör. `baskan.jpg`); yoksa emoji gösterilir.
- **Müzik:** Fon müziğini `muzik/muzik.mp3` (veya .wav/.ogg/.m4a) olarak ekleyin; yoksa oyun sessiz çalışır. Ayrıntı: `muzik/OKUBENI.txt`
- **Paylaşım linki:** Yayın sonrası `index.html` içindeki `SITE_URL` sabitine sitenin adresini yazın.
