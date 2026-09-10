> **TASLAK — hukuki inceleme gerekli.** Bu metin yapay zekâ yardımıyla,
> uygulamanın gerçek veri işleme pratiklerine göre hazırlandı. Yayınlamadan
> önce bir hukukçuya (KVKK + GDPR) okutulmalı. `[…]` alanları doldurulmalı.

# Gizlilik Politikası — Dolapta Ne Var

**Son güncelleme:** 10 Eylül 2026

Bu politika, **Dolapta Ne Var** ("Uygulama") mobil uygulamasının kişisel
verilerinizi nasıl işlediğini açıklar. Veri sorumlusu: **Can Doruk**
("biz"). İletişim: **semahattincandoruk@gmail.com**.

## 1. Topladığımız veriler

| Veri | Ne zaman | Neden |
|---|---|---|
| **E-posta adresi ve şifre** (şifre bize şifreli/hash olarak ulaşır) | Hesap oluştururken | Kimlik doğrulama, hesabınıza erişim |
| **Buzdolabı malzeme listesi** (ad, miktar, kategori, son kullanma tarihi) | Malzeme eklediğinizde | Uygulamanın temel işlevi; tarif üretimi |
| **Alışveriş listeniz** | Liste oluşturduğunuzda | Uygulamanın işlevi; cihazlar arası senkron |
| **Kaydedilen/favori tarifler** | Tarif ürettiğinizde | Geçmiş ve favoriler; cihazlar arası senkron |
| **Yapay zekâ çağrı kayıtları** (gönderilen malzeme listesi, dönen tarif metni, zaman, model, token sayısı) | Tarif ürettiğinizde veya fiş taradığınızda | Maliyet takibi, kötüye kullanım önleme, hizmet kalitesi |
| **Fiş / ürün fotoğrafları** | Fotoğraf tarattığınızda | Yalnızca üründeki metni çıkarmak için işlenir — **fotoğraf saklanmaz**, işlem sonrası silinir |
| **Uygulama görünüm tercihleri** (tema, bildirim ayarları) | Ayarları değiştirdiğinizde | Deneyimi kişiselleştirmek |
| **Cihaz reklam tanımlayıcısı** (yalnızca ücretsiz sürümde, rızanızla) | Reklam gösterirken | Reklam sunumu ve ölçümü (bkz. §4) |
| **Çökme / hata kayıtları** (etkinse) | Uygulama beklenmedik şekilde kapanırsa | Hataları düzeltmek |

Konum, rehber, arama geçmişi gibi verileri **toplamıyoruz**.

## 2. Verileri nasıl kullanıyoruz

- Uygulamanın çekirdek işlevini sunmak (malzeme takibi, tarif üretimi, alışveriş listesi).
- Hesabınızı yönetmek ve verilerinizi cihazlarınız arasında senkronlamak.
- Yapay zekâ maliyetini izlemek ve adil kullanım sınırlarını uygulamak.
- Ücretsiz sürümde reklam göstermek (Pro aboneliğinde reklam yoktur).
- Hataları teşhis edip düzeltmek, hizmeti geliştirmek.

Verilerinizi **satmıyoruz** ve reklam dışında pazarlama amacıyla üçüncü
kişilerle paylaşmıyoruz.

## 3. Yapay zekâ hakkında

Tarif üretimi ve fiş/ürün okuma **Google Gemini** modeli ile yapılır.
Malzeme listeniz (ve fiş taramada fotoğrafınız) işlenmek üzere Google'a
gönderilir. Google, bu verileri kendi
[Gemini API gizlilik koşulları](https://ai.google.dev/gemini-api/terms)
kapsamında işler. Fotoğraflar tarafımızca saklanmaz.

Yapay zekâ çıktıları hatalı olabilir — alerjenleri ve gıda güvenliğini
(pişirme sıcaklığı, tazelik) kendiniz doğrulamalısınız.

## 4. Reklamlar (yalnızca ücretsiz sürüm)

Ücretsiz sürümde **Google AdMob** ile reklam gösterilir. Avrupa Ekonomik
Alanı, Birleşik Krallık ve İsviçre'deki kullanıcılara, ilk açılışta Google'ın
rıza ekranı (UMP) gösterilir; kişiselleştirilmiş reklam yalnızca rıza
verirseniz gösterilir. AdMob'un veri işleme bilgisi:
<https://support.google.com/admob/answer/6128543>. **Pro aboneliğinde
reklam ve reklam tanımlayıcısı kullanılmaz.**

## 5. Abonelikler

Pro aboneliği **Google Play Faturalandırma** üzerinden işlenir. Ödeme
bilgilerinizi biz görmeyiz; yalnızca aboneliğinizin aktif olup olmadığı
bilgisini tutarız.

## 6. Üçüncü taraf hizmet sağlayıcılar

| Sağlayıcı | Amaç | Konum |
|---|---|---|
| **Supabase** | Kimlik doğrulama ve veritabanı barındırma | AB / ABD |
| **Google Gemini** | Tarif ve fiş yapay zekâsı | Google altyapısı |
| **Google AdMob** | Reklam (ücretsiz sürüm) | Google altyapısı |
| **Google Play** | Uygulama dağıtımı ve abonelik faturalandırma | Google altyapısı |
| **Sentry** (etkinse) | Çökme raporlama | AB |

## 7. Verilerin saklanması ve silinmesi

- Verileriniz, hesabınız aktif olduğu sürece saklanır.
- **"Hesabımı sil"** dediğinizde buzdolabınız, tarifleriniz, listeleriniz,
  yapay zekâ kayıtlarınız ve hesap bilgileriniz **kalıcı olarak** silinir;
  yedeklerden de en geç 30 gün içinde düşer.
- Uygulamayı silmek verilerinizi sunucudan silmez — bunun için "Hesabımı
  sil" adımını kullanın.

## 8. Haklarınız (KVKK m. 11 / GDPR)

- **Erişim / taşınabilirlik:** Profil → Gizlilik ve hesap → "Verilerimi
  indir (JSON)" ile tüm verinizi dışa aktarabilirsiniz.
- **Düzeltme:** Verilerinizi uygulama içinden düzenleyebilirsiniz.
- **Silme:** "Hesabımı sil" ile.
- **İtiraz / rıza geri çekme:** Reklam rızanızı cihaz/Google ayarlarından
  yönetebilirsiniz.
- Talepleriniz ve şikâyetleriniz için: **semahattincandoruk@gmail.com**.
  KVKK kapsamında Kişisel Verileri Koruma Kurulu'na şikâyet hakkınız saklıdır.

## 9. Çocukların gizliliği

Uygulama 13 yaşın altındaki çocuklara yönelik değildir ve bilerek onlardan
veri toplamaz.

## 10. Güvenlik

Veriler aktarım sırasında şifrelenir (HTTPS). Sunucu tarafı erişim, satır
düzeyi güvenlik (RLS) ile her kullanıcıyı yalnızca kendi verisiyle sınırlar.
Yapay zekâ anahtarları ve sunucu sırları istemciye hiçbir zaman gönderilmez.

## 11. Değişiklikler

Bu politikayı güncelleyebiliriz. Önemli değişikliklerde uygulama içinde
bilgilendirilirsiniz. Güncel sürüm her zaman bu adreste yayınlanır.
