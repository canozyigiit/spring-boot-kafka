# spring-boot-kafka

Sadece bir kaynak sisteminiz ve bir hedef sisteminiz olduğunda, bu sistemler arası veri transferi yapmanız gerektiğinde çözüm basittir.
Ancak birçok kaynak, birçok hedef sisteminiz olduğunda ve hepsinin birbirleriyle veri transferi yapması gerektiğinde işler gerçekten karmaşık hale gelecek ve herbir sistemin birbiri ile entegrasyonu gerekecektir.
Bu entegrasyonlar . protokol seçimi, verilerin nasıl aktarılacağı (TCP, HTTP, FTP, JDBC, REST, SOAP vb), veri formatı, verilerin nasıl parse edileceği (JSON, CSV, XML, Avro, Thrift vb) gibi birçok zorluğu beraberinde getirir.
Bunlara ek olarak bir kaynak sisteme yapılan her entegrasyon o sistem üzerinde ek yük yaratacaktır.
Apache Kafka bu sorunları aşmak için doğru çözüm olacaktır. 
Sistemlerin birbirlerine bağımlıklıklarını ortadan kaldırarak, üzerlerindeki yüklerini de düşürür.
Apache Kafka, LinkedIn tarafından geliştirilmiş, şu an Apache yönetiminde açık kaynak olarak çoğunlukla Confluent şirketi tarafından bakımı ve geliştirimi yapılan bir projedir.
Dağıtık (distrubuted) bir veri akış (streaming) platformudur. Hataya dayanıklı, yatay olarak ölçeklenebilen, esnek bir mimariye sahiptir.
Son derece yüksek performans ile bir sistemden diğer sisteme 10 ms’den az bir gecikme(latency) ile neredeyse gerçek zamanlı olarak veri transferini mümkün kılmaktadır.
Mesajlaşma sistemi (messaging system) olabilir, etkinlik takibi(activity tracking) için, uygulama loglarını toplamak için, sağladığı API ile stream processing amacıyla kullanılabilir.
Big Data entegrasyonları için kullanılabilir. Gerçek zamanlı öneriler, kararlar ve bilgiler(insights) oluşturmak için kullanılabilir.
