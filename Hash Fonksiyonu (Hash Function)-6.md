# Hash Fonksiyonu (Hash Function)

Hash fonksiyonu (Hash function), belirli bir girdi (input) değerini alıp, sabit uzunlukta bir çıktı (output) değeri üreten matematiksel bir fonksiyondur. Hash fonksiyonları, verileri birer benzersiz "hash" değeriyle temsil eder ve birçok farklı uygulama alanında kullanılır.

###   -Hash fonksiyonlarının ayrıntılı özellikleri şunlardır:
  
-Sabit Çıktı Boyutu: Hash fonksiyonları, herhangi bir boyuttaki girdileri (metinler, dosyalar, veriler vb.) sabit bir uzunlukta (tipik olarak birkaç ondalık veya on altısal karakter) bir çıktıya dönüştürür. Bu, çıktının girdi boyutundan bağımsız olarak her zaman aynı uzunlukta olacağı anlamına gelir.

-Deterministiklik: Aynı girdi her zaman aynı çıktıyı üretir. İki farklı girdi, farklı çıktılara sahip olacaktır. Bu, hash fonksiyonlarının tekrarlanabilir ve öngörülebilir olduğu anlamına gelir.

![Hash-6](https://github.com/umaysafak/Blockchain-Temelleri/assets/83416728/47997431-db6d-4c97-b268-312c57a0b4be)

-Hızlı Hesaplama: Hash fonksiyonları, verilen bir girdinin hash değerini hızlı bir şekilde hesaplar. Çoğu durumda, girdinin boyutu ne olursa olsun, hash değeri hesaplamak oldukça hızlıdır.

-Tek Yönlülük: Hash fonksiyonları, girdiden çıktıyı hesaplamak kolay olsa da, çıktıdan girdiyi geri hesaplamak neredeyse imkansızdır. Bu, hash fonksiyonlarının tek yönlü olduğu anlamına gelir ve gizlilik ve güvenlik için önemlidir.

-Kavramsal İlişkisizlik: Hesaplanan hash değeri, girdinin en küçük bir değişikliğinde tamamen farklı bir değer oluşturur. İki benzer girdi için bile, çıktıda tamamen farklı birer hash değeri elde edilir. Bu özellik, hash fonksiyonlarının veri bütünlüğü kontrolü, kimlik doğrulama ve parola koruması gibi alanlarda kullanılmasını sağlar.

-Kolluk: İdeal bir hash fonksiyonu, girdi değerinde herhangi bir değişiklik olduğunda tamamen farklı bir çıktı üretir. Bu, hash değerindeki en küçük bir değişikliğin dahi tamamen farklı bir hash değeri oluşturmasını sağlar.

Hash fonksiyonları, veri bütünlüğünün sağlanması, parola doğrulaması, dijital imza oluşturma, veri depolama ve veri tabanı indekslemesi gibi birçok alanda kullanılır. Ayrıca blokzincir teknolojilerinde de yaygın olarak kullanılırlar, özellikle blokların ve işlemlerin benzersiz kimliklerini oluşturmak için hash fonksiyonlarına başvurulur.
