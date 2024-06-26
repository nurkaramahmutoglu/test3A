**Selenium İde Commands (Selenyum İde Komutları)**

Web tarayıcılarını otomatize etmek için kullanılan Selenium WebDriver ile birlikte çalışan bir dizi komuttur. 
Bu komutlar, web uygulamalarındaki çeşitli işlemleri kaydetmenize ve yürütmenize olanak tanır. 
Genellikle kayıt ve oynatma aracı olarak adlandırılır.Çünkü kullanıcı arayüzü elementleriyle etkileşim kurma adımlarını kaydetmenize ve ardından bu kaydı daha sonra test
senaryolarını otomatikleştirmek için oynatmanıza izin verir.

İşte Selenium IDE'de kullanılan bazı temel komutlar:

**•	Open :** Bir web sayfasını URL'sine göre açar.

**•	Click :** Bir düğmeye, bağlantıya veya başka bir web öğesine tıklar.

**•	Type :** Bir metin kutusuna veya başka bir giriş alanına metin yazar.

**•	Select :** Bir açılır listeden bir öğe seçer.

**•	Verify :** Web sayfasındaki bir öğenin metnini, değerini veya varlığını doğrular.

**•	Wait :** Belirli bir süre veya bir öğenin görünür olması gibi belirli bir koşul gerçekleşene kadar bekler.

**•	Execute Script :** JavaScript kodunu çalıştırır.

**•	VerifyElementPresent :** Belirtilen web öğesinin varlığını doğrular.

**•	Select :** Bir dropdown menüsünden bir öğe seçer.

**•	AssertText :** Belirtilen web öğesinin metin içeriğini doğrular.

**•	WaitForElementPresent :** Belirtilen web öğesinin görünmesini bekler.

**•	Store :** Belirtilen değeri bir değişkende saklar.

**•	Echo :** Konsola bir mesaj yazdırır.

**•	RunScript :** Belirli bir JavaScript kodunu çalıştırır.

**•	Pause :** Testi belirli bir süre bekletir.

Bu komutlar, Selenium IDE'de test senaryoları oluştururken kullanılabilir. Kullanıcılar kaydettikleri eylemleri düzenleyebilir, yeniden sıralayabilir ve test senaryolarını
oluştururken ihtiyaçlarına göre bu komutları ekleyebilir veya çıkarabilirler.
Bu komutların yanı sıra, Selenium IDE daha karmaşık işlemler için koşullu ifadeler ve döngüler gibi ek özelliklere de sahiptir.
Selenium IDE komutları, genellikle Selenese (Selenium IDE için kullanılan komut dili) olarak adlandırılır. 
Selenese komutları, insan tarafından okunabilir bir formatta yazılır ve Python, Java, C# gibi çeşitli programlama dillerine dönüştürülebilir. 
Bu sayede otomasyon testlerini kod yazarak da oluşturabilirsiniz.

Selenium IDE'nin Kullanım Alanları:

**1)Web uygulamalarının işlevsellik testleri**

 Bir web uygulamasının gereksinimlerini ve işlevselliğini doğrulamak için gerçekleştirilen testlerdir. Bu testler, kullanıcıların uygulama üzerinde gerçekleştirebilecekleri eylemleri simüle eder ve uygulamanın beklendiği gibi çalışıp çalışmadığını kontrol eder.

İşlevsellik testleri genellikle aşağıdaki türleri içerir:

**1. Temel işlevsellik testleri :** Web uygulamasının en temel işlevlerini doğrulamayı amaçlar. Örneğin, kullanıcı girişi, form gönderimi, sayfa gezintisi gibi temel işlevler bu kategoriye girer.

**2. Kullanıcı senaryoları testleri :** Bu testler, kullanıcıların uygulama üzerinde gerçekleştirebileceği belirli senaryoları simüle eder.
   Örneğin, bir ürünü sepete ekleme, satın alma işlemi gibi tipik kullanıcı senaryoları bu kategoriye girer.

**3.Veri girişi ve doğrulama testleri :** Bu testler, uygulamaya girilen verilerin doğru şekilde işlendiğini ve saklandığını doğrular. 
  Örneğin, bir formdaki giriş alanlarına geçerli ve geçersiz verilerin girilmesi ve sonuçların doğrulanması gibi testler bu kategoriye girer.

**4. UI (Kullanıcı Arayüzü) testleri :** UI testleri, web uygulamasının kullanıcı arayüzünün doğru şekilde çalışıp çalışmadığını kontrol eder. Bu testler, sayfa düzeni, renkler, yazı tipi boyutları gibi görsel unsurları içerir.

**5. Hata durumları testleri :** Bu testler, uygulamanın hata durumlarına nasıl tepki verdiğini kontrol eder. Örneğin, geçersiz bir giriş yapılması durumunda doğru bir hata mesajı verilip verilmediği gibi durumlar bu testler de incelenir.

