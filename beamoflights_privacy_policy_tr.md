# Gizlilik Politikası - Beam of Light

**Son Güncelleme:** 22 Eylül 2026

## Özet

Beam of Light'ta hesap yoktur; adınız, e-postanız veya telefon numaranız hiçbir zaman istenmez. Reklam, reklam SDK'sı ve uygulama içi satın alma yoktur. Seviyeleri dengeleyebilmek için bölümlerin nasıl oynandığına dair anonim istatistikler toplarız; sizi başka uygulama veya sitelerde takip etmeyiz.

## Topladığımız veriler

Oyunun nasıl oynandığını anlamak için **Google Analytics for Firebase** kullanıyoruz. Beş olay kaydedilir:

- `level_start`, `level_resume`, `level_pause`, `level_end` — bir bölüm denemesi başına tek ölçüm
- `play_day` — oyunun açıldığı farklı gün sayısı

Her olay yalnızca oynanışa dair bilgiler taşır:

- Hangi bölüm: dahili adı ve numarası, meydan okuma türü, tahta şekli ve revize edilen bölümleri ayırt etmeye yarayan bir düzen özeti (hash)
- Deneme nasıl geçti: aktif geçirilen saniye, hamle sayısı, hata sayısı, kalan ışın sayısı ve denemenin başarılı mı, başarısız mı olduğu, yeniden mi başlatıldığı yoksa duraklatıldığı mı
- Genel ilerleme: kaç gün oynadığınız, ulaştığınız en yüksek bölüm ve tamamladığınız en yüksek bölüm
- Hangi yapı: uygulamanın genel sürüm mü yoksa test yapısı mı olduğu

Bunların yanında Analytics SDK'sı otomatik olarak bir **uygulama kurulum kimliği** (kurulumda üretilen rastgele bir değer), uygulama sürümü, cihaz modeli, işletim sistemi, dil ve maskelenmiş IP adresinizden türetilen kaba bir ülke/bölge bilgisi toplar. Tüm bu veriler TLS ile şifrelenerek iletilir.

Her deneme ayrıca rastgele üretilmiş bir deneme kimliği taşır. Bu kimlik yalnızca tek bir denemeye ait olayların birbiriyle eşleştirilebilmesi içindir; size veya başka bir denemeye bağlı değildir.

## Toplamadığımız veriler

Adınızı, e-posta adresinizi, telefon numaranızı, rehberinizi, fotoğraflarınızı, takviminizi, dosyalarınızı veya kesin konumunuzu toplamayız. Oyun, titreşim dışında hiçbir cihaz izni istemez.

Reklam kimliği kullanmayız. Android tarafında `AD_ID` izni uygulamadan açıkça kaldırılmıştır; her iki platformda da Analytics SDK'sı reklam depolaması, reklam kullanıcı verisi ve reklam kişiselleştirmesi kapalı olarak başlatılır. Toplanan hiçbir veri reklam amacıyla kullanılmaz; veri simsarlarına veya reklam ağlarına aktarılmaz.

Uygulama içi satın alma, liderlik tablosu ve hesap sistemi yoktur; dolayısıyla faturalandırılacak, sıralanacak veya giriş yapılacak bir şey de yoktur.

## Cihazınızda kalanlar

Seçtiğiniz dil, ses ve titreşim ayarlarınız, hareket azaltma tercihiniz, bölüm ilerlemeniz ve eğitimi görüp görmediğiniz cihazınızın kendi deposunda saklanır. Bu kayıt bize gönderilmez.

## Verileri kim işler

Analitik verilerini bizim adımıza Google işler ([Google Gizlilik Politikası](https://policies.google.com/privacy)). Apple ve Google ayrıca App Store ve Google Play'in işletmecisi olarak uygulamanın dağıtımını yürütür. Veri satmayız, reklamcılarla paylaşmayız.

## Hukuki dayanak ve saklama

GDPR veya KVKK'nın uygulandığı durumlarda hukuki dayanağımız, bölüm zorluğunu anlamak ve dengelemekteki meşru menfaattir. Analitik kayıtları Firebase projemizde yapılandırılan saklama süresi boyunca tutulur; bu süre 14 ayı aşmaz ve sonunda kayıtlar otomatik olarak silinir.

## Çocukların gizliliği

Oyun her yaşa uygundur. Çocuklardan bilerek kişisel bilgi toplamayız ve topladığımız istatistikler bir kimliğe bağlı değildir.

## Tercihleriniz

Oyunda şu an analitik için uygulama içi bir açma/kapama anahtarı bulunmuyor. Uygulamayı silmek tüm toplamayı durdurur ve uygulama kurulum kimliğini geçersiz kılar; yeniden kurduğunuzda eskisiyle bağlantısı olmayan yeni bir kimlik oluşur.

Sorularınız, düzeltme veya silme talepleriniz için aşağıdaki adrese yazın; anonim kayıtları bulabilmemiz için oynadığınız yaklaşık tarihleri ve cihazı belirtin.

## Bu politikadaki değişiklikler

Oyunun topladığı veriler değişirse, yeni sürüm yayınlanmadan önce bu belge ve tarihi güncellenir.

## İletişim

- **E-posta:** akinalpfdn@gmail.com
- **Web sitesi:** www.akinalpfdn.com
