# Kendi barındırdığınız veya açık kaynaklı bir Canvas ortamında Feedback Studio için LTI 1.3'ü yapılandırma
## Başlamadan önce
- [ ] En son sürüm açık kaynaklı Canvas'ı kullandığınızdan emin olun.
- [ ] En son sürüm açık kaynaklı Canvas'ın örneğinizde Derin Bağlantı'nın etkinleştirildiğinden emin olun.
- [ ] Bu entegrasyonu tamamlamak için hem Canvas yöneticisi hem de Turnitin yöneticisi gereklidir. Bunlar iki farklı kişi ise, entegrasyonun çalışması için birlikte çalışmalarını sağlayın.
- [ ] Kendi barındırdığınız ortam için yayıncı yapılandırmasının ne olduğunu bildiğinizden emin olun. Varsayılan olarak, normalde https://canvas.instructure.com şeklindedir, ancak bu değiştirilebilir. Bu nedenle, devam etmeden önce bu alanın ne olduğunu onaylayın, aksi takdirde entegrasyon tamamlanamaz.

## Turnitin'de ilk ayarlar
1. Küresel bir kurumun üyesiyseniz, `turnitin.com` üzerinden Turnitin hesabınıza giriş yapın. Alternatif olarak, Birleşik Krallık'taki bir kurumun üyesiyseniz `turnitinuk.com` adresinden giriş yapın.
3. Ekranın üst kısmındaki açılır menüden **Yönetici** görünümünün etkinleştirildiğinden emin olun. Öğretmen veya Öğrenci seçiliyse, lütfen Yönetici olarak değiştirin.

<img width="272" height="148" alt="turnitin01" src="https://github.com/user-attachments/assets/742c42c3-90c5-42b9-91cf-6c9ce59d38d0" />

4. Yönetici ana sayfasındaki `Entegrasyonlar` sütununda `Yapılandırılmamış` veya `Yapılandırılmış` düğmesi görünecektir. Bu düğme, yapılandırma başarıyla tamamlandıktan sonra bile “yapılandırılmamış” durumunu koruyabilir. 

<img width="1171" height="451" alt="turnitin02" src="https://github.com/user-attachments/assets/fbdc7138-a2bd-4ff6-91d6-5ed0a66c3d43" />

> Canvas test ortamınızda zaten bir LTI 1.1 entegrasyonu kuruluysa, test ortamınız için aynı hesabı kullandığınızdan emin olun.
> Test ortamınıza hangi hesabın bağlı olduğundan emin değilseniz, Canvas yöneticisi olarak `Ayarlar`a gidin ve `Uygulamalar` sekmesini seçin. Uygulama Yapılandırmalarını Görüntüle'yi seçin. Turnitin LTI 1.1 entegrasyonunuzun yanındaki dişli simgesini seçin ve Düzenle'yi seçin. Burada listelenen Tüketici anahtarı, kullanmanız gereken Turnitin hesap kimliğidir.
> Turnitin LTI 1.1 uygulamasını daha sonra silmeniz gerekeceğinden, uygulamanın adını değiştirmenizi de öneririz.

5. Yapılandırma sayfasını açmak için LTI 1.3 düğmesini seçin.
> Yapılandırılmamış entegrasyonların durum düğmesi aktif görünmez. Ancak, LTI 1.3 entegrasyonları, başarılı bir entegrasyondan sonra bile kalıcı olarak aktif görünmez.

6. Bu, ilk LTI 1.3 kaydınızsa, ne yapacağınız hakkında fikir edinmek için giriş sayfasını inceleyin. Hazır olduğunuzda, `Başlayın` düğmesini seçin.
  Zaten önceden bir kaydınız varsa, kayıt panosundan `Yeni kayıt oluştur` düğmesini seçin.

<img width="1202" height="421" alt="turnitin04" src="https://github.com/user-attachments/assets/2d2235a3-43bd-4af6-b060-ffddcac2e274" />

8. Canvas Açık Kaynak ortamları için `Diğer'i (Other)` seçin.
9. Seçiminize göre, sayfa entegrasyonu tamamlamak için Canvas Open Source'a girmeniz gereken bilgilerle otomatik olarak doldurulacaktır.

<img width="1162" height="790" alt="turnitin05" src="https://github.com/user-attachments/assets/24318fb3-5497-4b58-b5fa-d15f17868bbb" />

10. Bu sayfayı açık tutun ve Canvas Açık Kaynak ortamınıza yeni bir sekme açın.

## Canvas tarafı ayarlar
1. Öncelike `/var/canvas/config/security.yml` dosyasında `lti_iss: 'https://canvas.instructure.com'` değeri `lti_iss: 'https://canvas_lms_urlniz'` olarak güncellenip canvas lms uygulaması yeniden başlatın.
2. Canvas ortamınızın `Yönetici` sayfasına gidin ve ardından `Geliştirici Anahtarları` bölümünü açın.
<img width="1178" height="487" alt="turnitin06" src="https://github.com/user-attachments/assets/3be17f20-c8da-4698-8212-f804c9b0386a" />
3. Alt menüden + LTI Anahtarı seçeneğini seçin. Bir yapılandırma ekranı görüntülenecektir. Aşağıdaki bilgileri kullanarak alanları doldurun:
||||


