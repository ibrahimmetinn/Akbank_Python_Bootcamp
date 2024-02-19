# Akbank_Python_Bootcamp
 Akbank and Global AI bootcamp projects
# Library Management System (Kütüphane Yönetim Sistemi)
Bu projeyi tasarlama aşamalarım tümden gelim kuralına dayalıydı. Öncelikle Programın menüsünü tasarladım ve bu menü içerisinden sınıfa, sınıf içerisinden fonksiyonlara ulaştık.
![MENU](https://github.com/ibrahimmetinn/Akbank_Python_Bootcamp/assets/150549575/835a5ff9-ca03-4c0f-a668-1ace856a9e07)

Projemizin amacından bahsedelim. Projemizde amacımız,  bir kütüphane yönetim sistemi tasarlamak. Bu yönetim sisteminde kitapların çeşitli özellikleri ile kayıt altına alınması ve kullanıcı tarafından erişilmesi, kayıt altına alınan kitapların silinmesi.  Ve tabiki de bu programdan çıkış.  

![Menu_select](https://github.com/ibrahimmetinn/Akbank_Python_Bootcamp/assets/150549575/cc93b962-8ddb-4263-9e8e-3bedca65ae35)

Seçim ekranı while döngüsü ile kurulmuştur. Bu döngü kullanıcı tarafından girilen (1,2,3,q) değerler üzerine kuruludur. Bu noktada kullanıcı bir sayı girer. Veya q tuşu ile çıkma işlemi yapar. Eğer bu değerler dışında bir işlem gerçekleştirirse döngü yanlış değer girdiğini bu tanımlanan değerlerde sayı girmesi gerektiği uyarısını yapar.
![Menu](https://github.com/ibrahimmetinn/Akbank_Python_Bootcamp/assets/150549575/3271fd9c-e3ed-4eb1-aef8-bda00bc9fd35)
Öncelikle Class yani sınıf kavramından bahsedelim ve neden bu sistemi class(sınıf) kavramı üzerinden tasarladık. Direkt olarak değer değer giremez miydik? Tabi ki de girebiliriz  ancak, sınıf kullanmak kodunuzun daha organize olmasına yardımcı olacaktır.

### While döngüsü: 
While döngüsü program içerisinde sürekli olarak değer girebilmemizi ve fonksiyonlar arası gezinmemize olanak sağlar. 
### Class(Sınıf) Ve __init__
![Class__init__](https://github.com/ibrahimmetinn/Akbank_Python_Bootcamp/assets/150549575/3920891b-964b-408f-9d81-d611c17b22e8)
### __del__
![__del__](https://github.com/ibrahimmetinn/Akbank_Python_Bootcamp/assets/150549575/461217ad-1ea3-4b6f-8116-c00148c683e9)
### list_books
![list_books2](https://github.com/ibrahimmetinn/Akbank_Python_Bootcamp/assets/150549575/edea4d9b-db19-4652-b3f9-f76ad3132f5d)
![select_1_list_books](https://github.com/ibrahimmetinn/Akbank_Python_Bootcamp/assets/150549575/6493dcb1-e146-4a14-9da2-e13d8deb4b32)
#### seek()fonksiyonu ile ilgili ufak bir örnek
![file seek](https://github.com/ibrahimmetinn/Akbank_Python_Bootcamp/assets/150549575/83a7f96b-0c4d-421d-a01f-ef9e9c3eea12)
### add_book
![add_book2](https://github.com/ibrahimmetinn/Akbank_Python_Bootcamp/assets/150549575/9bd75dc8-4e90-4072-af97-02b4ba121704)
![add_book](https://github.com/ibrahimmetinn/Akbank_Python_Bootcamp/assets/150549575/eacd4552-647b-47a2-a186-948fef434e6a)
### remove book
![remove_books](https://github.com/ibrahimmetinn/Akbank_Python_Bootcamp/assets/150549575/7a24384e-8227-4049-ad8d-c3397d5957e6)

 ### truncate() fonksiyonu
 Truncate İnglizcede kesmek/kırpmak anlamına gelmektedir. parantez içerisindeki değer byte sayısını temsil etmektedir. yazılan değer kadar byte saklanır ve geriye kalan tüm byte değerleri silinir.
Burada truncate() fonksiyonu kullanmamızın sebebi kesme işlemi yapmasıdır.Satır olarak bölünen listeyi kopmle siliyoruz ve silinen satır ile alt satırı birleştiriyoruz. Ve içerisinde hiçbir değer girmedik çünkü zaten komple amacımız satırı silip alt satır ile birleştirmek. 



#### 



