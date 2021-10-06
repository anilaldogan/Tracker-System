# Tracker-System
ASP.NET MVC-Google Map API

Bu proje kapsamlı bir projedir bu sebeple daha ayrıntılı bilgi için benimle iletişime geçebilirsiniz: muh.anilaldogan@gmail.com
Son zamanların ve geleceğin ürünlerine bakış açımı geliştirmek için IoT projelerine ilgim artmış durumda. Peki IoT nedir? Internet Of Things (nesnelerin interneti) olarak da bilİnen, belirli bir haberleşme protokolü ile cihazların birbirleriyle haberleşmesi, veri paylaşması işlemleri gerçekleştirilen bir ağ-cihaz sistemidir. Bir IoT ekosistemi oluşturmak planlı ve kapsamlı bir çalıştırma gerektirir. Bu sebeple, olay kurgusunun ayrıntılı düşünülmüş olması önceliğimizdir. 

  Modüler kart biçiminde olan, enerjiyi verimli kullanan GPRS cihazları  bir çok noktada çözüm üretebilir fakat şirketin savunma sanayi misyonunu göz önünde bulundurarak, bu projeyi cihazların sahaya yollanan askeri  personelin konum verilerine ulaşmak için tasarladık.
	Kullanıcının bir ordu tabur komtanlığı olduğunu varsayarak tabur iç yapısında bulunan timlerin kümelenmesi ve takımın izlenmesi gibi olanaklar sağlanmıştır. Askeri personellerin harita üzerinde sıcaklık dağılımı gözlemlenebilmektedir. Askeri personelin her gün için verileri kayıt edilerek günlük rotaları oluşturulmaktadır.  Arayüz tasarımı mobil tasarıma da uygun olacak şekilde oluşturulmuştur. Bunların yanı sıra arayüz bilgilendirme bakımından basit ve anlaşılır bir şekilde kullanıcı odaklı tasarlanmıştır.
	Bir çok takip sistemi dışında bu takip sisteminin farklılıkları olarak azami veri kaybı ve sistem güvenliği, verinin doğruluğu ve sistemin verimli bir zaman aralığında çalışması gibi amaçlar ele alınacaktır.
  
# Kullanılan Teknoloji ve Araçlar:
ASP.NET MVC WEB
HeidiSQL (MySQL)
Google Map API
Bootstrap, W3Schools Web Tutorial

# GOOGLE MAP API DENEME VE GELİŞTİRME AMAÇLARI DIŞINDA ÜCRETLİ KULLANIM GEREKTİRDİĞİNDEN LÜTFEN KENDİ API KEY'İNİZİ ALIP "komuta_kontrol_sistemi" dosyası içerisindeki MVC Web projesinin front-end parçası olan "KKS.cshtml" İÇERİSİNDEKİ NOKTALI BÖLGEYE YAZINIZ!
<script src="https://maps.googleapis.com/maps/api/js?key=.........................&callback=initMap&libraries=drawing,visualization&v=weekly" defer></script>

# Web Servis ile GPRS Verisi Hakkında
"WebService1.asmx" dosyasında göreceğiniz fonksiyon GPRS verilerinin projemize giriş noktasıdır. Elimizde bir cihaz olmaması sebebiyle bir simülasyon ortamı oluşturmak istedik bu sebeple "gps_device" dosyası içerisindeki konsol uygulamasını web projesi localhost da koşarken çalıştırarak real time veri aktarımı gerçekleştirebilirsiniz.

# Proje üzerindeki yeni eklentiler:
Projede map ve veri kullanışlığını arttırmak amacıyla harita üzerinde sınırlar, şekiller, alan ve çap belirleme gibi kullanıcı etkileşimli yeni bir modül oluşturulma aşamasındayım. Bu sistemde Martı Tech firmasının Martı teknolojisi mobil arayüzündeki sınırlandırmalar ve yasak bölgelerin belirlenmesi gibi çözümler örnek alınabilir.

# Bu proje hobi ve teknoloji keşfi amacıyla oluşturulmuştur, hatalarım ve eksiklerim olabilir, lütfen düşünceleriniz ve geri bildirimleriniz için benimle iletişime geçin: muh.anilaldogan@gmail.com
