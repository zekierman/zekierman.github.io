---
title: "Perdah · Support"
permalink: /perdah/support/
author_profile: false
toc: true
toc_label: "Contents"
---

[Türkçe](#türkçe) · [English](#english)

## Türkçe

Perdah, geleneksel ıslak tıraş meraklıları ve koleksiyoncuları için tasarlanmış bağımsız bir tıraş günlüğüdür. Sorularınız, sorun bildirimleriniz ve geri bildirimleriniz için bu kılavuzu inceleyebilir veya bizimle doğrudan iletişime geçebilirsiniz.

---

### Sıkça Sorulan Sorular (SSS)

#### 1. Verilerim nasıl yedeklenir ve geri yüklenir?
Perdah, girdiğiniz tıraş kayıtlarını, dolaptaki eşyalarınızı, jilet kullanım sayılarınızı ve ayarlarınızı öncelikle cihazınızda saklar. Aynı zamanda hesabınıza bağlı tek bir bulut yedeği Google Cloud Firestore (Avrupa / eur3 bölgesi) üzerinde otomatik olarak güncellenir. Hesabını Apple ya da Google ile bağladıysan, yeni telefonda ya da yeniden kurulumdan sonra aynı hesapla giriş yapınca kayıtların bu yedekten geri gelir. Hiç bağlanmamış hesap yalnız bu telefondadır: uygulamayı silmeden önce Ayarlar'dan JSON yedeği al. 

*Not:* Fotoğraflar gizliliğiniz ve cihaz kotanız için buluta yüklenmez; yalnızca yerel cihazınızda tutulur.

#### 2. Telefonumu değiştirdiğimde verilerimi nasıl aktarırım?
Verilerinizin yeni cihazınıza sorunsuz aktarılması için:
1. Eski cihazınızda **Ayarlar** bölümünden hesabınızı bir **Google** veya **Apple** hesabına bağladığınızdan emin olun.
2. Yeni cihazınızda Perdah'ı açtığınızda aynı Google veya Apple hesabıyla giriş yapın.
3. Tüm kayıtlarınız, dolap envanteriniz ve istatistikleriniz otomatik olarak yeni cihazınıza yüklenecektir.

Ayrıca verilerinizi istediğiniz zaman **Ayarlar > Dışa Aktar** adımıyla standart **JSON veya CSV** dosyası olarak cihazınıza indirebilir ve güvenle arşivleyebilirsiniz.

#### 3. Anonim hesabı Google veya Apple ile nasıl bağlarım?
Uygulamayı ilk açtığınızda sizin için güvenli bir anonim hesap oluşturulur. Bu hesabı kalıcı hale getirmek ve telefon değişince geri yükleyebilmek için:
- **Ayarlar > Hesap** menüsüne gidin.
- iOS cihazlarda **Apple ile bağla**, Android veya iOS cihazlarda **Google ile bağla** seçeneğine dokunun.
- Mevcut tüm tıraş geçmişiniz ve dolabınız kaybolmadan yeni hesabınıza bağlanacaktır.

#### 4. Hesabımı ve tüm verilerimi nasıl silerim?
Perdah'ta verilerinizin kontrolü tamamen sizdedir:
- **Uygulama İçinden Silme:** **Ayarlar > Hesabı ve tüm verileri sil** seçeneğine dokunun. Bu işlem, buluttaki Firestore yedeğinizi, kimlik doğrulama hesabınızı ve cihazınızdaki yerel veritabanını anında ve geri alınamaz şekilde siler.
- **E-posta Yoluyla Silme:** Dilerseniz kayıtlı e-posta adresinizden `zekierman01@outlook.com` adresine silme talebi iletebilirsiniz. Talebiniz en geç 30 gün içinde tamamlanır.

#### 5. Haftalık hatırlatıcılar çalışmıyor, ne yapmalıyım?
Hatırlatıcılar harici bir sunucudan değil, tamamen telefonunuzun yerel işletim sistemi tarafından tetiklenir:
1. Telefonunuzun **Ayarlar > Bildirimler > Perdah** bölümünden bildirim izinlerinin açık olduğunu doğrulayın.
2. Android kullanıyorsanız, telefonunuzun pil tasarrufu ayarlarının Perdah'ın arka plan bildirimlerini kısıtlamadığından emin olun ("Pil Optimizasyonunu Devre Dışı Bırak" / "Kısıtlamasız").
3. Perdah içinde **Ayarlar > Hatırlatıcı** bölümüne girip günü ve saati yeniden kaydedin.

#### 6. Sanal sabun kalıbı ve taslar nedir?
Uygulamanın ana ekranında duran nikel tas içindeki sanal sabun kalıbı, kaydettiğiniz her tıraşla birlikte aşınır ve 12 tıraşta bir eriyerek tamamlanır. Her tamamlanan kalıp döngüsüyle birlikte yeni tas modelleri açılır. Bu özellik yalnızca motivasyon amaçlı bir görsel ritüeldir; dolabınızdaki gerçek tıraş sabunlarınızın fiziksel gramajını veya durumunu etkilemez.

---

### İletişim ve Destek

Uygulama ile ilgili teknik sorunlar, hata bildirimleri veya önerileriniz için doğrudan geliştiriciyle iletişime geçebilirsiniz:

- **Geliştirici:** Zeki Erman
- **E-posta:** `zekierman01@outlook.com`
- **Konum:** Konya, Türkiye

## English

Perdah is an independent wet-shaving journal and gear tracker crafted for wet-shaving enthusiasts and collectors. If you have questions, feedback, or need assistance, please consult this guide or contact us directly.

---

### Frequently Asked Questions (FAQ)

#### 1. How are my data backed up and restored?
Perdah saves your shave entries, cabinet inventory, blade usage counter, and settings locally on your device. Concurrently, a single cloud snapshot is automatically kept in Google Cloud Firestore (Europe / eur3 region) associated with your user account. If you have connected your account with Apple or Google, signing in with the same account on a new phone or after reinstalling restores your journal and gear from this backup. An account that was never connected stays only on this phone: export a JSON backup from Settings before removing the app.

*Note:* Photos are never uploaded to the cloud to preserve your privacy and storage; they remain stored exclusively on your local device.

#### 2. How do I transfer my data when switching to a new phone?
To ensure a smooth transition to a new device:
1. On your old phone, open **Settings** and make sure you have linked your account to **Google** or **Apple**.
2. On your new phone, install Perdah and sign in using the same Google or Apple account.
3. Your shave logs, gear collection, and stats are restored on your new device.

You can also export your entire data at any time via **Settings > Export** as a standard **JSON or CSV** file for personal archiving.

#### 3. How do I link an anonymous account to Apple or Google?
When you first open Perdah, an anonymous account is created for you. To link it and enable seamless backup:
- Navigate to **Settings > Account** ("Hesap").
- Select **Connect with Apple** (on iOS) or **Connect with Google** (on Android/iOS).
- Your existing shaving history and cabinet inventory will be securely linked to your permanent login.

#### 4. How can I delete my account and all data?
You have full ownership and control over your information:
- **In-App Deletion:** Go to **Settings > Delete account and all data** (in Turkish: "Hesabı ve tüm verileri sil"). This action immediately and permanently deletes your Firestore cloud backup, your authentication account, and all local data stored on your device.
- **Email Deletion Request:** You may also send an email from your registered account to `zekierman01@outlook.com`. Your deletion request will be processed within 30 days.

#### 5. My weekly reminders are not firing. What should I do?
Reminders are scheduled locally on your device rather than sent from an external push server:
1. Ensure notifications are enabled under your phone's system **Settings > Notifications > Perdah**.
2. If using Android, verify that battery optimization settings do not restrict Perdah ("Allow background activity" or "Unrestricted battery usage").
3. In Perdah, navigate to **Settings > Reminder** ("Hatırlatıcı"), adjust your preferred day and time, and save your settings.

#### 6. What is the virtual soap bar and bowl collection?
The nickel lather bowl and virtual soap bar on the Today screen represent a visual ritual companion. With every logged shave, the virtual soap gradually depletes, resetting every 12 shaves to unlock new classic bowl designs. This feature is purely a visual progress milestone; it does not alter or track the physical gram weight of your actual physical shaving soaps in your Cabinet.

---

### Contact & Support

For technical assistance, bug reports, or feature suggestions, reach out directly to the developer:

- **Developer:** Zeki Erman
- **Email:** `zekierman01@outlook.com`
- **Location:** Konya, Turkey
