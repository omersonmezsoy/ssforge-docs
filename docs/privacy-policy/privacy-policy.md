# Convertica Gizlilik Politikası / Privacy Policy

[Türkçe](#turkce) · [English](#english)

**Revizyon tarihi / Revision prepared:** 9 Kasım 2026 / November 9, 2026<br>
**Yürürlük / Effective date:** Bu revizyon, deponun `main` dalından aşağıdaki mevcut politika URL'sinde yayımlandığında yürürlüğe girer. / This revision takes effect when it is published from the repository's `main` branch at the existing policy URL.<br>
**Uygulama / App:** Convertica (`com.ssforge.convertica`)<br>
**Geliştirici / Developer:** SSForge<br>
**İletişim / Contact:** [omerss.apps@gmail.com](mailto:omerss.apps@gmail.com)<br>
**Politika URL'si / Policy URL:** [https://omersonmezsoy.github.io/ssforge-docs/privacy-policy/](https://omersonmezsoy.github.io/ssforge-docs/privacy-policy/)

---

<a id="turkce"></a>

## Türkçe

### 1. Kapsam ve temel yaklaşım

Bu Gizlilik Politikası, SSForge tarafından yayımlanan **Convertica** mobil uygulamasının bilgileri nasıl işlediğini açıklar. Convertica; para birimi ve birim dönüştürme, belge tarama ve düzenleme, tarih ve iş günü hesaplama, geri sayım ve Android ana ekran widget'ları gibi araçlar sunar.

Convertica için kullanıcı hesabı oluşturmanız gerekmez. SSForge, kişisel belgelerinizi, fotoğraflarınızı, OCR metinlerinizi, çizimlerinizi veya imzalarınızı saklayan bir Convertica sunucusu işletmez. Bu içerikler, aşağıda açıklanan üçüncü taraf SDK'ların otomatik teknik verilerinden ayrı olarak, cihazınızda işlenir ve SSForge'a ait bir sunucuya yüklenmez.

Uygulamayı kullanmanız bu politikada açıklanan işlemleri kabul ettiğiniz anlamına gelir. Kabul etmiyorsanız uygulamayı kullanmayın.

### 2. Cihazda işlenen belge ve kullanıcı içeriği

Convertica'da aşağıdaki işlemler cihazınızda gerçekleştirilir:

- Kamera ile belge tarama ve Google ML Kit kullanılarak cihaz üzerinde metin tanıma (OCR)
- İşletim sisteminin galeri veya dosya seçicisi aracılığıyla seçtiğiniz fotoğraf ve dosyaları açma
- PDF açma, sayfaları yeniden sıralama, döndürme, silme, birleştirme ve dışa aktarma
- Çizim, işaretleme, metin ekleme ve imza yerleştirme
- PDF, TXT, DOCX ve desteklenen diğer çıktıları oluşturma

Belge geçmişi, taranan görüntüler, OCR sonuçları, düzenleme verileri ve uygulama içinde kaydedilen dosyalar uygulamanın yerel depolamasında tutulabilir. Dışa aktarılan bir dosyayı seçtiğiniz başka bir konuma kaydederseniz o kopya seçilen konumda kalır.

**SSForge, belge, fotoğraf, OCR, çizim veya imza içeriğinizi kendi sunucularına yüklemez, saklamaz veya bunlara erişmez.** Bir dosyayı paylaşmayı seçtiğinizde işletim sisteminin paylaşım menüsünü siz başlatırsınız. Bundan sonra seçtiğiniz alıcı uygulama veya hizmet kendi gizlilik koşullarına göre işlem yapabilir.

### 3. İzinler ve cihaz kaynakları

- **Kamera:** Yalnız kamera kullanan tarama özelliklerini seçtiğinizde belge, fiyat veya birim yakalamak için istenir. İzni reddederseniz diğer özellikleri kullanmaya devam edebilirsiniz.
- **Fotoğraflar ve dosyalar:** İşletim sisteminin seçicisi üzerinden yalnız sizin seçtiğiniz öğelere erişilir. Seçiciyi iptal etmek içerik oluşturmaz veya yüklemez.
- **Bildirimler:** Geri sayım hatırlatmalarını etkinleştirdiğinizde yerel bildirim göstermek için istenir. Hatırlatma etkinleştirmezseniz bu izin ilgili akışta istenmez; izni reddetmek geri sayımı kaydetmenizi engellemez.

Convertica ses kaydetmez ve mikrofon izni istemez.

### 4. Yerel özellik verileri

Ayarlar, favoriler, önbelleğe alınmış kur verileri, belge geçmişi, çalışma takvimleri, özel günler, geri sayımlar ve hatırlatma tercihleri cihazınızda saklanabilir. Geri sayım bildirimleri cihaz tarafından yerel olarak zamanlanır. Android widget'ları, seçtiğiniz dönüşüm veya geri sayım bilgilerini ana ekranda göstermek için uygulamanın yerel verilerinden sınırlı bir anlık görüntü kullanabilir.

Bu yerel özellikler için SSForge hesabı veya SSForge sunucusu gerekmez. Cihazın yedekleme, dosya sistemi ve bildirim davranışları işletim sistemi ve cihaz üreticisi ayarlarına bağlı olabilir.

### 5. Kur, kıymetli maden ve resmî tatil verileri

Convertica, gerekli olduğunda üçüncü taraf veri hizmetlerine doğrudan cihazınızdan istek gönderir:

- **Frankfurter API:** Para birimleri ile altın ve gümüş gibi desteklenen kıymetli madenler için güncel, tarihsel ve dönemsel referans oranları. İstekler temel/hedef varlık kodlarını ve tarih veya tarih aralığını içerebilir. Yazdığınız dönüşüm tutarı gönderilmez; hesaplama cihazda yapılır. Gram değerleri troy ons oranlarından cihazda türetilir.
- **Nager.Date Community API v4:** Seçtiğiniz ülke ve yıl için ülke genelindeki resmî tatil verileri. İstekler ülke kodunu ve yılı içerebilir. Kişisel takviminiz, özel gün adlarınız, geri sayım başlıklarınız ve hatırlatma metinleriniz gönderilmez.

Bu hizmetlere yapılan standart internet istekleri, ağın çalışması için IP adresi ve standart bağlantı bilgilerini hizmet sağlayıcılarına gösterebilir. Frankfurter'ın yayımlanmış açıklamasına göre genel API kişisel veri, IP adresi veya istek URL'si kaydetmez ve Cloudflare'dan yalnız toplu trafik istatistikleri alır. Nager.Date verileri bilgilendirme amaçlıdır; tatillerin hukuki kesinliği için resmî makamları kontrol etmelisiniz.

### 6. Firebase Analytics

Convertica'nın production sürümü, özelliklerin kullanımını ve uygulamanın iyileştirilebileceği alanları anlamak için **Google Firebase Analytics** kullanır. Özel olaylar; ekran veya özellik açılması, bir dönüşümün tamamlanması, tarama/dışa aktarma sonucu ve genel işlem kategorisi gibi teknik kullanım sinyallerini içerebilir.

Convertica'nın özel Analytics olayları; belge veya görüntü içeriğini, OCR metnini, dosya adını, çizim veya imzayı, geri sayım başlığını, serbest metni, fiyatı ya da dönüşüm tutarını göndermeyecek şekilde tasarlanmıştır. Bununla birlikte Firebase SDK'ları, yapılandırmaya ve Google'ın güncel belgelerine bağlı olarak uygulama instance kimliği, reklam kimliği, yaklaşık konum (örneğin maskelenmiş IP'den türetilen bölge), cihaz/işletim sistemi bilgisi ve uygulama etkileşimleri gibi SDK kaynaklı verileri işleyebilir.

