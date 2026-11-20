# FolioPeek — Gizlilik Politikası / Privacy Policy

Son güncelleme / Last updated: 2026-11-20

[Türkçe](#türkçe) · [English](#english)

---

## Türkçe

### Kısaca

* Hesap veya oturum açma gerekmez.
* Reklam, izleme, analiz veya telemetri yoktur.
* Geliştiricinin işlettiği hiçbir sunucu yoktur.
* FolioPeek **internete hiç çıkmaz**; uygulama paketinde ağ erişim yetkisi (`internetClient`) bulunmaz.

### Belgeleriniz

* Açtığınız PDF'ler yalnızca bilgisayarınızda, Windows'un kendi PDF ve yazı tanıma bileşenleriyle ve uygulamanın içindeki kütüphanelerle işlenir. Hiçbir belge içeriği cihazınızdan çıkmaz.
* Siz kaydetmedikçe açık dosyada değişiklik yapılmaz. Kaydettiğiniz ya da dışa aktardığınız dosyalar yalnızca sizin seçtiğiniz yere yazılır. Kayıt sırasında veri kaybını önlemek için önce geçici bir dosya yazılır, doğrulandıktan sonra hedef dosyayla değiştirilir.
* **İmza:** Oluşturduğunuz imza bilgisayarda saklanmaz; yalnızca uygulama açıkken bellekte tutulur ("Son imzayı kullan"). Uygulamayı kapatınca silinir. İmza, siz bir belgeye yerleştirip kaydettiğinizde o belgenin parçası olur.
* **Not yazarı:** Ayarlar'a bir ad yazarsanız, eklediğiniz notlara yazar olarak bu ad yazılır ve kaydettiğiniz belgeyle birlikte gider. Boş bırakabilirsiniz.
* **Belge özellikleri:** Başlık, yazar gibi bilgiler belgenin kendisinden okunur. Pro ile düzenlediğiniz ya da temizlediğiniz bilgiler yalnızca sizin kaydettiğiniz yeni dosyaya yazılır.
* **Pano:** "Kopyala" dediğinizde seçili metin ya da alan yalnızca Windows panosuna yazılır.
* **Yazı tanıma:** Windows'ta yüklü yazı tanıma dil paketleri kullanılır. Eksik bir dil paketi için FolioPeek yalnızca Windows'un dil ayarlarını açar.

### Bilgisayarınızda tutulanlar

Hepsi `%LOCALAPPDATA%\FolioPeek` klasöründe, yalnızca bu bilgisayardadır:

* **settings.json — ayarlar:** dil, tema ve vurgu rengi, okuma modu, yakınlaştırma, not renkleri ve not yazarı adı; son açılan belgelerin yolları ve açılma zamanları; isterseniz son kalınan sayfalar ve açık sekmeler.
* **license.dat — Pro lisans önbelleği:** Pro eklentisini satın aldıysanız, uygulamanın çevrimdışı da Pro olarak açılabilmesi için lisans durumu Windows Veri Koruma API'si (DPAPI) ile şifrelenerek saklanır.
* **error.log — hata günlüğü:** Beklenmeyen bir hata olursa yalnızca teknik hata ayrıntıları yazılır; belge içeriği asla yazılmaz.

Son açılanlar listesini Ayarlar'dan temizleyebilirsiniz. Microsoft Store sürümünde bu klasör uygulamaya özeldir ve uygulamayı kaldırdığınızda Windows tarafından silinir.

### Uygulama içi satın alma

Tek seferlik **Pro** eklentisinin satın alınması tamamen Microsoft Store üzerinden yapılır. Ödeme ve kart bilgileriniz geliştiriciyle paylaşılmaz. FolioPeek, Windows'un Store bileşeninden yalnızca Pro eklentisinin fiyatını ve sizde etkin olup olmadığını sorar.

### Bağlantılar

Uygulama içindeki gizlilik politikası ve hata bildirimi bağlantıları varsayılan tarayıcınızda, Windows ayarları bağlantıları Windows Ayarları'nda açılır. Bir PDF'in içindeki web bağlantısına tıkladığınızda (ayarınıza göre önce sorularak) tarayıcınızda açılır. Dış sayfalar kendi gizlilik politikalarına tabidir.

### Paylaşım

FolioPeek hiçbir veri toplamadığı için üçüncü taraflarla paylaşılan bir kullanıcı ya da belge verisi yoktur.

### Çocuklar

FolioPeek, 13 yaş altındaki çocuklar dahil kimseden kişisel veri toplamaz.

### Değişiklikler ve iletişim

Bu politika, yeni bir yetki ya da veri işleme eklendiğinde güncellenir ve en üstteki tarih yenilenir. Sorularınız için [zeynelumitkorkmaz@gmail.com](mailto:zeynelumitkorkmaz@gmail.com?subject=FolioPeek) adresine e-posta gönderebilir ya da [GitHub Issues](https://github.com/umitkrkmz/FolioPeek/issues) sayfasını kullanabilirsiniz. Yardım ve sık sorulanlar: [SUPPORT.md](SUPPORT.md).

---

## English

### In short

* No account or sign-in required.
* No ads, tracking, analytics or telemetry.
* No developer servers exist.
* FolioPeek **never connects to the internet**; the app package declares no network capability (`internetClient`).

### Your documents

* The PDFs you open are processed only on your PC, with Windows' own PDF and text recognition components and the libraries inside the app. No document content ever leaves your device.
* The open file is not changed unless you save. Files you save or export are written only where you choose. To prevent data loss, a temporary file is written first and replaces the target only after it has been checked.
* **Signature:** A signature you create is not stored on your PC; it is kept in memory only while the app is open ("Use last signature") and is gone when you close the app. Once you place it in a document and save, it becomes part of that document.
* **Note author:** If you enter a name in Settings, it is written as the author of the notes you add and travels with the document you save. You can leave it empty.
* **Document properties:** Information such as title and author is read from the document itself. Values you edit or clear with Pro are written only to the new file you save.
* **Clipboard:** When you copy, the selected text or area goes only to the Windows clipboard.
* **Text recognition:** The text recognition language packs installed in Windows are used. For a missing pack, FolioPeek only opens Windows' language settings.

### Data stored on your PC

All of it lives in `%LOCALAPPDATA%\FolioPeek`, on this PC only:

* **settings.json — settings:** language, theme and accent colour, reading mode, zoom, note colours and the note author name; paths of recently opened documents and when they were opened; if you choose, the last page you read and the open tabs.
* **license.dat — Pro license cache:** If you bought the Pro add-on, its status is encrypted with the Windows Data Protection API (DPAPI) so the app can open as Pro offline too.
* **error.log — error log:** If an unexpected error occurs, only technical error details are written; document content is never logged.

You can clear the recent documents list in Settings. In the Microsoft Store version this folder belongs to the app and Windows removes it when you uninstall FolioPeek.

### In-app purchase

The one-time **Pro** add-on is bought entirely through the Microsoft Store. Payment and card details are never shared with the developer. FolioPeek only asks Windows' Store component for the add-on's price and whether it is active for you.

### Links

The privacy policy and issue links in the app open in your default browser; links to Windows settings open in Windows Settings. A web link inside a PDF opens in your browser when you click it (after asking first, depending on your setting). External pages are governed by their own policies.

### Sharing

Because FolioPeek collects no data, no user or document data is shared with third parties.

### Children

FolioPeek does not collect personal information from anyone, including children under 13.

### Changes and contact

This policy is updated whenever a new capability or data handling is added, and the date at the top is renewed. For questions, e-mail [zeynelumitkorkmaz@gmail.com](mailto:zeynelumitkorkmaz@gmail.com?subject=FolioPeek) or use the [GitHub Issues](https://github.com/umitkrkmz/FolioPeek/issues) page. Help and common questions: [SUPPORT.md](SUPPORT.md).
