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