### 7. Firebase Crashlytics

Convertica'nın production sürümü, çökmeleri ve teknik hataları tanılamak için **Google Firebase Crashlytics** kullanır. Crashlytics otomatik olarak stack trace, ilgili uygulama durumu, cihaz ve işletim sistemi üst verileri, uygulama sürümü ve Crashlytics kurulum UUID'si gibi tanılama verilerini işleyebilir. Analytics etkin olduğunda, çökmeden önceki uygulama etkileşimlerini açıklayan breadcrumb bilgileri de rapora eklenebilir.

Convertica, Crashlytics'e belge/OCR/imza içeriğini, kullanıcı dosya adını, serbest metni veya dönüşüm tutarını kasıtlı olarak eklemez. Teknik raporların içeriği kullanılan SDK sürümüne ve hata bağlamına göre değişebilir.

### 8. Google AdMob

Convertica'nın ücretsiz production sürümü banner reklamları göstermek için **Google AdMob** kullanır. Google Mobile Ads SDK'nın resmî açıklamasına göre SDK; reklam, analiz ve sahtekârlığı önleme amaçlarıyla aşağıdaki verileri otomatik olarak toplayabilir ve paylaşabilir:

- IP adresi ve bundan tahmin edilebilen yaklaşık/genel konum
- Uygulama açılışı, dokunmalar, reklam gösterimleri ve görüntülemeler gibi uygulama ve reklam etkileşimleri
- Başlangıç süresi, takılma oranı, enerji kullanımı gibi tanılama ve performans bilgileri
- Android reklam kimliği, app set ID ve uygun olduğunda cihazdaki oturum açmış hesaplarla ilişkili diğer cihaz/hesap tanımlayıcıları

