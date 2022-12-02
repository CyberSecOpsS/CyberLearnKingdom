# CyberLearnKingdom 🔥💻
Cyber Learn Kingdom ile Siber Guvenliği öğren

Ücretsiz 🤩

Temel,Orta,Üst seviye 🚀

Ayrıntılı anlatım 😎

Türkçe 🇹🇷

##### NOT : Yazılarda sorun yaşanmaması için translate'yi Türkçe yapınız aksi takdirde bazı kelime hataları olabilmekte ❗
# Temel Network

Temel Network Siber Güvenliğin olmazsa olmazıdır

Üstelik temel Network kolay öğrenilen bir konudur

O zaman ilk derse geçelim 👇

#### AĞ NEDİR ? 

Ağ, temel olarak veri paylaşımı amacıyla çeşitli cihazları birbirine bağlayan teknolojidir.
örnek olarak internet. 

#### İSTEMCİ NEDİR ?

İstemciler, sunucudan alınan bilgileri istemelerini ve görüntüleyebilmelerini sağlayan yazılımla yüklü  
hostlardır. Internet Explorer gibi web tarayıcıları istemci yazılımlarına örnektir.

#### İP ADRESİ NEDİR ?

İnternete bağlı cihazların kimlik numarasıdır. İnternete bağlı olan her cihaz; bilgisayar, telefon, tablet bir IP'ye sahiptir. Böylece, ağ üzerinde birbirlerinden ayrılabilirler ve birbirleri ile IP aracılığıyla iletişim kurabilirler.

#### SUNUCU NEDİR ?

Sistemdeki verileri saklayan ve bu verileri istek geldiğinde istemciye ulaştıran yüksek performansa sahip bilgisayarın oluşturduğu yapıdır.

#### UÇ CİHAZ NEDİR ?

Verinin kullanıldığı tablet, telefon, bilgisayar ve yazıcı gibi aygıtlardır.

#### ROUTER NEDİR ?

IP paketlerini bir cihazdan başkasına aktarır, ağ katmanını kullanırlar.

#### FİREWALL NEDİR ? 
 Firewall kendisine verilen kurallar dahilinde üzerine gelen paketlerin geçmesine izin veren, engelleyen, yazılımdır.

#### PORT NEDİR ?

Bilgisayar arası iletişimde, port, iletişimin uç noktasıdır. Yazılımsal açıdan olaya bakıldığında, port belli bir işleme ait olan mantıksal bir yapıdır. Bir port, bir aktarım katmanı protokolünden ve 16 bitlik "port numarasından" oluşur. Portların kullandığı en yaygın aktarım katmanı protokolleri TCP ve UDP'dir.

#### OSİ MODELİ NEDİR ?

OSI modeli (Open System Interconnection) yedi katmandaki protokolleri göstermek için bir bilgisayar ağı çerçevesini oluşturur. Ağ oluşturma kurumlarındaki bir protokol, bir tür müzakere ve iki ağ kuruluşu arasında bir kuraldır. OSI modeli ISO (International Organization for Standardization) geliştirmiştir

+ Application
+ Presentation
+ Session
+ Transport
+ Network
+ Data link
+ Physical

#### OSI PHYSİCAL KATMANI

Physical (Fiziksel Katman) :

❗️Elektrik bağlantısı, ışık etkisi, radyo vb. sinyallerden sorumludur.

❗️Tekrarlayıcı cihazlar, kablolar, ethernet bu katman üzerinde çalışır

#### OSI DATA LİNK KATMANI

Data link (Veri Katmanı) :

❗️Veri bağlantı katmanları fiziksel katmana erişim ve kullanım ile ilgili kurallar belirler.

❗️Bu katmanda Ethernet ya da Token Ring olarak bilinen erişim yöntemleri çalışır ve bu erişim yöntemleri verileri kendi protokollerine uygun olarak işleyerek iletirler

❗️Veri bağlantı katmanlarının büyük bir bölüm ağ kartı içinde gerçekleşir.

#### Network ( Ağ Katmanı) :

❗️Bu katman sayesinde veri yönlendirici aracılığıyla yönlendirme sağlanması

❗️Anahtarlama ve yönlendirme teknolojisi bu katmanda çalışır.

❗️Veri paketini hedefe yönlendirilmesi ve iletilmesini sağlar.

