# First-Repo-Learn-Github
Learning Git &amp; GitHub fundamentals with simple examples

🚀 First-Repo-Learn-Github 🌟
👋 Git ve GitHub temellerini basit örneklerle öğrenmek amacıyla oluşturduğum ilk projeme hoş geldiniz! (Learning Git & GitHub fundamentals with simple examples)

🛠️ Bu repoda, sıfırdan bir repo nasıl oluşturulur adım adım tecrübe ediyor ve GitHub üzerinde karşılaştığım temel yapılandırma ayarlarını not alıyorum.

📚 Öğrendiğim Temel Kavramlar

Yeni bir proje başlatırken karşımıza çıkan bazı temel ayarlar ve anlamları:

📝 Description: Projenizin ne işe yaradığını, hedefini ve içeriğini diğer kullanıcılara kısaca özetlediğiniz bilgi alanıdır.

👁️ Choose visibility: Deponuzun dünyadaki herkes tarafından (Public) veya sadece sizin belirlediğiniz kişiler tarafından (Private) görünür olmasını seçtiğiniz ayardır.

📖 README: Projenizin ana sayfasında yer alan, ziyaretçilere projenin amacı, içeriği ve nasıl kullanılacağı hakkında rehberlik eden tanıtım dosyasıdır.

🚫 .gitignore: Git'in takip etmesini ve uzak depoya yüklemesini istemediğiniz kişisel, gizli veya gereksiz derleme dosyalarını belirttiğiniz metin dosyasıdır.

⚖️ License: Yazdığınız kodun başkaları tarafından hangi yasal şartlar altında kullanılabileceğini, paylaşılabileceğini veya değiştirilebileceğini belirleyen belgedir.Ben bu projede kodlarımın herkes tarafından özgürce kullanılıp geliştirilebilmesi için esnek ve açık kaynak dostu olan MIT Lisansı'nı kullandım.

------------------------------------------------------------------------------------------------------------------------

🤔 Git ve GitHub Nedir? Farkları Nelerdir?

🛠️ Git Nedir?
Git, yazılım projelerinde yapılan değişiklikleri kaydetmeye ve yönetmeye yarayan, bilgisayarınızda çalışan (lokal ve dağıtık) bir versiyon kontrol sistemidir. Bir komut satırı aracı olarak kurulur ve çalışır.

⏳ Geçmişi Tutar & Geri Alma: Kodların versiyon geçmişini kaydeder. Yanlış bir değişiklik yapıldığında kolayca önceki sürüme dönülmesini sağlar.

👥 Paralel Çalışma: Bir ekip içinde farklı özelliklerin aynı anda, birbirini etkilemeden canlı bir şekilde geliştirilmesine olanak tanır.

🔍 Değişiklik Takibi: Hangi kodun, ne zaman ve kim tarafından yazıldığını/değiştirildiğini detaylıca takip etmemizi sağlar.

🌐 GitHub Nedir?
GitHub, Git ile yönetilen projelerinizi internet üzerinde barındırabileceğiniz (repo barındırma), grafik arayüz (GUI) sunan çevrimiçi bir platformdur. Kısaca "Git + Sosyal/Online Ortam" diyebiliriz. İster komut satırı (CMD) üzerinden isterseniz de GitHub Desktop masaüstü uygulaması ile projelerinizi yönetebilirsiniz.

🤝 Ekip Çalışması ve Kod Paylaşımı: Takım üyelerinin aynı proje üzerinde rahatça çalışmasına imkan verir. Açık kaynak projelerinizi yayınlayabilir veya özel projelerinizi güvenle yedekleyebilirsiniz.

⏪ Eski Bir Dost: SVN (Apache Subversion)

Git'ten önce oldukça yaygın olan SVN, Git gibi dağıtık bir yapıda değildir. Her şeyin tek bir sunucuda tutulduğu merkezi bir mantıkla çalışır ve günümüzde yerini daha modern olan Git'e bırakmıştır.

🖥️ Temel Terminal ve Dosya Yönetim Komutları

