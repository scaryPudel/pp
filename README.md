• Ak je problém inherentne paralelný, je možne zostaviť preň iba paralelný algoritmus.
o Nepravda
___________________________________________________________________________
• Ak je problém nedostatočne škálovateľný, zvýšenie počtu procesorov už nevedie k zvýšeniu zrýchlenia.
o Pravda
___________________________________________________________________________
• Ak má byť problém riešený paralelným spôsobom, potom:
o Musí preň existovať prinajmenšom efektívny paralelný algoritmus
o Nemusí preň existovať nevyhnutne optimálny paralelný algoritmus
___________________________________________________________________________
• Ak veľkosť problému nie je známa, expanzívny paralelizmus treba riadiť počas vykonávania výpočtu.
o Pravda
___________________________________________________________________________
• Ak znížime časovú zložitosť algoritmu, môže sa stať, že súčasne zvýšime jeho pamäťovú zložitosť.
o Pravda
___________________________________________________________________________
• Algoritmus s najpriaznivejšou časovou zložitosťou, ktorý je možno použiť na riešenie problému, určuje súčasne aj časovú zložitosť problému.
o Pravda
___________________________________________________________________________
• Architektúra MIMD môže pozostávať z:
o Procesných elementov
o Zbernice
o Spoločnej pamäte
o Prepojovacej siete
___________________________________________________________________________
• Cieľom realizácie paralelných výpočtov je zníženie času výpočtu a/alebo spracovanie veľkého množstva údajov.
o Pravda
___________________________________________________________________________
• Čas vykonávania paralelného algoritmu sa skladá z času počítania, času komunikovania a času čakania.
o Pravda
___________________________________________________________________________
• Čas vykonávania paralelného programu sa skladá z času počítania, času komunikovania a času čakania.
o Pravda
___________________________________________________________________________
• Čas vykonávania paralelného programu sa skladá z:
o Času počítania
o Idle time
o Času čakania
o Času komunikovania
___________________________________________________________________________
• DM-MIMD podporuje škálovateľnosť horšie ako SM-MIMD.
o Nepravda
___________________________________________________________________________
• Efektívnosť E(n, p) je definovaná ako E(n, p) = S(n, p)/p.
o Pravda
___________________________________________________________________________
• Efektívnosť E(n, p) je definovaná ako E(n, p) = T(n,l) / T(n,p).
o Nepravda
___________________________________________________________________________
• Efektívnosť E(n,p) je definovaná ako E(n,p) = T(n,1)/T(n,p).
o Nepravda
___________________________________________________________________________
• Embarrasingly parallel problems je termín preložiteľný ako trápne paralelne problémy.
o Pravda
___________________________________________________________________________
• Embarrassingly parallel problems:
o Medzi úlohami je iba malá závislosť
o Je ľahké dekomponovať na podúlohy
___________________________________________________________________________
• Expanzívny paralelizmus môže byť:
o Realizovaný na architektúrach MIMD
o Jemnozrnný
o Hrubozrnný
o Realizovaný na architektúrach SIMD hrubozrnný
___________________________________________________________________________
• Expanzívny paralelizmus môže byť:
o Realizovaný na architektúrach SIMD
o Realizovaný na architektúrach MIMD
o Jemnozrnný
o Hrubozrnný
___________________________________________________________________________
• Expanzívny paralelizmus, kde n^2 je špeciálnym prípadom expanzívneho paralelizmu, ktorý sa nazýva rozdeľuj a panuj.
o Pravda
___________________________________________________________________________
• Explicitný paralelizmus umožňuje programátorovi pomocou špecializovaných direktív alebo volaní funkcií určených pre synchronizáciu, komunikáciu a dekompozíciu úloh realizovať paralelizáciu výpočtu.
o Pravda
___________________________________________________________________________
• Flynnova klasifikácia posudzuje množstvo súčasne spracovávaných inštrukcií a súčasne spracovávaných dát:
o Pravda
___________________________________________________________________________
• Gustafsonov zákon predpokladá, že veľkosť sekvenčnej časti výpočtu klesá so zväčšovaním sa rozmeru problému:
o Nepravda
___________________________________________________________________________
• Implicitný paralelizmus umožňuje kompilátoru alebo interpreteru zdrojového kódu automaticky odhaľovať' inherentný paralelizmus vlastný určitým konštrukciám programu.
o Pravda
___________________________________________________________________________
• Jednoduchý paralelizmus je jemnozrnný.
o Nepravda
___________________________________________________________________________
• Jednoduchý paralelizmus možno niekedy využiť pri prúdovom paralelizme pre zlepšenie vyváženosti pri prúdovom spracovaní.
o Pravda
___________________________________________________________________________
• Jedným z kľúčových problémov, ktoré je potrebné v súvislosti s paralelnými výpočtami riešiť, je vyvažovanie paralelného výpočtu.
o Pravda
___________________________________________________________________________
• Lineárna časová zložitosť algoritmu, formálne zapísaná ako 0(1), je na grafe reprezentovaná priamkou rovnobežnou s osou x, prechádzajúcou na ose y hodnotou 1, za predpokladu, že na ose y je počet operácii a na ose x je uvedené n.
o Nepravda
___________________________________________________________________________
• Maximálny stupeň paralelizmu (MSP) je maximálny počet procesných elementov, ktorý bol v určitom čase využívaný na realizáciu paralelného výpočtu.
o Pravda
___________________________________________________________________________
• Maximálny stupeň paralelizmu (MSP) sa nemôže nikdy rovnať hodnote 1.
o Nepravda
___________________________________________________________________________
• Medzi funkcie kolektívnej komunikácie v rámci MPI patria:
o MPI_Scan
o MPI_Exscan
o MPI_Alltoall
o MPI_Reduce_Scatter
___________________________________________________________________________
• Medzi nevýhody implicitného paralelizmu patrí:
o Nutné doplnenie ďalších kľúčových slov do jazyka a jazykových konštrukcií
o Možné zahltenie zdrojov
o Strata kontroly nad paralelným vykonávaním
o Možné redukovanie výkonnosti paralelného vykonávania
___________________________________________________________________________
• MIMD architektúry zvyčajne obsahujú viac procesných jednotiek ako architektúry
SIMD.
o Nepravda
___________________________________________________________________________
• Najlepší sekvenčný algoritmus môže byť predsa len rýchlejší ako algoritmus, ktorý je paralelizovaný.
o Pravda
___________________________________________________________________________
• Nech TN(n) je čas vykonávania najrýchlejšieho známeho sekvenčného algoritmu na jedno procesore, potom numerická efektívnosť = TN(n)/T(m,1).
o Pravda
___________________________________________________________________________
• Neohraničený paralelizmus algoritmu neberie do úvahy zdroje počítačového systému.
o Pravda
___________________________________________________________________________
• Neohraničený paralelizmus znamená, že škálovanie paralelného počítača pridávaním ďalších procesorov neznižuje efektivitu paralelizácie.
o Nepravda
___________________________________________________________________________
• Nie je možné súčasne znižovať pamäťovú aj časovú zložitosť riešenia problému.
o Nepravda
___________________________________________________________________________
• Nový komunikátor možno vytvoriť prostredníctvom funkcie:
o MPI_Comm_dup
o MPI_Comm_split
o MPI_Comm_create
___________________________________________________________________________
• Numerická efektívnosť je mierou kvality sekvenčného algoritmu berúc do úvahy spracovávané údaje.
o Pravda
___________________________________________________________________________
• Ohraničený paralelizmus berie do úvahy zdroje počítačového systému.
o Pravda
___________________________________________________________________________
• Podľa Amdahlovho zákona zrýchlenie dosiahnuteľné na paralelnom počítači je závislé od počtu procesorov, ktoré sú k dispozícii pri paralelnom výpočte.
o Nepravda
___________________________________________________________________________
• Podľa Amdahlovho zákona zrýchlenie dosiahnuteľné na paralelnom počítači môže byť značne ohraničené existenciou malej časti sekvenčného kódu, ktorý nemožno paralelizovať.
o Pravda
___________________________________________________________________________
• Pre architektúru MISD platí:
o Táto architektúra má obmedzený aplikačný rámec a preto sa používa zriedkavo
o Architektúra paralelných počítačov typu MISD sa skladá zo špecializovaných rýchlych procesorov
o Je vhodná pre riešenie hrubozrnných paralelných problémov
o Procesory v nej komunikujú prúdovým spôsobom
___________________________________________________________________________
• Pre architektúru paralelného počítača SM-MIMD platí:
o Prístup k spoločnej pamäti možno riadiť pomocou semaforov
___________________________________________________________________________
• Pre architektúry DM-MIMD platí:
o Je pri nej dôležité minimalizovať komunikáciu medzi procesormi
o Komunikácia medzi procesormi prebieha výlučne prostredníctvom správ
o Pre hrubozrnné paralelné problémy škáluje omnoho lepšie ako SIMD
o Podporuje škálovateľnosť omnoho viac ako architektúra MIMD so spoločnou amäťou
___________________________________________________________________________
• Pre architektúry VSM-MIMD platí:
o Umožňuje procesom priamy prístup do vyhradenej časti pamäte iných rocesov
o Fyzicky je realizovaná ako architektúra s distribuovanou pamäťou
___________________________________________________________________________
• Pre dekompozíciu paralelných problémov platí:
o Je potrebné zabrániť nechcenému presúvaniu dát medzi operačnou pamäťou Počítača a sekundárnym úložným zariadením z dôvodu zlej dekompozície roblému
o Pri nesprávnej dekompozícii paralelného problému môže dôjsť k uviaznutiu výpočtu
o Cieľom správnej dekompozície paralelného problému je aj minimalizácia komunikácie
o Môže byť aj triviálna
___________________________________________________________________________
• Pre expanzívny a masívny paralelizmus platí:
o Sú inherentne problémom pravidelnej povahy
o Sú pomocou nich zostaviteľné vysoko výkonné paralelné aplikácie
___________________________________________________________________________
• Pre expanzívny paralelizmus platí:
o Ak je hrubozrnný, je realizovaný prostredníctvom architektúry MIMD
o Ak veľkosť problému nie je známa, ľahko dochádza k preťaženiu paralelnej architektúry v dôsledku vyčerpania zdrojov
___________________________________________________________________________
• Pre expanzívny paralelizmus platí:
o Z funkčného hľadiska je dekompozícia problému triviálna
o Používaná dekompozícia sa nazýva aj hierarchická dekompozícia
o Ta istá funkcia je pri ňom používaná na rôznych úrovniach
___________________________________________________________________________
• Pre Flynnovu klasifikáciu platí, že:
o SM-MIMD predstavuje MIMD so zdieľanou pamäťou (Shared Memory MIMD)
o DM-MIMD predstavuje MIMD s distribuovanou pamäťou (Distributed Memory MIMD)
___________________________________________________________________________
• Pre grafový komunikátor platí:
o Funkcia MPI_Graph_create umožní vytvoriť grafový komunikátor
o Proces má v grafovom komunikátore susedov, ktorých možno identifikovať pomocou funkcie MPI_Graph_neighbours
o Proces má v grafovom komunikátore susedov, ktorých počet možno zistiť pomocou funkcie MPI_Graph_neighbor_count
o Grafový komunikátor možno vytvoriť aj z komunikátora MPI_COMM_WORLD
___________________________________________________________________________
• Pre Gustafsonov zákon platí:
o Nie je v rozpore s Amdahlovym zákonom
o Platí, ak riešime dostatočne veľký problém
o Hovorí, že je možné dosiahnuť nelimitované zrýchlenie paralelného výpočtu
o Platí, ak máme k dispozícii dostatočne veľký počet procesorov
___________________________________________________________________________
• Pre inherentný paralelizmus platí:
o Existuje inherentne paralelný algoritmus aj inherentne paralelný problém
___________________________________________________________________________
• Pre jednoduchý paralelizmus platí:
o V praxi pri ňom zvyčajne nemožno dosiahnuť vysoký stupeň paralelizácie
o Jednoduchý paralelizmus je hrubozrnný
o Zvyčajne sa pri ňom spracovávajú nezávislé množiny údajov
o Problém P sa dekomponuje na množinu n podproblémov (úloh), ktoré možno riešiť nezávisle na sebe
___________________________________________________________________________
• Pre karteziánsky komunikátor platí:
o Predstavuje n-dimenzionálnu pravidelnú mriežku procesov
o Pri vzniku karteziánskeho komunikátora je možné preusporiadať ranky jednotlivých procesov
___________________________________________________________________________
• Pre komunikáciu v rámci MPI platí:
o Existuje kolektívna komunikácia (skupinová) – (collective comunication)
o Existuje adresná komunikácia (bod-bod) – (Point-to-point communication)
o Neblokujúca komunikácia – vykonávanie programu pokračuje okamžite po zavolaní funkcie pre komunikáciu teda počas odosielania/prijímania správy
o Blokujúca komunikácia - vykonávanie procesu sa pozastaví, kým sa správa neodošle/neprijme
___________________________________________________________________________
• Pre komunikátory platí:
o Inter-komunikátory neumožňujú kolektívnu komunikáciu
o Intra-komunikátory umožňujú kolektívnu komunikáciu
___________________________________________________________________________
• Pre masívny paralelizmus platí:
o Je využiteľný na architektúrach SIMD
o V typickom prípade ide o jemnozrnný paralelizmus
o Jednotlivé množiny spracovávaných údajov sa pri ňom môžu navzájom prekrývať
o Je využiteľný na architektúrach MIMD
___________________________________________________________________________
• Pre masívny paralelizmus platí:
o Údajová dekompozícia je z hľadiska funkcie triviálna
o Nazýva sa aj údajovým paralelizmom
___________________________________________________________________________
• Pre neblokujúcu komunikáciu v rámci MPI platí:
o Funkcia MPI_Wait slúži na blokovanie vykonávania procesu do momentu, kým nie je dokončená konkrétna požiadavka
o Funkcia MPI_Test slúži na testovanie, či bola dokončená konkrétna požiadavka, ale neblokuje pri tom vykonávanie procesu
___________________________________________________________________________
• Pre ohraničenosť paralelizmu platí:
o Ohraničený paralelizmus algoritmu je vyjadrený paralelným časom výpočtu, berúc do úvahy (ohraničenie) zdroje počítačového systému
o Neohraničený paralelizmus algoritmu je vyjadrený paralelným časom výpočtu, neberú pritom do úvahy(ohraničenie) zdroje počítačového systému
___________________________________________________________________________
• Pre ohraničenosť paralelizmu platí:
o Nie je hrubozrnná
___________________________________________________________________________
• Pre optimálny paralelný algoritmus platí:
o p.T = Ts kde p znamená počet procesorov, T znamená paralelný čas výpočtu a Ts je čas výpočtu pri použití najrýchlejšieho známeho sekvenčného algoritmu
___________________________________________________________________________
• Pre pamäťovú zložitosť algoritmov platí:
o Pamäťová zložitosť algoritmu sa určí ako maximálna veľkosť spotreby pamäte počas vykonávania algoritmu
o Out-of-core algoritmus je taký algoritmus, ktorý uchováva z celkového objemu spracovávaných dát v hlavnej pamäti počítača iba minimálne množstvo dát, potrebné pre realizáciu výpočtu
___________________________________________________________________________
• Pre paralelizmus platí:
o Jednoduchý a prúdový paralelizmus sú inherentne problémom nepravidelnej povahy
o Jednoduchý a prúdový paralelizmus je zvyčajne hrubozrnný
___________________________________________________________________________
• Pre priemerný stupeň paralelizmu platí:
o Môže byť aj desatinné číslo
___________________________________________________________________________
• Pre programové modely založené na odovzdávaní správ platí:
o SPMD znamená Single Program Multiple Data
o MPMD znamená Multiple Program Multiple Data
o Pre každú aplikáciu modelu MPMD je možné použiť aplikáciu modelu SPMD
___________________________________________________________________________
• Pre prúdový paralelizmus platí, že problém P sa dekomponuje na množinu n podproblémov (úloh), ktoré sú riešené jeden po druhom.
o Pravda
___________________________________________________________________________
• Pre prúdový paralelizmus platí, že problém P sa dekomponuje na množinu n podproblémov (úloh), ktoré sú riešené všetky naraz v tom istom čase.
o Nepravda
___________________________________________________________________________
• Pre SIMD platí:
o SIMD je architektúra vhodná pre spracovanie obrazovej informácie
o SIMD procesné elementy môžu byť usporiadané do 2D mriežok
___________________________________________________________________________
• Pre Single Instruction Single Data architektúru platí:
o Poradie vykonávania inštrukcií je deterministické
o Môže byt využitá pri pseudoparalelnom vykonávaní výpočtov
___________________________________________________________________________
• Pre SISD platí:
o Pri vykonávaní programu využíva jediný prúd dát
o Pri vykonávaní programu využíva jediný prúd inštrukcií
o Pri výkonných paralelných výpočtoch sa nepoužíva
o Je to sekvenčný, jednoprocesorový počítačový systém
___________________________________________________________________________
• Pre SM-MIMD platí:
o Táto skratka znamená Shared Memory Multiple Instructions Multiple Data
o Nevýhodou je hladovanie (starvation) - práca procesných jednotiek je brzdená čakaním na komunikáciu s pamäťou
o Pre túto architektúru paralelných počítačov je charakteristický menší počet procesných jednotiek
___________________________________________________________________________
• Pre stupeň paralelizmu SP platí:
o Zostáva v určitých časových intervaloch realizácie paralelného výpočtu konštantný
o Je počet procesných elementov, ktoré sú v danom čase využívané na realizáciu paralelného výpočtu
___________________________________________________________________________
• Pre súbežné programovanie platí:
o Pri súbežnom programovaní sa nevyžaduje aby výsledný program bežal na paralelnom počítačovom systéme
o Paralelizmus využívaný v systémoch reálneho času je zvyčajne hrubozrnnejší ako pri paralelnom počítaní ako pri paralelných výpočtoch
___________________________________________________________________________
• Pre škálovateľnosť v IDEÁLNOM prípade platí že:
▪ S(n,p)= p E(n,p)= 100%
o Pravda
___________________________________________________________________________
• Pre škálovateľnosť v REÁLNOM prípade platí, že:
▪ S(n, p) < p E(n, p) < 100%
o Pravda
___________________________________________________________________________
• Pre zložitosť algoritmu:
o Neplatí, že nižšia zložitosť algoritmu automaticky umožňuje jeho ľahšie pochopenie
o Neplatí, že nižšia zložitosť algoritmu automaticky umožňuje jeho ľahšie naprogramovanie
___________________________________________________________________________
• Pri expanzívnom paralelizme je problém rekurzívne delený na n podproblémov toho istého typu.
o Pravda
___________________________________________________________________________
• Pri expanzívnom paralelizme je problém rekurzívne delený na n podproblémov toho istého typu, kde n je z rozsahu od 0 do 1.
o Nepravda
___________________________________________________________________________
• Pri expanzívnom paralelizme, ak veľkosť problému nie je známa, ľahko dochádza k preťaženiu paralelnej architektúry v dôsledku vyčerpania zdrojov.
o Pravda
___________________________________________________________________________
• Pri Gustafsonovom zákone nie je zrýchlenie paralelného počítania zhora ohraničené.
o Pravda
___________________________________________________________________________
• Pri inicializácii MPI:
o Inicializácia MPI je realizovateľná prostredníctvom funkcie MPI_Init
o Pri inicializácii MPI vznikne komunikátor MPI_COMM_WORLD
o Pri inicializácii MPI vznikne komunikátor MPI_COMM_SELF
o Pri inicializácii MPI je každému procesu pridelený rank v komunikátore MPI_COMM_WORLD
___________________________________________________________________________
• Pri jednoduchom paralelizme, keď rozdelíme problém na p úloh, záleží na tom, aby bol čas potrebný pre realizáciu jednotlivých úloh približne rovnaký, pretože tieto úlohy sa realizujú sekvenčne jedna po druhej.
o Nepravda
___________________________________________________________________________
• Pri jednoduchom paralelizme, keď rozdelíme problém na p úloh, záleží na tom, aby bol čas potrebný pre realizáciu jednotlivých úloh približne rovnaký.
o Pravda
___________________________________________________________________________
• Pri programovaní systémov reálneho času platí:
o V súvislosti s nim je používaný termín concurrent programing
o Cieľom je zabezpečenie požiadaviek na čas vykonávania programu
___________________________________________________________________________
• Pri programovaní výkonných paralelných výpočtov je základným cieľom dosiahnutie tých istých výsledkov ako na sekvenčnom počítači, avšak pomocou viacprocesorovej architektúry.
o Pravda
___________________________________________________________________________
• Priemerný stupeň paralelizmu (PSP) je priemerný počet procesných elementov, ktorý bol v určitom čase využívaný na realizáciu paralelného výpočtu.
o Pravda
___________________________________________________________________________
• Problém P sa dekomponuje na množinu n podproblémov (úloh), ktoré sú riešené všetky naraz, v tom istom čase.
o Nepravda
___________________________________________________________________________
• Program pre data flow počítač:
o Je v podobe data flow grafu
o Pravidlo aktivácie (PA) hovorí, že inštrukcia je aktivovaná, keď je vykonateľná a k dispozícii sú zdroje na jej vykonávanie
o Vykonávanie inštrukcií data flow grafu je prijímanie, spracovávanie, vysielanie aktivačných značiek
o Pravidlo vykonateľnosti (PV) hovorí, že inštrukcia je vykonateľná, ak sú dostupné všetky jej operandy
___________________________________________________________________________
• Prúdový paralelizmus je zväčša hrubozrnný paralelizmus a preto sa pri ňom architektúry MISD používajú zriedkavo.
o Pravda
___________________________________________________________________________
• Prúdový paralelizmus je zväčša hrubozrnný paralelizmus a preto sa pri ňom architektúry MIMD používajú zriedkavo.
o Nepravda
___________________________________________________________________________
• Rozoznávame časovú a pamäťovú zložitosť algoritmov a problémov.
o Pravda
___________________________________________________________________________
• S(n, p) = T(n, 1) / T(n, p).
o T(n, 1) je sekvenčný čas vykonávania na jednom procesore
o T(n, p) je čas vykonávania na p procesoroch
___________________________________________________________________________
• Ťažko paralelizovateľné sekvenčné časti kódu patria medzi náklady paralelného výpočtu.
o Pravda
___________________________________________________________________________
• Vykonaná práca wi v časovom intervale Ati je vyčísliteľná ako wi = SP(Ati) x Ati x r [ops], kde SP(Ati) je stupeň paralelizmu, r je počet operácií vykonávaných na procesnom elemente za sekundu.
o Pravda
___________________________________________________________________________
• Výkonná paralelná aplikácia nie je jednoducho vytvoriteľná s využitím prúdového paralelizmu.
o Pravda
___________________________________________________________________________
• Výkonná paralelná aplikácia nie je jednoducho vytvoriteľná s využitím jednoduchého paralelizmu.
o Pravda
___________________________________________________________________________
• Výkonné paralelné výpočty sa uplatňujú predovšetkým pri modelovaní, simulácii a analýze zložitých technických, fyzikálnych a biologických systémov, s cieľom skúmania ich vlastností a predpovedania ich správania.
o Pravda
___________________________________________________________________________
• Vzhľadom na obmedzený aplikačný záber, architektúra MISD sa používa zriedkavo.
o Pravda
___________________________________________________________________________
• Zníženie komunikačných nákladov pri realizácii paralelného výpočtu možno dosiahnuť:
o Návrhom vhodnej topológie procesov pri dekompozícii problému
o Minimalizáciou počtu prenášaných správ
o Maximalizáciou dĺžky správy
o Prekrytím komunikácie a výpočtu
___________________________________________________________________________
• Zrýchlenie S(n,p) je definované ako S(n,p) = T(n,1) / t(N,P).
o Pravda
