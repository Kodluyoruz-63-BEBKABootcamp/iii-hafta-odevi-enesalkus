# III-hafta-odevi

> ### .NET Kodu Nedir :
> .NET veya .NET Framework Microsoft firması tarafından 2000 yılında geliştirilmeye başlanmış ve .NET Foundation topluluğuna devir edilmiş bir yazılım geliştirme platformudur. İçerisinde yer alan kütüphaneler sayesinde kolayca masaüstü, web ve cep telefonu uygulamaları geliştirmeye imkan verir.
> #### Nasıl Derlenir : [Derleme süreci.](http://geekswithblogs.net/manjunath.k/archive/2013/06/12/.net-framework-compilation-proces.aspx)

> ### Roslyn Compiler Nedir :
> .NET Derleyici Platformu, Microsoft'tan C # ve Visual Basic .NET dilleri için bir dizi açık kaynak derleyici ve kod analizi API'sıdır. Proje özellikle C # ve VB.NET derleyicilerinin kendi kendini barındıran sürümlerini içerir.

> ### Restful Servisler Nasıl Çalışır :
> REST, client-server arasındaki haberleşmeyi sağlayan HTTP protokolü üzerinden çalışan bir mimaridir. REST ,servis yönelimli mimari üzerine oluşturulan yazılımlarda kullanılan bir transfer yöntemidir.İstemci ve sunucu arasında XML ve JSON verilerini taşıyarak uygulamanın haberleşmesini sağlar.REST mimarisini kullanan servislere ise RESTful servis denir.
> #### Alternatifleri Nelerdir :
> - GraphQL : verileri istemeyi açıklayan bir sözdizimidir. Graph database ile alakası yoktur. Facebook tarafından geliştirilmektedir. GraphQL katmanı bir veya birden fazla veri kaynağı ile istemcinin arasında yaşar, istemciden gelen istekleri alır ve gereken verileri döner. Özetlemek gerekirse GraphQIL şu üç ana özelliğe sahiptir:
> 1. İstemcinin istediği verilerin belirtilmesini sağlar.
> 2. Birden fazla kaynağın veriye ulaşmasını kolaylaştırır.
> 3. Bir tür sistem ile veriyi açıklar.
> - Falcor : Falcor modeli Netflix tarafından geliştirilen bir JavaScirpt kütüphanesidir. Tüm uzak veri kaynaklarının sanal bir JSON graph aracılığıyla tek bir domian model aracılığyla temsil edilmesini sağlar. Veri toplamak için hala REST yapısını kullanır. Yani, bir request için farklı endpoint'lere istek gönderilir ve her resourse için JSON object döndürülür.
> - OData : Yapısal olarak istemciden gönderilen sorgu isteği sunucu tarafında işlenerek sonuç üretilmekte ve clienta gönderilmektedir. Ayriyetten istemci tarafından talep edilen metadata belgesi ile OData kullandığı entitylerin detaylarından istemciyi bilgilendirebilmektedir.

> ### Extension Method Nedir :
> Kelime anlamı genişletilebilir metod olan Extension Method'lar C#3.0 ile hayatımıza girmiştir ve yaptığı iş itibatiyle kullanım açısından son derece faydalı metodlardır. Tek cümleyle özetlemek gerekirse class ve struct yapılarını modify etmeden ilgili struct yada class'için extension metodlar eklememizi sağlar.
> #### Nasıl Yazılır : 
> - Extension metodlar static bir class içerisinde static olarak tanımlanmalıdır. 
> - Extend edilecek class ilgili extension metoda metodun ilk parametresi olarak verilip önünde this keyword'ü ile tanımlanmalıdır
> - Extension metod da tanımlı parametrelerden sadece 1 tanesi this keyword'ü ile tanımlanır

> ### MVC'nin Alternatifleri Nelerdir :
> - HMVC (Hierarchical Model-View-Controller)
> - MVVM (Model-View-ViewModel)
> - MVP (Model View Presenter)
> - MVA (Model View Adapter)
> - PAC (Presentation Abstraction Control)
> - RMR (Resource-Method-Representation)
> - ADR (Action-Domain-Responder)

> ### Architectural Pattern Nedir :
> Mimari desenler, yazılım mühendisliğindeki mimari sorunlara çözümler öneren yazılım desenleridir. Bir mimari desen, yazılım sistemi için alt sistemlerden ve bunların sorumluluklarıyla iç ilişkilerinden meydana gelen temel ve yapısal bir organizasyon şemasını ifade eder.

> ### ViewData, ViewBag ve TempData Farkları Nelerdir :
> Öncelikle ViewData ve ViewBag aynı çalışma mantığına sahip olmakla beraber ViewData ; asp.net mvc, asp.net mvc 2 ve asp.net mvc3 de çalışmaktadır. Fakat ViewBag asp.net mvc 3 ile birlikte gelen yeni ve runtime içerisinde oluşan dinamik bir asp.net mvc 3 nesnesidir. ViewData kullanımında köşeli parentez içerisine (ViewData["Test"] ) içerisine yazdığımız anahtar kelime ( key = Test) sayesinde diğer ViewData lardan ayırmış oluruz. ViewData nesneside birden fazla farklı nesne ayırmasını ViewDataDictionary sınıfı aracılıyla, "key/value" syntax sayesinde çözümlemiş olur. TempData ise çok basit bir çalışma mantığı vardır. Bunu kısaca açıklamak gerekirse herhangi Controller dan oluşturulmuş olan veriyi Views ler arasında taşımamıza veya tek bir View içerisinde elimizdeki veriyi ekran çıktısı olarak görüntüler.
