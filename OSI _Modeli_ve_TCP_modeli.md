**OSI MODELİ VE TCP MODELİ** <br/>

![OSI_ve_TCP_modelleri](https://github.com/user-attachments/assets/8542530b-08e1-45a7-905f-6811dad61829) <br/>

OSI  (Open Systems Interconnection) ve TCP/IP (Transmission Control Protocol/Internet Protocol) bilgisayar ağları ve iletişim protokolleri ile ilgili iki önemli modeldir.

**OSI Modeli** <br/>
OSI, yedi katmandan oluşan bir referans modelidir. Her katman, belirli bir işlevselliğe sahiptir ve ağ iletişimini standartlaştırmak için tasarlanmıştır. 

Katman 7- Uygulama Katmanı(Application) : Kullanıcı uygulamaları ile doğrudan etkileşimde bulunmakta olan katmandır. HTTP, FTP, DNS SSH, Telnet gibi protokolller örnek olarak söylenebilir.
Katman 6- Sunum Katmanı (Presentation)  : Verilerin biçimlendirilmesi ve şifrelenmesi bu katmanda sağlanmaktadır. GIF, JPEG, TIFF, EBCDIC, ASCII gibi prototokoller örnek olarak söylenebilir.
Katman 5- Oturum Katmanı (Session)      : İki cihaz arasında oturum açma ve kapama işlemlerini yönetir. NFS,RPC, X WİNDOWS SYSTEM, APPLE TALK SESSİON PROTOCOL gibi protokoller örnek verilebilir.
Katman 4- Taşıma Katmanı (Transport)    : Verilerin güvenilir bir şekilde iletilmesini sağlar.  TCP protokolü örnek olarak verilebilir.
Katman 3- Ağ Katmanı  (Network)         : Verilerin yönlendirilmesi ve adreslenmesi ile ilgilenir. IP, ARP,RARP,BOOTP,ICMP protokolleri örnek olarak verilebilir.
Katman 2- Veri Bağlantısı Katmanı (Data Link): Hatalı veri iletimini düzeltir ve çerçeveler oluşturur. Kablolu veya kablosuz ethernet kartımızın MAC adresini aldığımız ve ARP protokolünün çalıştığı katman olarak bilinmektedir.
SLIP, PPP protokolleri veri bağlantısı katmanına örnek olarak verilebilir.
Katman 1- Fiziksel Katman (Physical)    : Fiziksel iletim ortamı (kablolar, sinyaller) ile ilgilenir. IEEE 1394, DSL, ISDN protokolleri bu katmana örnek verilebilir.

**TCP/IP MODELİ** <br/>
TCP ve IP protokollerinin birleştirilmesiyle oluşturulan ağ cihazlarını birbirine bağlamak ve internet üzerinden iletişim kurmak için kullanılan bir iletişim modelidir. 
TCP/IP modeli 4 katmandan oluşmaktadır:
-Link katmanı: OSI katmanındaki 1.katman olan Fiziksel katman ile 2.katman olan veri bağlantısı katmanı birleşerek oluşan katman (Ethernet, FDDI, Token Ring, ATM, OC, HSSI vb.)
-Ağ Katmanı: IP adresleme ve yönlendirme işlevlerini üstlenir (IPv4,IPv6,ICMP,ICMPv6,IGMPve IPsec, bu katmanda kullanılan bazı protokoller).
-İletim Katmanı: Verilerin güvenilir bir şekilde iletilmesini sağlar (TCP, UDP).
-Uygulama (Application) Katmanı: TCP/IP modelinde, OSI Modelindeki Katman 5-6-7. katman Uygulama katmanında toplanmıştır.Kullanıcı uygulamalarının iletişim kurmasını sağlar (HTTP, FTP, SMTP).
