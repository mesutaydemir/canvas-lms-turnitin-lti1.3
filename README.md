# Kendi barındırdığınız veya açık kaynaklı bir Canvas ortamında Feedback Studio için LTI 1.3'ü yapılandırma
## Başlamadan önce
- [ ] En son sürüm açık kaynaklı Canvas'ı kullandığınızdan emin olun.
- [ ] En son sürüm açık kaynaklı Canvas'ın örneğinizde Derin Bağlantı'nın etkinleştirildiğinden emin olun.
- [ ] Bu entegrasyonu tamamlamak için hem Canvas yöneticisi hem de Turnitin yöneticisi gereklidir. Bunlar iki farklı kişi ise, entegrasyonun çalışması için birlikte çalışmalarını sağlayın.
- [ ] Kendi barındırdığınız ortam için yayıncı yapılandırmasının ne olduğunu bildiğinizden emin olun. Varsayılan olarak, normalde https://canvas.instructure.com şeklindedir, ancak bu değiştirilebilir. Bu nedenle, devam etmeden önce bu alanın ne olduğunu onaylayın, aksi takdirde entegrasyon tamamlanamaz.

## Turnitin'de ilk ayarlar
1. Küresel bir kurumun üyesiyseniz, `turnitin.com` üzerinden Turnitin hesabınıza giriş yapın. Alternatif olarak, Birleşik Krallık'taki bir kurumun üyesiyseniz `turnitinuk.com` adresinden giriş yapın.
2. Ekranın üst kısmındaki açılır menüden **Yönetici** görünümünün etkinleştirildiğinden emin olun. Öğretmen veya Öğrenci seçiliyse, lütfen Yönetici olarak değiştirin.
3. Yönetici ana sayfasındaki `Entegrasyonlar` sütununda `Yapılandırılmamış` veya `Yapılandırılmış` düğmesi görünecektir. Bu düğme, yapılandırma başarıyla tamamlandıktan sonra bile “yapılandırılmamış” durumunu koruyabilir. 
> Canvas test ortamınızda zaten bir LTI 1.1 entegrasyonu kuruluysa, test ortamınız için aynı hesabı kullandığınızdan emin olun.
> Test ortamınıza hangi hesabın bağlı olduğundan emin değilseniz, Canvas yöneticisi olarak Ayarlar'a gidin ve Uygulamalar sekmesini seçin. Uygulama Yapılandırmalarını Görüntüle'yi seçin. Turnitin LTI 1.1 entegrasyonunuzun yanındaki dişli simgesini seçin ve Düzenle'yi seçin. Burada listelenen Tüketici anahtarı, kullanmanız gereken Turnitin hesap kimliğidir.
> Turnitin LTI 1.1 uygulamasını daha sonra silmeniz gerekeceğinden, uygulamanın adını değiştirmenizi de öneririz.