Bu işlemler Google'ın şartları, kullanıcının bölgesi, cihaz ayarları, izin/tercih seçenekleri ve reklam yapılandırmasına bağlıdır. Android ayarlarından reklam kimliğinizi sıfırlayabilir veya silebilir ve mevcut reklam gizliliği seçeneklerini yönetebilirsiniz.

### 9. Saklama ve silme

Yerel Convertica verileri, siz silene, uygulama verilerini temizleyene veya uygulamayı kaldırana kadar cihazda kalabilir. İşletim sisteminin yedekleme davranışı bu işlemlerin sonucunu etkileyebilir. Uygulama dışına aktardığınız veya başka bir hizmetle paylaştığınız kopyalar ayrıca silinmelidir.

Firebase ve AdMob gibi üçüncü taraf hizmetlerin saklama ve silme süreleri kendi yapılandırmalarına, şartlarına ve politikalarına tabidir. SSForge'a destek e-postası gönderirseniz mesajınız ve e-posta adresiniz talebi yanıtlamak, güvenlik veya yasal yükümlülükleri yerine getirmek için gerekli olduğu sürece e-posta sağlayıcısında tutulabilir. Silme veya gizlilik talebi için aşağıdaki adresten iletişime geçebilirsiniz.

### 10. Güvenlik ve üçüncü taraflar

Firebase ve Google Mobile Ads SDK'ları, resmî belgelerine göre topladıkları verileri aktarım sırasında HTTPS/TLS ile şifreler. Diğer çevrimiçi hizmetler de destekledikleri güvenli bağlantıları kullanır. Hiçbir aktarım veya depolama yöntemi yüzde yüz güvenli değildir.

Kullandığımız başlıca üçüncü taraflar ve belgeleri:

