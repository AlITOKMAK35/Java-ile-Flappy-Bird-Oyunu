Flappy Bird

Proje Açıklaması
Bu proje, Java kullanılarak geliştirilen klasik Flappy Bird oyununun bir versiyonudur. Oyuncular, kuşu yukarı doğru zıplatmak için boşluk tuşunu kullanarak borular arasında geçmeye çalışırlar. Oyun, kuşun borulara çarpması veya ekranın altına düşmesi durumunda sona erer.

Özellikler

Kuş Kontrolü: Kuşu yukarı doğru zıplatmak için boşluk tuşunu kullanın. Kuş, yerçekimi nedeniyle sürekli aşağıya doğru hareket eder.

Borular: Borular ekranda rastgele aralıklarla ve yukarıdan aşağıya hareket eder. Oyuncunun borular arasında geçmesi gerekir.

Skor: Borular arasında başarılı bir şekilde geçtikçe skor artar. Skor ekranda gösterilir.

Oyun Sonu: Kuş borulara çarptığında veya ekranın altına düştüğünde oyun biter.

Gereksinimler

Java Development Kit (JDK): Projeyi derlemek ve çalıştırmak için Java JDK 8 veya üstü gereklidir.

Swing ve AWT Kütüphaneleri: GUI bileşenlerini ve grafik işlemleri için Java Swing ve AWT kütüphaneleri gereklidir.

Resim Dosyaları: flappybirdbg.png, flappybird.png, toppipe.png, ve bottompipe.png dosyaları proje dizininde bulunmalıdır.

Kurulum ve Çalıştırma

Kodun Yüklenmesi:

Kodunuzu bir Java IDE (IntelliJ IDEA, Eclipse vb.) ya da bir metin düzenleyiciye yapıştırın ve dosyayı FlappyBird.java olarak kaydedin.

Resim Dosyalarını Ekleyin:

flappybirdbg.png, flappybird.png, toppipe.png, ve bottompipe.png dosyalarını proje dizinine yerleştirin.

Derleme:

Komut satırını açın ve dosyanın bulunduğu dizine gidin.

Java dosyasını derlemek için şu komutu çalıştırın:

javac FlappyBird.java

Çalıştırma:

Derlenmiş sınıf dosyasını çalıştırmak için şu komutu kullanın:

java FlappyBird

Kullanım

Kuşu Kontrol Etme:

Boşluk tuşuna basarak kuşu yukarı zıplatabilirsiniz.

Borulara Dikkat Edin:

Borular arasında geçmeye çalışın. Borulara çarpmak veya ekranın altına düşmek oyunu sona erdirir.

Skor:

Borular arasında başarılı bir şekilde geçtikçe skor artar. Skor ekranın üst kısmında görüntülenir.

Kod Açıklamaları

Bird Class: Kuşun konumunu, boyutlarını ve resmini içerir.

Pipe Class: Boruların konumunu, boyutlarını, resmini ve geçti mi bilgisini içerir.

FlappyBird Class: Ana oyun mantığını içerir. Kuşun hareketini, boruların yerleştirilmesini, çarpışma kontrolünü ve oyun döngüsünü yönetir.

paintComponent(Graphics g): Oyun ekranını çizer.

draw(Graphics g): Arka planı, kuşu ve boruları çizer.

move(): Kuşun hareketini ve boruların hareketini günceller.

collision(Bird a, Pipe b): Kuşun borularla çarpışıp çarpışmadığını kontrol eder.

actionPerformed(ActionEvent e): Her döngüde oyunun güncellenmesini sağlar.

keyPressed(KeyEvent e): Boşluk tuşuna basıldığında kuşu yukarı zıplatır ve oyunu yeniden başlatır.

İletişim

Sorularınız veya geri bildirimleriniz için benimle iletişime geçebilirsiniz:

E-posta: alitokmak3535@gmail.com

GitHub: AlITOKMAK35 - https://github.com/AlITOKMAK35 -
