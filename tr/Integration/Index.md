# Entegrasyon Nasıl Yapılır?

![screenshoot](../../m/integrationhowto.png)

> Entegrasyona başlarken size özel test ortamı için `Api Url` , api `Key` , `Secret` ve `supplierid` bilgileri A101 tarafından temin edilir. Öncelikle test ortamında işlemler tamamlandıktan sonra prod ortamı için sadece bu bilgiler değişecektir.

>Entegrasyonu yaparken tüm endpointlere ulaşabileceğiniz swagger arayüzü sağlanmaktadır.

* Entegrasyon `REST Api` ler düzerinden yütülmektedir.
* Bazı doğrulamasız apiler haricinde tüm apiler `Basic Auth` kullanarak yürütülmektedir.
* Api urlleri  `https://{path_the_comlab_api}/sapigw/suppliers/{supplierid}/` şeklinde başlayarak ilgili fonksiyon eklenerek oluşur. `{supplierid}`,`{path_the_comlab_api}` sizelere iletilecektir.

* Entegrasyon ile ilgili detayları [Entegrasyon Nasıl Yapılır?](https://drive.google.com/file/d/17JQBJphLvFR09l-ie1Hbxj-IWHGkufpG/view?usp=sharing) dosyası içerisinde inceleyebilirsiniz. 
