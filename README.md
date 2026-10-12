<div align="center">

<img src="assets/hero-ikili.svg" width="100%" alt="Solda Kıvılcım: Küçük görevler, büyüyen bir alev. Ücretsiz, oyunlaştırılmış alışkanlık uygulaması. Sağda AI Odası: Bir iş yaz, ekip çalışsın. Yapay zekâların birlikte çalıştığı oda.">

</div>

## Kıvılcım

Kıvılcım'ı yapıyorum: küçük görevleri alev alev bir seriye dönüştüren bir alışkanlık uygulaması. Hesap istemez, sunucusu yoktur; kayıtlar cihazda kalır. Windows, Mac, Linux ve Android'de çalışıyor; iPhone sürümü yolda.

<a href="https://yigit2015.github.io/kivilcim-indir/#indir"><img src="assets/btn-indir-dark.png" height="44" alt="Kıvılcım'ı indir"></a>&nbsp;
<a href="https://yigit2015.github.io/kivilcim-indir/uygulama/"><img src="assets/btn-web-dark.png" height="44" alt="Tarayıcıda dene"></a>&nbsp;
<a href="https://github.com/yigit2015/kivilcim-indir/releases/latest"><img src="https://img.shields.io/github/v/release/yigit2015/kivilcim-indir?label=son%20s%C3%BCr%C3%BCm&color=FF7A1A&style=flat-square" height="20" alt="Son sürüm"></a>

<br>

<a href="https://yigit2015.github.io/kivilcim-indir/"><img src="assets/showcase-dark.webp" width="100%" alt="Kıvılcım masaüstünde kenar çubuklu geniş düzenle, telefonda Bugün (görev yörüngesi), Macera ve Günü kapat ekranlarıyla."></a>

### Kıvılcım'ın kuralları

<table>
  <tr>
    <td width="25%" valign="top">
      <img src="assets/icons/gizlilik.svg" width="28" alt=""><br>
      <b>Hesap yok</b><br>
      Kayıt, e-posta, sunucu yok. Paylaşım QR ya da kodla, cihazdan cihaza.
    </td>
    <td width="25%" valign="top">
      <img src="assets/icons/seri.svg" width="28" alt=""><br>
      <b>Küçük adım</b><br>
      Her gün bir tik alevi büyütür. Seri uzadıkça Kıvı'nın rengi değişir.
    </td>
    <td width="25%" valign="top">
      <img src="assets/icons/nazik.svg" width="28" alt=""><br>
      <b>Suçlama yok</b><br>
      Seri kırılınca ceza yok; son 30 günün tutarlılığı ve "tekrar hoş geldin".
    </td>
    <td width="25%" valign="top">
      <img src="assets/icons/erisim.svg" width="28" alt=""><br>
      <b>Herkes için</b><br>
      Ekran okuyucu, sade hareket, renk körü dostu işaretler, büyük yazı.
    </td>
  </tr>
</table>

### Nerede

- **Tanıtım sitesi:** [yigit2015.github.io/kivilcim-indir](https://yigit2015.github.io/kivilcim-indir/)
- **İndirmeler:** [kivilcim-indir](https://github.com/yigit2015/kivilcim-indir) deposunun [Releases](https://github.com/yigit2015/kivilcim-indir/releases) sayfası
- **Sürüm notları:** [her sürümde ne değişti](https://yigit2015.github.io/kivilcim-indir/surumler/)
- **Destek:** [sık sorulanlar](https://yigit2015.github.io/kivilcim-indir/destek/) ya da destekkivilcim@gmail.com

## AI Odası

AI Odası'nı da yapıyorum: birden çok yapay zekâyı tek ekranda birlikte çalıştıran bir ekip odası. Bir şef işi dağıtır, yardımcılar yazar, bir hakem her cevabı puanlar; kimin ne yaptığı ve ne harcadığı canlı görünür. Kendi API anahtarlarınla, kendi bilgisayarında çalışır.

<img src="assets/ai-odasi-vitrin.webp" width="100%" alt="AI Odası'nın ana ekranı: solda kayıtlı odalar, ortada şefin yazdığı sonuç kartı, sağda beş yapay zekânın bugünkü token sayısıyla durduğu ekip panosu.">

<sub>Görüntü uygulamanın anahtarsız deneme modunda çekildi; içindeki cevaplar örnek metindir.</sub>

### AI Odası'nın kuralları

<table>
  <tr>
    <td width="25%" valign="top">
      <img src="assets/icons/ai-ekip.svg" width="28" alt=""><br>
      <b>Şef dağıtır</b><br>
      İşi şefe verirsin; şef parçalara böler, uygun yardımcıya dağıtır, tek cevap yazar.
    </td>
    <td width="25%" valign="top">
      <img src="assets/icons/ai-hakem.svg" width="28" alt=""><br>
      <b>Hakem puanlar</b><br>
      Her cevap alakalılık ve kalite puanı alır. Puan düşükse ikinci görüş istenir.
    </td>
    <td width="25%" valign="top">
      <img src="assets/icons/ai-token.svg" width="28" alt=""><br>
      <b>Hiçbir şey gizli değil</b><br>
      Kim bağlanıyor, düşünüyor, yazıyor; kaç saniye, kaç token: hepsi ekranda.
    </td>
    <td width="25%" valign="top">
      <img src="assets/icons/ai-anahtar.svg" width="28" alt=""><br>
      <b>Anahtarlar sende</b><br>
      Anahtarlar bilgisayarında kalır, tarayıcıya geri gönderilmez. Arada sunucu yok.
    </td>
  </tr>
</table>

Henüz herkese açık değil; tanıtım sitesi hazırlanıyor.

## Nasıl yapılıyor

Kıvılcım Expo ve React Native ile TypeScript'te yazılıyor; hareketler Reanimated, semboller Phosphor. Masaüstü sürümü Electron kabuğunda aynı kodu çalıştırıyor. Tanıtım sitesi derleme adımı olmayan düz HTML ve CSS; hareketleri GSAP veriyor, dışarıya tek istek atmıyor.

AI Odası bağımlılıksız bir Node sunucusu ile düz HTML, CSS ve JavaScript; derleme adımı yok. Karakterleri elle çizilmiş SVG.
