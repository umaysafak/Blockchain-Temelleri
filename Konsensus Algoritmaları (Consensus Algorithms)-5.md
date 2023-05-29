# Konsensus Algoritmaları (Consensus Algorithms)

Konsensus mekanizması (Consensus Mechanism), bir blokzincir ağı veya dağıtılmış defterdeki katılımcıların, birlikte kabul edilecek bir blok veya işlem listesi üzerinde anlaşmalarını sağlayan bir protokol veya algoritmadır. Konsensus mekanizması, dağıtılmış sistemlerde güvenilirlik, güvenlik ve bütünlük sağlamak için kullanılır.

Konsensus mekanizmaları, blokzincir teknolojisi ile çalışan ve merkezi olmayan ağlarda kullanılan önemli unsurlardır. Bu mekanizmalar, blokzincirin bir parçası olan düğümler (nodes) arasında gerçekleştirilen işlemlerin doğrulanması, yeni blokların eklenmesi ve ağdaki birlik ve uyumun sağlanması için kullanılır.

###   Konsensus mekanizmalarının temel amaçları şunlardır:
  
-İşlem Onayı: Konsensus mekanizması, ağdaki düğümler arasında gerçekleşen işlemlerin onaylanmasını sağlar. İşlemlerin doğrulanması ve onaylanması, güvenilir ve güvenli bir blokzincir ağının temelini oluşturur.

-Blok Oluşturma: Yeni blokların oluşturulması ve eklenmesi için konsensus mekanizması kullanılır. Katılımcılar, bir sonraki bloğun oluşturulmasına katkıda bulunurlar ve blokların sırasını ve içeriğini belirlemek için anlaşma sağlarlar.

-Çift Harcama ve Sahtekarlık Önleme: Konsensus mekanizmaları, çift harcama gibi sahtekarlık girişimlerini önlemek için tasarlanmıştır. Her işlemin tek bir kez gerçekleşmesini sağlamak ve güvenilir bir işlem geçmişi oluşturmak için çalışırlar.

-Ağ Güvenliği: Konsensus mekanizmaları, ağın güvenliğini sağlamak için kullanılır. Saldırı girişimlerine karşı dirençli olmalı ve ağdaki tüm katılımcıların güvenli bir şekilde işlem yapmasını sağlamalıdır.

![konsensus-5](https://github.com/umaysafak/Blockchain-Temelleri/assets/83416728/d84cbd55-b5a3-4ce5-8401-9271bb523b7b)


###   Bazı popüler konsensus algoritmaları şunlardır:
  
-Proof of Work (PoW): Proof of Work, Bitcoin gibi blokzincirlerde kullanılan ilk konsensus algoritmasıdır. Madencilik olarak da bilinir. Madenciler, karmaşık matematiksel problemleri çözmek için hesaplama gücü kullanır ve blokları doğrular. Bloğun onaylanması için madencilerin bu problemleri çözmeleri ve bir özet (hash) üretmeleri gerekir. PoW, işlem gücüne dayalı bir konsensus algoritmasıdır.

-Proof of Stake (PoS): Proof of Stake, Ethereum 2.0 gibi bazı blokzincirlerde kullanılan bir konsensus algoritmasıdır. Proof of Stake'de, blokların doğrulanması ve onaylanması, blokzincire sahip olan kişilerin varlık miktarına dayanır. Blokları onaylayacak olanlar, varlıklarını bir süreliğine blokzincire kilitler ve buna karşılık olarak blokları onaylama hakkı kazanır.

-Delegated Proof of Stake (DPoS): Delegated Proof of Stake, EOS gibi bazı blokzincirlerde kullanılan bir konsensus algoritmasıdır. DPoS'te, blokları onaylamak için belirli sayıda temsilci veya paydaş seçilir. Temsilciler, blokları doğrular ve onaylar. DPoS, PoS algoritmasının daha hızlı ve ölçeklenebilir bir versiyonudur.

-Practical Byzantine Fault Tolerance (PBFT): PBFT, merkezi olmayan sistemlerde güvenli ve toleranslı bir konsensus sağlamak için kullanılan bir algoritmadır. PBFT, Byzantine Fault Tolerance (BFT) konseptine dayanır ve düğümler arasında işbirliği yaparak anlaşmaya varmayı sağlar.

-Raft Consensus Algorithm: Raft, blokzincir gibi dağıtık sistemlerde kullanılan bir konsensus algoritmasıdır. Raft algoritması, lider-takipçi modelini kullanır ve düğümlerin bir lider düğüm tarafından yönetilmesini sağlar. Lider düğüm, blokları onaylar ve düğümler arasında konsensüs sağlar.

-Proof of Authority (PoA): Proof of Authority, özel blokzincirlerde sıkça kullanılan bir konsensus algoritmasıdır. PoA'da, blokları onaylamak için belirli otoriteler veya güvenilir düğümler seçilir. Bu düğümler, blokları onaylar ve işlemleri doğrular. PoA, işlem hızı ve güvenlik açısından avantaj sağlar, ancak merkeziyetçi bir yapıya sahiptir.

-Tendermint: Tendermint, dağıtık uygulamalar için bir konsensus algoritması ve blokzincir motorudur. Tendermint, Byzantine Fault Tolerance (BFT) konsensus algoritmasını kullanır ve düğümler arasında anlaşmaya varmayı sağlar. Bu algoritma, hızlı ve güvenilir bir konsensus sağlar.

-Proof of Elapsed Time (PoET): Proof of Elapsed Time, Intel tarafından geliştirilen bir konsensus algoritmasıdır. PoET, işlemlerin sıralanması ve blok onaylama sürecinin rastgele bir zaman dilimi boyunca gerçekleştirilmesini sağlar. Bu algoritma, enerji tüketimini azaltırken hızlı ve güvenilir bir konsensus sağlar.

-Byzantine Fault Tolerance (BFT): Byzantine Fault Tolerance, blokzincir gibi dağıtık sistemlerdeki hatalı düğümlere (Byzantine hataları) karşı dirençli bir konsensus algoritmasıdır. BFT algoritmaları, hatalı düğümlerin varlığına ve iletişim hatalarına dayanabilen güvenilir bir konsensus sağlar.

Bu konsensus algoritmaları, blokzincir teknolojisinde farklı kullanım durumlarına ve gereksinimlere yönelik çeşitli yaklaşımları temsil etmektedir. Her bir algoritma, farklı güvenlik modelleri, performans özellikleri ve ölçeklenebilirlik avantajları sunar. Projenizin gereksinimlerine ve kullanım senaryonuza bağlı olarak uygun konsensus algoritmasını seçmek önemlidir.
