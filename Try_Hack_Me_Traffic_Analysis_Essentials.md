**Traffic Analysis Essentials (Trafik Analizi Temelleri)**

**Görev1-Giriş**

Ağ Güvenliği, ağa bağlı veri, uygulama, cihaz ve sistemlerin korunmasına yönelik işlemler bütünüdür. 
Siber güvenliğin önemli alt alanlarından biri olarak kabul edilmektedir. 
Ağ erişilebilirliği, bütünlüğü, sürekliliği ve güvenilirliğini sağlamak için mimarinin/altyapının sistem tasarımı, işletimi ve yönetimine odaklanır.
Trafik analizi (genellikle Ağ Trafik Analizi olarak adlandırılır), Ağ Güvenliği alanının bir alt alanıdır ve birincil odak noktası, sorunları ve anormallikleri belirlemek için ağ verilerini araştırmaktır.
Bu oda, Ağ Güvenliği ve Trafik analizinin temellerini kapsayacak ve Trafik/Paket Analizine adım atmanıza yardımcı olmak için bu disiplinlerin temel kavramlarını tanıtacaktır. 
Bu odada çalışmaya başlamadan önce “Ağ Temelleri” modülünü tamamlamanızı öneririz.

![Try_hackme_Görev-1](https://github.com/user-attachments/assets/c904c7e4-cbaa-4b53-99f3-83862dc11da0)

**Görev2-Network Security and Network Data (Ağ Güvenliği ve Ağ Veri)**
![networksecurity](https://github.com/user-attachments/assets/beaa79bd-203e-429b-bc65-7647b841ce69)

*Ağ Güvenliği*

Ağ Güvenliğinin temel kaygısı iki temel kavrama odaklanır: kimlik doğrulama ve yetkilendirme. 
Bu iki temel kavramın uygulanmasını sağlamak ve ölçmek için çeşitli araçlar, teknolojiler ve yaklaşımlar vardır ve bunların ötesine geçerek süreklilik ve güvenilirlik sağlar. 
Ağ güvenliği operasyonları, mevcut maksimum güvenlik yönetimini sağlamak için üç temel kontrol seviyesi içerir.

*Temel Ağ Güvenlik Kontrol Düzeyleri:*

![Temel_ag_güvenigi_kontrol](https://github.com/user-attachments/assets/8a3a0078-04b7-41f4-a12a-f75929e49dd5)

Bu kontrol seviyeleri altında iki ana yaklaşım ve birden fazla unsur bulunmaktadır.
Ağ güvenliği operasyonlarında kullanılan en yaygın unsurlar aşağıda açıklanmıştır.

Ana yaklaşımlar:

![Ana_yaklasinlar](https://github.com/user-attachments/assets/258d17fc-e64d-4780-9a01-5e46706f5068)

*Erişim Kontrolünün temel unsurları:*

![Erisim_kontrolu_temel_unsurlar](https://github.com/user-attachments/assets/409b08bc-b909-4b5e-80fa-8dc3c2f83325)

**Tehdit Kontrolünün temel unsurları:**
![Tehdit_kontrolu_unsur](https://github.com/user-attachments/assets/f00e5b29-ac75-425e-8b14-dff4646c563d)

*Tipik Ağ Güvenlik Yönetimi İşlemi verilen tabloda açıklanmıştır:*

![Tipik_ag_guvenlıgı](https://github.com/user-attachments/assets/4389de82-455b-40b3-8bb8-99147baca952)

**Yönetilen Güvenlik Hizmetleri**

Her kuruluşun belirli güvenlik alanları için özel gruplar oluşturmak için yeterli kaynağı yoktur.
Bunun birçok nedeni vardır: bütçe, çalışan beceri seti ve kuruluş büyüklüğü güvenlik operasyonlarının nasıl ele alınacağını belirleyebilir. 
Bu noktada, güvenlik ihtiyaçlarını sağlamak/geliştirmek için gereken çabayı yerine getirmek üzere Yönetilen Güvenlik Hizmetleri (MSS) devreye girer.
MSS'ler, hizmet sağlayıcılara dış kaynaklı olarak verilen hizmetlerdir.
Bu hizmet sağlayıcılara Yönetilen Güvenlik Hizmet Sağlayıcıları (MSSP'ler) denir. 
Günümüzde, çoğu MSS zaman ve maliyet açısından etkilidir, şirket içinde veya dış kaynaklı olarak yürütülebilir, katılımı kolaydır ve yönetim sürecini kolaylaştırır. 
MSS'nin çeşitli unsurları vardır ve en yaygın olanları aşağıda açıklanmıştır.
![yonetilen_guvenlik_hizmetleri](https://github.com/user-attachments/assets/2fb11aa0-c939-4e74-a55b-4cba66007bf1)

**Which Security Control Level covers contain creating security policies? (Hangi Güvenlik Kontrol Seviyesi güvenlik politikalarının oluşturulmasını kapsar?)**
**Cevap:** Administrative(Yönetimsel)

**Which Access Control element works with data metrics to manage data flow? (Hangi Erişim Kontrol öğesi veri akışını yönetmek için veri ölçümleriyle çalışır?)**
**Cevap:** Load Balancing (Yük dengeleme)

**Which technology helps correlate different tool outputs and data sources? (Farklı araç çıktıları ile veri kaynaklarının ilişkilendirilmesine hangi teknoloji yardımcı olur?)**
**Cevap:** Security Orchestration Automation and Response (Güvenlik Orkestrasyon Otomasyonu ve Yanıtı (SOAR))

**Görev-3 Trafik Analiz**
![Trafik_analiz](https://github.com/user-attachments/assets/e96a3f28-217f-47d3-88e5-de93075c8333)

*Trafik Analizi / Ağ Trafik Analizi**

Trafik Analizi, sistem sağlık sorunlarını, ağ anormalliklerini ve tehditleri tespit etmek ve bunlara yanıt vermek için ağ verilerini ve iletişim modellerini yakalama, kaydetme/izleme ve analiz etme yöntemidir. 
Ağ zengin bir veri kaynağıdır, bu nedenle trafik analizi güvenlik ve operasyonel konularda faydalıdır.
Operasyonel sorunlar sistem kullanılabilirlik kontrollerini ve performans ölçümünü kapsar ve güvenlik sorunları ağdaki anormallikleri ve şüpheli aktivite tespitini kapsar.

Trafik analizi ağ güvenliğinde kullanılan temel yaklaşımlardan biridir ve aşağıda listelenen ağ güvenliği operasyonlarının birden fazla disiplininin bir parçasıdır:

•	Ağ Koklama ve Paket Analizi (Wireshark odasında ele alınmıştır)
•	Ağ İzleme (Zeek odasında ele alınmıştır)
•	İhlal Tespiti ve Önleme (Snort odasında ele alınmıştır)
•	Ağ Adli Bilimi (NetworkMiner odasında ele alınmıştır)
•	Tehdit Avı (Brim odasında ele alınmıştır)

Trafik Analizinde kullanılan iki temel teknik vardır:

![Trafik_analizi_teknikleri](https://github.com/user-attachments/assets/8446f3cb-8621-42e9-b48d-6f9589af3317)

Trafik Analizinin Faydaları:
	Tam ağ görünürlüğü sağlar.
	Varlık takibi için kapsamlı temellendirmeye yardımcı olur.
	Anormallikleri ve tehditleri tespit etmeye/bunlara yanıt vermeye yardımcı olur.

**Trafik Analizi Hala Önemli mi?**
Güvenlik araçlarının/hizmetlerinin yaygın kullanımı ve bulut bilişime doğru artan geçiş, saldırganları tespit edilmekten kaçınmak için taktiklerini ve tekniklerini değiştirmeye zorluyor. 
Ağ verileri saf ve zengin bir veri kaynağıdır. 
Kodlanmış/şifrelenmiş olsa bile, garip, tuhaf veya beklenmedik bir desene/duruma işaret ederek yine de bir değer sağlar. 
Bu nedenle trafik analizi, gelişmiş tehditleri tespit etmek ve bunlara yanıt vermek isteyen herhangi bir güvenlik analisti için hala olmazsa olmaz bir beceridir.
Artık Trafik Analizinin ne olduğunu ve nasıl çalıştığını biliyorsunuz.

![View_site_butonu](https://github.com/user-attachments/assets/6bd9633e-3bcc-4935-a354-f21f8d6ce9f7)

Şimdi statik siteyi kullanarak bir trafik analizi işlemini simüle edin ve işaretleri bulun.

**Level-1 Kötü amaçlı IP adreslerinin tanımlanmasını ve filtrelenmesini simüle ediyor. Bayrak nedir?**
**Cevap:** THM{PACKET_MASTER}

**Level-2, kötü amaçlı IP ve Port adreslerinin tanımlanmasını ve filtrelenmesini simüle ediyor.Bayrak nedir?**
**Cevap:** THM{DETECTION_MASTER}


**Görev 4- Sonuç**
Tebrikler! "Trafik Analizi Temelleri" odasını yeni bitirdiniz.
Bu odada, ağ güvenliği ve trafik analizi kavramlarının temellerini ele aldık:
	Ağ Güvenliği İşlemleri
	Ağ Trafik Analizi
Artık "Ağ Güvenliği ve Trafik Analizi" modülünü tamamlamaya hazırsınız.

![son_gorev](https://github.com/user-attachments/assets/d6350480-d052-44ff-ba8c-ac9134bbb117)