Projelerimizi komut satırında yönetirken sıkça kullandığımız temel komutlar:

📂 cd Desktop : Masaüstü dizinine geçiş yapar.

📁 mkdir <klasör_adı> : Yeni bir klasör oluşturur.

➡️ cd <klasör_adı> : Oluşturulan klasörün içine girer.

📄 touch index.html : Klasör içinde yeni bir dosya (örneğin index.html) oluşturur.

📋 ls : Bulunduğunuz dizindeki dosya ve klasörleri listeler.

🍎 open . : (Mac için) Bulunduğunuz klasörü dosya yöneticisinde açar.

🪟 explorer . : (Windows için) Bulunduğunuz klasörü dosya gezgininde açar.

💻 code . : Bulunduğunuz klasörü doğrudan VS Code editöründe açar.

⚙️ Sık Kullanılan Git Komutları

🌱 git init : Bulunduğunuz klasörde yeni bir Git deposu oluşturur.

📥 git clone <url> : İnternetteki mevcut bir depoyu (repoyu) bilgisayarınıza indirir.

➕ git add . : Yapılan tüm değişiklikleri kaydedilmek üzere sahneye (staging area) ekler.

💾 git commit -m "Mesaj" : Sahneye alınan değişiklikleri açıklayıcı bir mesajla beraber kaydeder.

🚀 git push : Bilgisayarınızdaki yerel güncellemeleri GitHub'a (uzak depoya) gönderir.

🔄 git pull : GitHub'daki güncel değişiklikleri bilgisayarınıza çeker.

------------------------------------------------------------------------------------------------------------------------

🛠️ Sıfırdan Proje Oluşturma ve GitHub'a Gönderme Adımları