❗️Yönlendirici bu katmanda çalışır

#### Transport (Taşıma Katmanı) :

❗️ Taşıma katmanı alt katmanlar (Transport Set) ve üst katmanlar (Application Set) arasında geçit görevi üstlenir.

❗️ Bu katmanlarda kesim (segment) halinde hareket eder.

❗️Verinin uçtan uca buluşmalarını sağlar, zamanında ulaşıp ulaşmadığını kontrol eder.
SPX, TCP, UDP gibi protokoller bu katmadan çalışır.

#### Session ( Oturum Katmanı) :

❗️birden fazla bilgisayarla aynı ve iletişim içinde ne zaman, düzenli bilgisayarla konuşabilmeyi sağlar.

❗️Oturum ve bağlantı koordinasyonu ile ilgilenir.

❗️ Uygulamalar arasındaki bağlantıların kurulması, yönetimi ve sonlandırılmasından sorumludur.

❗️ NetBIOS ve Sockets gibi protokoller farklı bilgisayarlarla aynı anda olan yönlendirmeleri yönetme imkanı sağlarlar.

#### Presentation ( Sunum Katmanı) :

 ❗️ Görevi gönderilecek olan verinin diğer bilgisayarı anlaşılacak şekilde çevrilmesidir.

❗️Datayı Şifreleme ve şifre çözme bu katmadan gerçekleşir

❗️GIF, JPEG, ASCII vb. bu katmanda çalışır.

#### Application (Uygulama Katmanı) :

❗️ posta ve diğer ağ yazılımı hizmetleri için uygulama hizmetinden sorumludur.

❗️ FTP, HTTP, SMTP, Telnet gibi protokoller burada çalışır.

#### SIRADAKİ KONU TCP/UDP

#### TCP (Transmission Control Protocol) nedir? 

 bilgisayarlar arasındaki iletişimin kayıpsız olarak ve küçük paketler hâlinde gerçekleştirilmesine yarayan bir protokoldür. Aslında veriyi alırken ya da karşı tarafa gönderirken verinin bütünlüğünü sağlaması ve kimlik doğrulaması yapması TCP protokolünün en önemli özelliğidir.

#### UDP “User Datagram Protocol Nedir ? 

UDP’nin temel işlevi verilerin gönderimini bağlantı kurulmaksızın gerçekleştirmektir, Tcp'ye göre daha hızlıdır, giden veriyi eksiksiz şekilde gidip gitmemesini kontrol etmez

### PORTLAR
En yaygın kullanılan port numaraları 

+ 20-21 : FTP 
+ 22      : SSH 
+ 23      : TELNET 
+ 25      : SMTP 
+ 53      : DNS 
+ 67-68 : DHCP
+ 80      : HTTP
+ 88      : KERBEROS 
+ 110   : POP3
+ 137  : NETBİOS 
+ 140  : IMAP 
+ 161  : SNMP
+ 443  : MİCROSOFT DC (Active directory) 
+ 445 : MİCROSOFT SQL SERVER 
+ 3306 : MYSQL

#### FTP ( FİLE TRANSFER PROTOCOL) NEDİR ?

Dosya Transfer Protokolü olarak biliniyor. İsminden de anlaşılacağı üzere dosya transfer işlemi için kullanılan bir protokoldür. İnternete bağlı iki bilgisayar arasında dosya transferini sağlayan bir protokoldür.

ftp://ftp.sitead

#### SSH NEDİR ? 

kullanıcıların sunucularını internet üzerinden kontrol edebilmelerini sağlayan ve sunucular üzerinde çeşitli değişiklikler ve düzenlemeler yapabilme olanağı tanıyan bir uzaktan yönetim güvenlik protokolüdür

#### TELNET NEDİR ?

Internet ağı üzerindeki çok kullanıcılı bir makineye uzaktaki başka bir makineden bağlanmak için kullanılır 

#### SMTP NEDİR ?

e-posta göndermek için sunucu ile istemci arasındaki iletişim şeklini belirleyen protokoldür.


#### IDOR (Insecure direct object reference) NEDİR?
bir saldırganın hedef web uygulamasında yetkisiz erişim elde etmesine ve eylemler gerçekleştirmesine olanak tanıyan bir web uygulama zafiyetidir.
