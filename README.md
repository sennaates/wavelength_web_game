# Dalga Boyu (Wavelength Web Oyunu)

Dalga Boyu, popüler masa oyunu Wavelength'ten ilham alınarak geliştirilmiş, web tarayıcısı üzerinden oynanabilen interaktif bir takım oyunudur. Özellikle mobil cihazlarda (tablet ve telefon) yatay (landscape) kullanım için optimize edilmiş modern, duyarlı (responsive) bir arayüze sahiptir.

## 🎯 Nasıl Oynanır?

Oyun iki takım halinde oynanır. Her turda aşağıdaki adımlar izlenir:
1. **Ölçek Belirlenir:** Ekranda "Sıcak ↔ Soğuk" gibi zıt kavramlardan oluşan bir ölçek görünür.
2. **Hedef Gizlenir:** İpucu verecek oyuncu cihazı sadece kendisi görecek şekilde eline alır ve "Gizle" butonuna basar. Çark rastgele döner ve hedef bölge gizlenir.
3. **İpucu Verilir:** İpucu veren oyuncu, hedefin ölçekte nereye (örneğin daha çok sıcak tarafına mı yoksa soğuk tarafına mı) denk geldiğini düşünerek takımı için **tek kelimelik** bir ipucu söyler.
4. **Tahmin Yapılır:** Takım arkadaşları iğneyi sürükleyerek hedefin nerede olduğunu tahmin ederler.
5. **Çark Açılır:** Tahmin tamamlandıktan sonra çark açılır ve iğnenin bulunduğu bölgeye göre (2, 3 veya 4) puan kazanılır. Belirlenen hedef puana ilk ulaşan takım oyunu kazanır!

## ✨ Özellikler

- **Responsive Tasarım:** Hem dikey hem de yatay (landscape) ekranlarda, her boyuttaki cihazda sorunsuz bir oyun deneyimi.
- **Tema Seçeneği (Açık/Koyu):** Sağ üst köşedeki buton ile **Açık (Gündüz)** ve **Koyu (Gece)** temalar arasında anında geçiş yapabilme imkanı.
- **Dinamik Çark Sistemi:** SVG tabanlı interaktif çark ile sürükle-bırak hissiyatı ve akıcı gizleme/açılma animasyonları.
- **Fikir Jeneratörü:** Kendi ölçeğini bulmakta zorlanan oyuncular için tek tıkla rastgele kelime zıtlıkları öneren yerleşik fikir (Örn: "Tehlikeli ↔ Güvenli") sistemi.
- **Görsel Efektler:** Tur sonlarında ve oyun bitiminde kazanan takımı kutlayan görsel konfeti animasyonları.

## 🚀 Kurulum & Çalıştırma

Oyun tamamen statik istemci tarafında (frontend) çalışmaktadır. Herhangi bir sunucu kurulumu ya da veritabanı bağlantısı gerektirmez.

1. Projeyi bilgisayarınıza indirin veya klonlayın:
   ```bash
   git clone https://github.com/sennaates/wavelength_web_game.git
   ```
2. Klasör içerisindeki `index.html` dosyasını herhangi bir modern web tarayıcısında (Chrome, Safari, Firefox vb.) açın.
3. Arkadaşlarınızla oynamaya başlayın!

## 🛠️ Teknolojiler

- **HTML5 / SVG:** Temel yapı ve tamamen özel çizilmiş çark grafikleri.
- **CSS3:** Özel CSS Grid / Flexbox düzenleri, medya sorguları (media queries) ve CSS Variable tabanlı çoklu tema desteği.
- **Vanilla JavaScript:** Oyun mantığı, durum (state) yönetimi ve SVG etkileşimleri.

## 🤝 Katkıda Bulunma

Bu proje tamamen açık kaynaklıdır. Oyun deneyimini iyileştirecek her türlü fikir, tasarım önerisi veya kod katkısı için *Pull Request* (PR) gönderebilirsiniz. İyi oyunlar!