Terminali açtıktan sonra sırasıyla şu adımları izleyerek projemizi yerelden (bilgisayardan) buluta (GitHub'a) taşıyoruz:

1️⃣ Klasör ve Dosya Oluşturma (Temel Terminal İşlemleri)

📂 cd Desktop : Masaüstüne geçiş yaparız.

📁 mkdir <klasör_adı> : Masaüstünde yeni bir klasör oluştururuz.

➡️ cd <klasör_adı> : Oluşturduğumuz klasörün içine gireriz.

📄 touch index.html : Klasör içinde index.html adında boş bir dosya oluştururuz.

📋 ls : Klasörün içindekileri listeler, dosyamızın başarıyla oluştuğunu teyit ederiz.

🍎 open . (Mac) veya 🪟 explorer . (Windows) : Bulunduğumuz klasörü görsel bir pencere olarak açar.

💻 code . : Projemizi doğrudan VS Code editörü içinde açar.

2️⃣ Git'i Başlatma ve Durum Kontrolü

🔍 git status : Depomuzun o anki durumunu gösterir. (Eğer henüz Git başlatılmadıysa hata verir).

🌱 git init : Bulunduğumuz klasörü bir Git deposu (repository) haline getiririz. VS Code'da yeni eklediğimiz dosyanın yanında U (Untracked - Takip Edilmeyen) harfi belirir.

❓ git status : Tekrar durum kontrolü yaptığımızda index.html dosyasının kırmızı renkte olduğunu görürüz. Bunun nedeni, Git'in dosyanın varlığını bilmesi ama henüz değişiklikleri takip etmeye başlamamasıdır.

3️⃣ Dosyaları Sahneye Alma ve Kaydetme (Commit)

➕ git add . : DİKKAT! Bu komut dosyaları GitHub'a göndermez. Yapılan değişiklikleri paketlenmek üzere Git'in "Sahne"sine (Staging Area) ekler.

✅ git status : Dosyaların artık yeşil renge döndüğünü ve "Changes to be committed" (Kaydedilmeye hazır) aşamasına geldiğini görürüz.

💾 git commit -m "ilk commit mesajım" : Sahnedeki değişikliklerin kesin bir fotoğrafını çeker ve kendi bilgisayarımıza kaydeder. VS Code'daki U harfi artık kaybolur çünkü dosya güvenli bir şekilde kayıt altına alınmıştır.

🧹 git status : Şimdi durum sorguladığımızda "Nothing to commit, working tree clean" mesajını alırız. Yani yerel bilgisayarımızda kaydedilecek başka hiçbir şey kalmamıştır, her şey tertemizdir.

4️⃣ GitHub ile Bağlantı Kurma ve Kodları Fırlatma

🌿 git branch -M main : Eskiden "master" olarak isimlendirilen ana çalışma dalımızın adını, güncel standartlara uyarak "main" olarak değiştiririz.

🔗 git remote add origin [https://github.com/KULLANICI_ADIN/REPO_ADIN.git](https://github.com/KULLANICI_ADIN/REPO_ADIN.git) : Bilgisayarımızdaki yerel klasör ile internetteki (GitHub'daki) uzak depoyu birbirine bağlarız.

🚀 git push -u origin main : Ve mutlu son! Bilgisayarımızda kaydettiğimiz (commit attığımız) tüm dosyaları GitHub sunucularına göndeririz.

------------------------------------------------------------------------------------------------------------------------

🖥️ VS Code Arayüzü (GUI) ile Kod Gönderme Rehberi

Terminal komutlarını ezberlemek istemediğimizde veya günlük çalışma akışımızı hızlandırmak istediğimizde, VS Code'un sol menüsünde yer alan Source Control (üzerinde yol ayrımı olan dal simgesi 🌿) panelini kullanabiliriz.

İşte arayüzdeki işlemlerin terminaldeki karşılıkları:

1️⃣ Değişiklikleri Sahneye Al (Staging)
Dosyalarında bir değişiklik yapıp kaydettiğinde, Source Control panelindeki "Changes" (Değişiklikler) başlığı altında görünürler.

🖱️ Arayüzde Ne Yapıyoruz? Değiştirilen dosyaların veya "Changes" yazısının hemen yanındaki + (Artı) simgesine tıklayarak dosyaları "Staged Changes" kısmına alırız.

💻 Terminaldeki Karşılığı: git add .

2️⃣ Değişiklikleri Kaydet (Commit)
Sahneye aldığımız dosyaları, ne değişiklik yaptığımızı belirterek yerel bilgisayarımıza kaydetme adımıdır.

💬 Arayüzde Ne Yapıyoruz? Üstteki boş "Message" kutusuna yaptığımız değişikliği anlatan kısa bir not yazarız (Örn: index.html güncellendi). Ardından hemen altındaki mavi Commit butonuna (veya üstteki ✓ simgesine) tıklarız.

💻 Terminaldeki Karşılığı: git commit -m "index.html güncellendi"

3️⃣ GitHub'a Gönder ve Eşitle (Push / Sync)
Yerel bilgisayarımızda kaydettiğimiz bu değişiklikleri internetteki (GitHub) depomuza fırlatma vaktidir.

🔄 Arayüzde Ne Yapıyoruz? Commit işlemini tamamladıktan sonra beliren mavi renkli Sync Changes (Değişiklikleri Eşitle) butonuna tıklarız. Bu buton arka planda hem yeni değişiklikleri çeker hem de bizimkileri gönderir.

💻 Terminaldeki Karşılığı: git push (ve öncesinde varsa git pull)

👤 Git'e Kendinizi Tanıtın (Kimlik Ayarları)

Eğer bilgisayarınızda Git'i ilk kez kurup kullanıyorsanız, dosyalarınızı kaydetmeye (Commit) çalıştığınızda Git size "Sen kimsin?" (Author identity unknown) şeklinde bir hata verebilir. Çünkü Git, takım çalışmalarında karışıklık olmaması için yazdığınız kodların kimin tarafından yapıldığını kayıt altına almak ister.

Bunu çözmek için terminale sırasıyla şu iki komutu girerek kendinizi tanıtmanız yeterlidir:

📛 Adınızı belirleyin:
git config --global user.name "Adınız Soyadınız"

📧 GitHub E-postanızı belirleyin:
git config --global user.email "githuba_kayitli_epostaniz@mail.com"

------------------------------------------------------------------------------------------------------------------------

⏳ Uzun Bir Aradan Sonra Projeye Dönüş (Geri Dönüş Ritüeli)

Bilgisayarı kapatıp günler sonra projemize tekrar döndüğümüzde baştan git init veya git remote add gibi kurulum komutlarını girmemize gerek yoktur. Git, projemizin geçmişini ve GitHub bağlantısını sonsuza dek hatırlar. Sadece klasörümüzün içine girip (cd klasor_adi) şu rutin adımları izlememiz yeterlidir:

1️⃣ Durum Kontrolü (Röntgen Çekmek)
Masaya oturduğumuzda ilk iş, projenin ve Git'in ne durumda olduğunu kontrol etmektir.

💻 Komut: git status

🖥️ Terminal Çıktısının Anlamı:

On branch main 👉 Doğru yerde, ana daldasınız.

Your branch is up to date with 'origin/main' 👉 Bilgisayarınızdaki dosyalar GitHub'daki deponuzla kelimesi kelimesine aynı ve güncel.

nothing to commit, working tree clean 👉 Kaydedilmeyi bekleyen yeni bir değişiklik yok, çalışma masanız tertemiz.

2️⃣ İnternetteki Değişiklikleri Çekme (Senkronizasyon)
Biz yokken GitHub üzerinden (veya başka bir ekip arkadaşımız tarafından) projede bir değişiklik yapılmış olma ihtimaline karşı bilgisayarımızı güncelleriz.

💻 Komut: git pull origin main

🖥️ Terminal Çıktısının Anlamı:

Eğer Already up to date. yazıyorsa, GitHub'da yeni bir kod yoktur, zaten en güncel sürüme sahibiz demektir. Güvenle işe başlayabiliriz.

3️⃣ Editörü Aç ve Çalışmaya Başla
Her şeyin temiz ve güncel olduğundan emin olduktan sonra kod editörümüzü açar ve projemize kaldığımız yerden devam ederiz.

💻 Komut: code . (VS Code'u bulunduğumuz klasörde açar)

------------------------------------------------------------------------------------------------------------------------

🕰️ Zaman Makinesi: Git Log (Geçmişi İncelemek)

Projeye başından beri kimin, ne zaman, hangi kodları eklediğini görmek için Git'in "günlük" özelliğini kullanırız.

💻 Komut: git log

Bu komutu yazdığımızda karşımıza geçmişten günümüze doğru tüm kayıtların (commit) detaylı bir listesi çıkar:

🆔 commit 60abf... : Değişikliğin Git dünyasındaki benzersiz kimlik numarasıdır (Hash kodu). Eski bir sürüme dönmek için bu kod kullanılır.

📍 (HEAD -> main, origin/main) : Şu an projenin en güncel noktasında (HEAD) olduğumuzu ve bilgisayarımız ile GitHub'ın tam senkronize olduğunu gösterir.

👤 Author: Furkan Öztürk <mail@...> : Değişikliği kimin yaptığını gösterir. (Kimlik doğrulama ayarlarımızın çalıştığının kanıtıdır).

🕒 Date: Sat May 2... : O kaydın tam olarak hangi gün ve saatte yapıldığını belirtir.

💬 "readme güncellendi" : Değişikliği kaydederken yazdığımız açıklama (commit) mesajıdır.

🛑 ÖNEMLİ İPUCU - Log Ekranından Çıkmak: Geçmiş kayıtlar çok uzunsa, terminal hepsini bir ekrana sığdıramaz ve ekranın en altında : (iki nokta) işareti belirir. Sayfada aşağı inmek için Enter tuşunu kullanabilirsiniz. İşiniz bittiğinde bu ekrandan çıkıp normal komut satırına dönmek için klavyeden sadece q (quit/çıkış) tuşuna basmanız yeterlidir!