Web uygulamalarının kullanıcı beklentilerini karşılamasını sağlamak ve uygulamanın sağlam, güvenilir ve kullanılabilir olduğunu doğrulamak için önemlidir. 
Bu testler, uygulamanın gereksinimlere uygun olduğunu ve beklendiği gibi çalıştığını garanti altına alır.

**2)Gerileme testleri**
Bir yazılımın yeni bir değişiklik veya güncelleme sonrasında, mevcut işlevselliğinin hâlâ beklenen davranışları sergileyip sergilemediğini doğrulamak için gerçekleştirilen testlerdir. 
Bu testler, yazılımın yeni bir sürümü yayınlandığında veya mevcut kod tabanında yapılan herhangi bir değişiklikten sonra kullanılır.

Gerileme testleri, öncelikle mevcut işlevselliğin etkilenip etkilenmediğini belirlemek için gerçekleştirilir. Bir değişiklik veya güncelleme yapıldıktan sonra, bu testlerin amacı, mevcut test kapsamı içindeki özelliklerin hala çalışır durumda olduğunu doğrulamaktır.

Gerileme testleri aşağıdaki adımları içerebilir:

**1. Varolan test senaryolarının çalıştırılması :** Mevcut test senaryoları, değişikliklerden önce test edilmiş olan işlevselliği kapsar. Bu senaryolar, değişikliklerin ardından çalıştırılarak herhangi bir gerilemenin tespit edilmesi sağlanır.

**2. Test kapsamının güncellenmesi :** Değişikliklerden etkilenebilecek alanları belirlemek için test kapsamı gözden geçirilir ve gerektiğinde güncellenir.

**3. Yeni testlerin oluşturulması:** Değişikliklerden etkilenebilecek yeni işlevselliği test etmek için yeni test senaryoları oluşturulabilir.

**4. Manuel ve otomatik testlerin kullanılması:** Gerileme testleri, manuel olarak veya otomatik test araçları kullanılarak gerçekleştirilebilir. Otomatik testler, işlemi hızlandırabilir ve daha kapsamlı bir kapsama sağlayabilir.

**5. Değişikliklerin geri alınması :** Bir gerileme tespit edilirse, değişikliklerin geri alınması veya düzeltilmesi gerekebilir. Daha sonra testler tekrar çalıştırılarak sorunun giderilip giderilmediği doğrulanır.

Yazılımın sürekli gelişim sürecinde önemli bir rol oynar ve herhangi bir değişiklik veya güncelleme sonrasında yazılımın sağlamlığını ve işlevselliğini korumak için önemlidir.

**3)UI Testleri (Kullanıcı Arayüzü)**

Bir yazılımın kullanıcı arayüzünün doğru çalışıp çalışmadığını doğrulamak için yapılan testlerdir. Bu testler, bir web uygulaması, masaüstü uygulama veya mobil uygulama gibi çeşitli türdeki yazılımlar için uygulanabilir. UI testleri, kullanıcıların uygulama ile etkileşimini simüle eder ve kullanıcıların beklenen davranışları sergileyip sergilemediğini kontrol eder.

UI testleri genellikle aşağıdaki özellikleri doğrular:

**1. Sayfa Düzeni ve Görünüm :** Uygulamanın sayfa düzeninin ve görünümünün beklenen şekilde olduğunu doğrular.
     Örneğin, metin kutuları, düğmeler, bağlantılar, menüler gibi öğelerin doğru yerde ve doğru boyutta olup olmadığını kontrol eder.

**2. İşlevsellik :** Kullanıcıların uygulama üzerinde gerçekleştirebileceği işlevleri doğrular. 
     Örneğin, bir düğmeye tıklama, bir formu doldurma, bir bağlantıya tıklama gibi işlevleri test eder.

**3.Navigasyon :** Kullanıcıların uygulama içinde gezinme yeteneklerini kontrol eder. 
   Örneğin, menüler arasında geçiş yapma, sayfa içi bağlantıları takip etme gibi navigasyon özelliklerini test eder.

**4. Form Girişi ve Doğrulama :**  Kullanıcıların form alanlarına veri girişi yapabilmesini ve bu girdilerin doğru şekilde işlendiğini doğrular. 
     Örneğin, bir kullanıcının bir kayıt formunu doldurup göndermesini ve sonucun başarılı olup olmadığını kontrol eder.

**5. Hata Durumları :** Uygulamanın hata durumlarında nasıl davrandığını kontrol eder. Örneğin, geçersiz bir giriş yapıldığında veya bir bağlantı hatası oluştuğunda uygulamanın doğru bir şekilde tepki verip vermediğini test eder.

UI testleri genellikle otomatik test araçları veya yazılımları kullanılarak gerçekleştirilir. 
Bu araçlar, UI elementlerine otomatik olarak erişir ve kullanıcı etkileşimlerini simüle eder. Böylece, yazılımın kullanıcı arayüzünün doğru çalışıp çalışmadığını hızlı bir şekilde kontrol etmek mümkün olur.