- [Google Gizlilik Politikası](https://policies.google.com/privacy)
- [Firebase — Google Play veri açıklaması](https://firebase.google.com/docs/android/play-data-disclosure)
- [Google Mobile Ads SDK — Google Play veri açıklaması](https://developers.google.com/admob/android/privacy/play-data-disclosure)
- [Google ML Kit metin tanıma](https://developers.google.com/ml-kit/vision/text-recognition/v2/android)
- [Frankfurter API](https://frankfurter.dev/)
- [Nager.Date](https://github.com/nager/Nager.Date)

Her hizmet kendi şart ve gizlilik uygulamalarından sorumludur.

### 11. Haklarınız ve tercihleriniz

Bulunduğunuz yere göre erişim, düzeltme, silme, kısıtlama, itiraz veya veri taşınabilirliği gibi haklara sahip olabilirsiniz. Convertica verilerinin büyük bölümü cihazınızda olduğundan yerel verileri uygulama içinden, Android uygulama ayarlarından veya uygulamayı kaldırarak yönetebilirsiniz. Reklam tercihlerini Android ve Google reklam ayarlarından yönetebilirsiniz.

SSForge'ın kontrolündeki veriler veya destek yazışmaları hakkında talepte bulunmak için [omerss.apps@gmail.com](mailto:omerss.apps@gmail.com) adresine yazın. Uygulanabilir mevzuat uyarınca makul süre içinde yanıt veririz.

### 12. Çocukların gizliliği

Convertica genel amaçlı bir yardımcı uygulamadır ve 13 yaşın altındaki çocuklara (veya ülkenizde geçerli daha yüksek asgari yaşa) yönelik değildir. Bir çocuğun bize kişisel bilgi gönderdiğini düşünüyorsanız silebilmemiz için bizimle iletişime geçin.

### 13. Politika değişiklikleri

Uygulama özellikleri, yasal gereklilikler veya üçüncü taraf hizmetler değiştiğinde bu politikayı güncelleyebiliriz. Yeni revizyon, bu sayfada yayımlandığında yürürlüğe girer; önemli değişiklikler için uygun olduğunda uygulama veya mağaza sayfasında ayrıca bildirim sağlanabilir.

### 14. İletişim

**SSForge**<br>
E-posta: [omerss.apps@gmail.com](mailto:omerss.apps@gmail.com)

---

<a id="english"></a>

## English

### 1. Scope and basic approach

This Privacy Policy explains how the **Convertica** mobile application published by SSForge handles information. Convertica provides tools including currency and unit conversion, document scanning and editing, date and business-day calculations, countdowns, and Android home-screen widgets.

Convertica does not require a user account. SSForge does not operate a Convertica server that stores your personal documents, photos, OCR text, drawings, or signatures. Separate from automatic technical data processed by the third-party SDKs described below, this content is processed on your device and is not uploaded to a server owned by SSForge.

By using the app, you agree to the processing described in this policy. If you do not agree, please do not use the app.

### 2. Documents and user content processed on device

The following operations are performed on your device in Convertica:

- Scanning documents with the camera and on-device text recognition (OCR) using Google ML Kit
- Opening photos and files that you select through the operating system's gallery or file picker
- Opening PDFs, reordering, rotating, deleting and merging pages, and exporting documents
- Drawing, markup, adding text, and placing a signature
- Creating PDF, TXT, DOCX, and other supported outputs

Document history, scanned images, OCR results, editing data, and files saved inside the app may be kept in the app's local storage. If you export a file to another location, that copy remains in the location you selected.

**SSForge does not upload, store, or access your document, photo, OCR, drawing, or signature content on its own servers.** When you choose to share a file, you initiate the operating system share sheet. The recipient app or service you select may then process the file under its own privacy terms.

### 3. Permissions and device resources

- **Camera:** Requested only when you choose a camera-based scan feature to capture a document, price, or unit. If you deny permission, other features remain available.
- **Photos and files:** Only items you select through the operating system picker are accessed. Cancelling the picker does not create or upload content.
- **Notifications:** Requested when you enable countdown reminders so the device can show local notifications. The relevant flow does not request this permission if you do not enable reminders; denying it does not prevent you from saving a countdown.

Convertica does not record audio and does not request microphone permission.

### 4. Local feature data

Settings, favorites, cached rate data, document history, work calendars, custom days, countdowns, and reminder preferences may be stored on your device. Countdown notifications are scheduled locally by the device. Android widgets may use a limited snapshot of local app data to show the conversion or countdown information you selected on the home screen.

These local features do not require an SSForge account or an SSForge server. Device backup, file-system, and notification behavior may depend on your operating system and device-manufacturer settings.

### 5. Exchange-rate, precious-metal, and public-holiday data

When needed, Convertica sends requests directly from your device to third-party data services:

- **Frankfurter API:** Current, historical, and period reference rates for currencies and supported precious metals such as gold and silver. Requests may include base/quote asset codes and a date or date range. The amount you enter is not sent; conversion is calculated on device. Gram values are derived on device from troy-ounce rates.
- **Nager.Date Community API v4:** Country-wide public-holiday data for the country and year you select. Requests may include the country code and year. Your personal calendar, custom-day names, countdown titles, and reminder text are not sent.

Standard internet requests to these services may expose an IP address and standard connection information to the service providers as necessary for networking. Frankfurter's published statement says its public API does not collect or log personal data, IP addresses, or request URLs and receives only aggregate traffic statistics from Cloudflare. Nager.Date data is informational; consult official authorities when legal certainty about a holiday is required.

### 6. Firebase Analytics

The production version of Convertica uses **Google Firebase Analytics** to understand feature usage and where the app can be improved. Custom events may include technical usage signals such as a screen or feature being opened, a conversion being completed, a scan/export result, and a general action category.

Convertica's custom Analytics events are designed not to send document or image content, OCR text, file names, drawings or signatures, countdown titles, free-form text, prices, or conversion amounts. Depending on configuration and Google's current documentation, Firebase SDKs may nevertheless process SDK-derived data such as an app-instance identifier, advertising identifier, approximate location (for example a region derived from a masked IP address), device/operating-system information, and app interactions.

### 7. Firebase Crashlytics

The production version of Convertica uses **Google Firebase Crashlytics** to diagnose crashes and technical errors. Crashlytics may automatically process diagnostic data such as stack traces, relevant app state, device and operating-system metadata, app version, and a Crashlytics installation UUID. When Analytics is enabled, breadcrumb information describing app interactions before a crash may also be attached to a report.

Convertica does not intentionally attach document/OCR/signature content, user file names, free-form text, or conversion amounts to Crashlytics. The contents of a technical report may vary with the SDK version and error context.

### 8. Google AdMob

The free production version of Convertica uses **Google AdMob** to show banner advertisements. According to the Google Mobile Ads SDK's official disclosure, the SDK may automatically collect and share the following data for advertising, analytics, and fraud-prevention purposes:

- IP address and the approximate/general location that may be estimated from it
- App and ad interactions such as app launches, taps, ad impressions, and views
- Diagnostic and performance information such as launch time, hang rate, and energy usage
- Android advertising ID, app set ID, and, where applicable, other device/account identifiers related to signed-in accounts on the device

This processing depends on Google's terms, the user's region, device settings, permission/choice mechanisms, and advertising configuration. You can reset or delete the advertising ID and manage available advertising privacy options in Android settings.

### 9. Retention and deletion

Local Convertica data may remain on the device until you delete it, clear the app's data, or uninstall the app. Operating-system backup behavior may affect the outcome. Copies exported outside the app or shared with another service must be deleted separately.

Retention and deletion periods for third-party services such as Firebase and AdMob are governed by their configuration, terms, and policies. If you email SSForge for support, your message and email address may be retained by the email provider for as long as needed to respond to the request and meet security or legal obligations. You may use the contact below for deletion or privacy requests.

### 10. Security and third parties

According to their official documentation, Firebase and the Google Mobile Ads SDK encrypt data they collect in transit using HTTPS/TLS. Other online services use secure connections where supported. No transmission or storage method is completely secure.

Our principal third-party services and documentation are:

- [Google Privacy Policy](https://policies.google.com/privacy)
- [Firebase — Google Play data disclosure](https://firebase.google.com/docs/android/play-data-disclosure)
- [Google Mobile Ads SDK — Google Play data disclosure](https://developers.google.com/admob/android/privacy/play-data-disclosure)
- [Google ML Kit text recognition](https://developers.google.com/ml-kit/vision/text-recognition/v2/android)
- [Frankfurter API](https://frankfurter.dev/)
- [Nager.Date](https://github.com/nager/Nager.Date)

Each service is responsible for its own terms and privacy practices.

### 11. Your rights and choices

Depending on where you live, you may have rights such as access, correction, deletion, restriction, objection, or data portability. Because most Convertica data is stored on your device, you can manage local data in the app, through Android app settings, or by uninstalling the app. You can manage advertising choices in Android and Google ad settings.

For requests about data under SSForge's control or support correspondence, email [omerss.apps@gmail.com](mailto:omerss.apps@gmail.com). We will respond within a reasonable period as required by applicable law.

### 12. Children's privacy

Convertica is a general-purpose utility app and is not directed to children under 13 (or a higher minimum age applicable in your country). If you believe a child has sent us personal information, contact us so that we can take appropriate deletion steps.

### 13. Changes to this policy

We may update this policy when app features, legal requirements, or third-party services change. A new revision becomes effective when it is published on this page; where appropriate, material changes may also be announced in the app or store listing.

### 14. Contact

**SSForge**<br>
Email: [omerss.apps@gmail.com](mailto:omerss.apps@gmail.com)

---

*Bu politika yalnız SSForge tarafından yayımlanan Convertica (`com.ssforge.convertica`) için geçerlidir. / This policy applies only to Convertica (`com.ssforge.convertica`) published by SSForge.*

<!--
Maintainer publication note (not shown in rendered Markdown previews that hide comments):
This revision becomes effective only after merge to main and a successful GitHub Pages deployment from /docs.
Verify the unchanged public URL after deployment.
-->
