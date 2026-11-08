 OmerFaruk_Demir_YODA_OTONOM_YAZILIM
 
#Repository githubda kişinin,kişilerin birlikte çalışmasını ya da aynı şekilde bir takımın birbirinden haberdar bir şekilde proje yürütmesini sağlayan bir ortamdır.Burada projenin kodları public veye private şeklinde tutulur.Takımda birisi yanlış birşey yaptığında proojenin önceki sürümlere dönmek gibi avantajları vardır repositorie'nin.Kodların tutulduğu bir depo benzetmesi yapabiliriz.

Commite gelirsek commit bizim yeni yaptığımız kodları veya kodlarda yaptığımız değişiklikleri repositorye yüklemektir.Takım arkadaşlarımızı aynı repositorye ekleyebiliriz ama onlarda değişiklik vb.
yapıp commit ettiklerinde repository sahibinin izni lazımdır oraya yüklemek için.Bundan dolayı repository sahibine bu kodlar gönderilir eklensin mi diye.

Branch ve merge kavramlarına gelirsek projeler 3-5 satır kodlardan oluşmayacak,bir sürü kişi proje için çalışacak bundan dolayı herkese farklı görev verilecek.Örneğin YODA'da yapıldığı gibi projede yazılım için farklı işlerle uğraşılacak burada bütün kodların toplanacağı yer main dosyası olacak ama herkes buraya kodları yazınca eklemeyecek direket.Herkes kendi branch'inde binevi kendi yerinde kodları yazıcak,test edicek hata var mı kontrol edicek main dosyayla kontrol edicek ondan sonra merge işlemine geçicek aslında merge işlemini branch ile main dosyasının birleşimi gibi düşünebiliriz.

Stage işlemini commit atmadan önce kodların tutulduğu yer gibi düşünebiliriz çünkü koldar üzerinde değişiklikler yapabiliriz çünkü öyle durumlar yaşanabilir.stage alanından sonra seçilenleri commit yapabiliriz ama.

Son olarak push ve pull kavarmlarına değineceğim bunlar biraz birbirine zıt çünkü push kavramı yerel yani bilgisayardaki commitleri github'a gönderir böylece arkadaşlarımız o dosyalara erişebilir pull iste tam tersi arkadaşlarımız eklemiştir biz onu kendi bilgisayarımıza çekiyoruzdur.<img width="317" height="410" alt="image" src="https://github.com/user-attachments/assets/cfc3c779-69d3-41b6-b387-5f5a234336e1" />

Buradaki dallarda aşağıdan yukarıya gitmeyi kronolojik düşünebiliriz en aşağıdaki mavi hat main dosyayı,ayrılan sarı hat branch'i yani ayrı bir yerde yapılan farklı bir çalışmayı gösteriyor ondan sonra mavi ve sarı hat birleşiyor burası merge işlemi.Ondan sonra devam eden mor hat readme dosyasında yapılan değişiklikleri temsil ediyor.



