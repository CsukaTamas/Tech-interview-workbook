# Tesztautomatizálási kérdések

## Tesztelési alapok (ISTQB-hez kapcsolódó)
<img src="https://www.mindsmapped.com/wp-content/uploads/2016/06/ISTQB.jpg" alt="image" width="300" height="220">

#### ✅ Mi a tesztelés célja? Mi nem az?
Bármely projekt esetén a tesztelés céljai az alábbiak lehetnek:<br> 
● A munkatermékek, mint például a követelmények, felhasználói történetek, műszaki tervek és kód 
hibamegelőzés céljából történő kiértékelése<br> 
● Annak igazolása, hogy az összes meghatározott követelmény teljesült-e<br> 
● Annak ellenőrzése, hogy a teszt tárgya teljes mértékben implementálásra került, továbbá annak, 
validálása, hogy a felhasználók, illetve más érintett felek elvárásainak megfelelően működik. <br> 
● A teszt tárgyának minőségébe vetett bizalom kiépítése <br> 
● A meghibásodások és hibák megtalálása és ezáltal a nem megfelelő szoftverminőség kockázati 
szintjének csökkentése <br> 
● Megfelelő információ biztosítása az érintett feleknek, hogy ezáltal megalapozott döntést 
hozhassanak különösen a teszt tárgyának minőségi szintjére vonatkozóan <br> 
● A szerződésben foglalt, jogi vagy szabályozott követelményeknek, szabványoknak való 
megfelelés biztosítása, és/vagy igazolni a teszt tárgyának ezen követelményeknek, 
szabványoknak való megfelelőségét <br> 
#### ✅ Mik a tesztelési alapelvek?
1. A tesztelés a hibák jelenlétét mutatja, nem a hiányukat <br> 
A tesztelés kimutathatja a hibák jelenlétét, de azt nem képes igazolni, hogy nincsenek hibák. A teszteléssel 
csökken annak az esélye, hogy a szoftverben felfedezetlen hibák maradnak, de ha nem találnak hibát, az 
nem bizonyítja, hogy a rendszer helyes. <br> 
2. Nem lehetséges kimerítő teszt <br> 
Kimerítő teszt, azaz a mindenre (a bemenetek és előfeltételek minden kombinációjára) kiterjedő tesztelés a 
triviális eseteket leszámítva nem lehetséges. Ahelyett, hogy megkísérelnénk a kimerítő tesztelést, 
kockázatelemzés, tesztelési technikák használata és priorizálása szükséges a tesztelési erőforrások 
összpontosításához. <br> 
3. A korai tesztelés időt és pénzt spórol <br> 
A hibák korai megtalálásának érdekében a szoftverfejlesztési életciklus során mind a statikus, mind a 
dinamikus teszttevékenységeket a lehető legkorábban el kell kezdeni. A korai tesztelésre az angol 
szakirodalomban néha shift left-ként utalnak. A szoftverfejlesztési életciklus alatti korai tesztelés segít a 
költséges változtatások csökkentésében vagy eliminálásában (lásd: 3.1-es fejezet). <br> 
4. Hibafürtök megjelenése <br> 
A kiadást megelőző tesztelés során megtalált hibák többsége rendszerint néhány modulban van, vagy ezen 
modulok felelősek a működési meghibásodások többségéért. A megjósolt hibafürtök és a tesztelés vagy
működés során ténylegesen megfigyelt hibafürtök fontos bemenetként szolgálnak a tesztelési erőforrások 
összpontosítása érdekében alkalmazott kockázatelemzés számára (ahogy a 2. elvben említettük) <br> 
5. Kísérd figyelemmel a féregirtó paradoxont <br> 
Ha ugyanazokat a teszteket hajtjuk végre újra és újra, akkor ezen tesztek egy idő után nem fognak új hibákat 
találni. Ahhoz, hogy új hibákat találjunk, a létező teszteket és tesztadatokat módosítani kell, illetve új teszteket 
kell írni. (A tesztek egy idő után már nem hatékonyak a hibák megtalálásában csakúgy, ahogyan egy idő 
után a féregirtók sem hatékonyak a rovarok elpusztításában.) Néhány esetben például az automatikus 
regressziós tesztelés esetében a féregirtó paradoxonnak egy előnyös kimenete is van, ami a regressziós 
hibák viszonylag alacsony száma. <br> 
6. A tesztelés függ a körülményektől <br> 
A tesztelést különböző körülmények esetén különbözőképpen hajtják végre. Például egy biztonságkritikus 
ipari irányító szoftvert másképp tesztelnek, mint egy e-kereskedelmi mobilalkalmazást. Egy másik példában, 
a tesztelés egy Agilis projektben különbözik egy szekvenciális szoftverfejlesztési életciklust alkalmazó projekt 
tesztelésétől (lásd: 2.1-es fejezet). <br> 
7. A hibamentesség egy téveszme <br> 
Néhány szervezet azt várja el, hogy a tesztelők minden lehetséges tesztet le tudjanak futtatni és minden 
lehetséges hibát megtaláljanak, de az 1. és a 2. alapelv kimondja, hogy ez lehetetlen. Továbbá téveszme 
(téves meggyőződés) azt várni, hogy csupán azzal, hogy sok hibát találnak meg és javítanak ki, biztosítják a 
rendszer sikerességét. Például a meghatározott követelmények teljeskörű tesztelése és az összes talált hiba 
kijavítása még mindig eredményezhet egy nehezen használható rendszert, ami nem elégíti ki a felhasználók 
összes igényét és elvárását, vagy más hasonló rendszerekhez képest silányabb minőségű. <br> 
#### ✅ Mi az egységtesztelés (unit testing)? Ki felelős az egységtesztek írásáért?
Az egységtesztelés (unit testing) egy olyan tesztelési technika, amelynek célja a program legkisebb egységeinek (általában függvényeknek vagy metódusoknak) külön-külön való tesztelése. A teszt célja annak biztosítása, hogy az egyes egységek megfelelően működnek a várt módon. <br>
A komponens tesztelését általában a kódot író fejlesztő végzi, de minimum a tesztelt kódhoz való hozzáférés
szükséges hozzá. A fejlesztők felváltva is végezhetik a fejlesztési feladataikat, illetve a hibák megtalálását,
kijavítását. <br>
#### ✅ Mik a tesztszintek, és mi a különbség köztük?
• komponenstesztelés <br>
• integrációs tesztelés <br>
• rendszertesztelés <br>
• elfogadási tesztelés <br>
A különbség az, hogy a különböző tesztszintek más-más célokra összpontosítanak: az egységtesztelés az egyes modulok helyes működésére, míg a rendszertesztelés az egész rendszer működésére koncentrál. <br>
#### ✅ Mi a különbség a verifikáció és a validáció között?
Verifikáció: A verifikáció azt jelenti, hogy a szoftver megfelelően épül fel, vagyis a fejlesztés során ellenőrizzük, hogy a rendszer helyesen készül el a specifikációk és követelmények szerint. A verifikáció célja annak biztosítása, hogy a "megfelelő módon" készül-e el a termék. <br>
Validáció: A validáció azt jelenti, hogy a szoftver megfelel a felhasználói igényeknek és a valós használati környezetnek. A validáció célja annak biztosítása, hogy a "helyes" terméket készítettük el, amely valóban azt nyújtja, amit a felhasználók várnak. <br>

#### ✅ Mik a tesztelési típusok, és mi a különbség köztük?
• Funkcionális tesztelés: A rendszer funkcionális tesztelése olyan teszteket foglal magában, melyek kiértékelik a rendszer által
végzendő funkciókat. <br>
• Nemfunkcionális tesztelés: A rendszer nemfunkcionális tesztelése során a rendszerek és szoftverek jellemzőit vizsgáljuk, például a
használhatóságot, a teljesítmény-hatékonyságot vagy a biztonságot. <br>
• Fehérdoboz tesztelés: A fehérdoboz tesztelés a rendszer belső szerkezete vagy az implementáció alapján származtatja a
teszteseteket. A belső szerkezet tartalmazhat kódot, architektúrát, munkafolyamatokat és/vagy
adatfolyamokat a rendszeren belül. <br>
• Funkcionális tesztelés: A rendszer funkcionális tesztelése olyan teszteket foglal magában, melyek kiértékelik a rendszer által
végzendő funkciókat. <br>
• Változásokhoz kapcsolódó tesztelés: Ha egy rendszeren változtatásokat eszközölnek, pl. hibajavítás miatt, vagy hogy új funkciókat vezessenek
be, esetleg a meglévőket módosítják, le kell tesztelni azt, hogy a változtatások valóban javították-e a hibát,
vagy helyesen hajtották-e végre a funkció implementálását, és a változtatások nem jártak-e előre nem látható
következményekkel.<br>

#### ✅ Mi a különbség a fehér doboz, szürke doboz és fekete doboz tesztelés között?
Fehér doboz tesztelés: A tesztelő hozzáfér a kódhoz és annak struktúrájához, és a tesztelés során az implementációt és a belső működést ellenőrzi. A cél a kód hibáinak megtalálása.<br>
Szürke doboz tesztelés: A tesztelő részleges hozzáféréssel rendelkezik a rendszer belső működéséhez, így a tesztelés részben a kódot, részben pedig a felhasználói oldalt célozza meg.<br>
Fekete doboz tesztelés: A tesztelő nem látja a kódot, és csak a rendszer bemeneteit és kimeneteit vizsgálja. A tesztelés célja annak biztosítása, hogy a szoftver az elvárt módon működjön a felhasználói szempontból.<br>

#### ✅ Mi a különbség a felhasználói elfogadási teszt (UAT) és a rendszerteszt között?
Felhasználói elfogadási tesztelés (UAT): <br>
A felhasználók által a rendszeren végzett felhasználói elfogadási tesztek általában arra irányulnak, hogy
valós vagy szimulált éles működési környezetben validálják azt, hogy a rendszer a leendő felhasználók
számára alkalmas lesz-e a használatra. <br>
Rendszertesztelés: <br>
A rendszertesztelés a teljes rendszer vagy termék viselkedésére és képességeire összpontosít, gyakran
figyelembe véve a végpontok közötti feladatokat, amelyeket a rendszer képes végrehajtani, és a
nemfunkcionális viselkedéseket, amelyeket ezen feladatok végrehajtása közben mutat.<br>

#### ✅ Sorolj fel különbségeket a regressziós tesztelés, a füsttesztelés és az újratesztelés között!
Regressziós tesztelés: A regressziós tesztelés célja annak biztosítása, hogy a szoftver új verziója vagy változtatása nem okozott hibákat a már meglévő funkciókban.<br>
Füsttesztelés: A füstteszt gyorsan ellenőrzi, hogy a rendszer alapvető funkciói működnek-e. Ez a tesztelési fázis az elsődleges hibák kiszűrésére szolgál. <br>
Újratesztelés: Az újratesztelés célja annak biztosítása, hogy a már korábban tesztelt hibák javításra kerültek, és nem okoztak új problémákat a rendszerben. <br>

#### ✅ Mi a különbség a statikus és dinamikus tesztelés között?
Statikus tesztelés: A statikus tesztelés a munkatermékek manuális vizsgálatára (azaz felülvizsgálatok), illetve a kód vagy más
munkatermékek eszközvezérelt vizsgálatára (azaz statikus elemzésre) támaszkodik. <br>
Dinamikus tesztelés: A dinamikus tesztelés a program futtatásával történik, és a szoftver viselkedését vizsgálja a különböző bemenetekre adott válaszok alapján. <br>

### ✅ Hasonlítsd össze a V-modellt, a vízesés modellt és az Agile megközelítést a tesztelés szempontjából!


<img src="https://t4.ftcdn.net/jpg/03/90/15/65/360_F_390156585_8w1lsOyICIAOvDCU8tExXW2QwLCOFwXD.jpg" alt="image" width="550" height="400">


<img src="https://i.imgur.com/S38EBJw.png" alt="image" width="550" height="400">   <img src="https://segedletek.level14.hu/assets/img/modszertan-vizeses.svg" alt="image" width="550" height="400">


<img src="https://promanconsulting.hu/wp-content/uploads/2022/03/agilis-modszertanok-optimized.jpg" width="550" height="400">

V-modell: A V-modell egy szekvenciális fejlesztési és tesztelési megközelítés, ahol a tesztelési fázisok párhuzamosan futnak a fejlesztési fázisokkal. A tesztelés már a tervezési fázisban elkezdődik, és minden fejlesztési lépéshez tartozik egy tesztelési lépés. <br>
Vízesés modell: A vízesés modell egy lineáris és szigorú megközelítés, amelyben a tesztelés csak a fejlesztési folyamat végén történik. Nincs visszacsatolás a tesztelés és a fejlesztés között. <br>
Agile megközelítés: Az Agile megközelítés iteratív és rugalmas, ahol a tesztelés folyamatosan végbemegy a fejlesztés során. Az Agile tesztelés folyamatos visszajelzést ad a szoftverről, és az új funkciók minden iterációja után tesztelést végeznek. <br>
A fő különbség az, hogy a V-modell és a vízesés modell inkább lineáris, míg az Agile folyamatos, iteratív és rugalmas tesztelési folyamatot biztosít. <br>




## Reporting, Bugs
<img src="https://moolya.com/blog/wp-content/uploads/2023/05/Bug-Report.png" alt="image" width="300" height="220">

#### ✅ Milyen lépéseket követnél egy hiba megtalálásakor?
1. Meggyőződöm a hiba körülményeiről, mi váltotta ki a hibát és megpróbálom reprodukálni a hibát.
2. A hibát megfelelően kell dokumentálni, ami tartalmazza a tesztelési környezet leírását, a várt és a tényleges eredményt, a hiba reprodukálásának lépéseit, hiba súlyosságának szintjét, stb.
3. A hiba dokumentálását átadom a szoftverért felelős fejlesztő(k)nek, akik megpróbálják megjavítani a talált hibát.

#### ✅ Beszélj a gyakori tesztjelentésekről és részleteikről!
1. Tesztterv (Test Plan): A tesztelési folyamat előre meghatározása, a tesztelés céljainak és módszertanának dokumentálása. <br>

2. Tesztesetek (Test Cases): A tesztelés során végrehajtott egyes tesztelési lépések részletes dokumentálása, a várható eredmények meghatározásával.

3. Hibajelentés (Bug Report): A tesztelés során talált hibák, anomáliák dokumentálása és kommunikálása a fejlesztők felé.

4. Tesztelési eredmények jelentés (Test Execution Report): A tesztelési ciklus befejezése után készül el, és összegzi a tesztelés során elért eredményeket.

5. Összefoglaló tesztjelentés (Test Summary Report): A tesztelési folyamat végén készült összegzés, amely tartalmazza a tesztelés általános eredményeit, a tesztelt funkciókat és a talált hibákat.


#### ✅ Mit tartalmaz egy hibajelentés?
1. Hibaazonosító: Segít a hibák nyomon követésében és azonosításában
2. Cím: A hiba rövid leírása, ami jól tükrözi a hiba jellegét
3. Hiba leírása: A hiba részletesebb bemutatása, ami leírja, hogy mi történt és mi a probléma
4. Reprodukálási lépések: Bemutatja, hogy hogyan lehet az adott hibát újra előteremteni, reprodukálni
5. Elvárt eredmény: Leírja az általunk elvárt eredményt, ha nem lenne hiba.
6. Tényleges eredmény: A valóban megjelenő eredményt írja le, ami a hibás változatot mutatja be.
7. Hiba súlyossága és prioritása
8. Környezeti információ: a tesztelés során használt környezet leírása
9. Hiba típusa
10. Hiba állapota

#### ✅ Hogyan rangsorolnál egy hibát?

A hibák jelentősségük és súlyosságuk szerint rangsorolhatók:
1. Alacsony: Általában nem befolyásolja a rendszer működését. Lehetnek elírások vagy UI-hibák
2. Közepes: A rendszer használata közben zavaró hibák, de nem minden esetben befolyásolják a rendszer működését.
3. Magas: A rendszer ugyan általában használható, de olyan hibákat tartalmaz, amik egyes funkciók működését befolyásolhatják.
4. Kritikus: A rendszert magas szinten befolyásoló hibák, amik megakadályozzák a rendszer megfelelő működését, akár teljesen használhatatlanná téve azt.


## Test Automation, Selenium
<img src="https://media.licdn.com/dms/image/C4D12AQE3GOyVsZazOw/article-cover_image-shrink_600_2000/0/1583830696602?e=2147483647&v=beta&t=bYHbKyhMoWsMgtEug6eSf3m0db5ZtGEl437TeS1qkfI" alt="image" width="320" height="220">

#### ✅ Melyik teszteseteket érdemes automatizálni és melyiket nem?
Érdemes a gyakran ismétlődő teszteket, nem gyakran változó funkciók tesztelését automatizálni időspórolás érdekében.<br>
Nem szükséges vagy éri meg a ritkábban használt vagy gyakran változó funkciók és részek tesztelését automatizálni 

#### ✅ Írj le egy jó automatizált tesztet!
Konkrét funkciót teszteljen, legyen többször futtható és működjön megbízhatóan. Legyen integrálható folyamatos integrációs/telepítési folyamatokba. A program fejlődése során legyen az automatizált teszt könnyen frissíthető. A teszt ne igényeljen manuális közbeavatkozást

#### ✅ Mi a Selenium, Selenium IDE és Selenium WebDriver?
Selenium<br>
A Selenium egy nyílt forráskódú tesztelő keretrendszer, amelyet webalkalmazások automatizált tesztelésére használnak. Támogatja több böngészőt (pl. Chrome, Firefox, Safari) és operációs rendszert, és lehetővé teszi, hogy a tesztelők szimuláljanak felhasználói interakciókat, mint például kattintás, szövegbevitel vagy űrlapok kitöltése.

Selenium IDE<br>
A Selenium IDE (Integrated Development Environment) egy böngészőbővítmény, amely lehetővé teszi a felhasználók számára, hogy egyszerűen rögzítsenek és lejátszanak automatizált teszteket közvetlenül a böngészőben. Ez egy könnyen használható, interaktív eszköz, ideális azok számára, akik nem programozók, de gyorsan szeretnének teszteket készíteni.

Selenium WebDriver<br>
A Selenium WebDriver a Selenium keretrendszer egyik kulcsfontosságú komponense, amely programozói szinten lehetővé teszi a tesztelők számára, hogy böngészőket irányítsanak. A WebDriver közvetlenül kommunikál a böngészőkkel, és szimulálja a felhasználói interakciókat (például kattintásokat, billentyűleütéseket), így ideális választás a fejlettebb, skálázható automatizált tesztelési megoldásokhoz.

#### ✅ Hogyan lehet azonosítani a webes elemeket?
A webes elemeket különböző lokátorok segítségével tudjuk azonosítani, amik lehetnek: ID, név, osztály neve, HTML tag neve, link szövege, CSS Selector vagy XPath.

#### ✅ Hogyan lehet várni az elemekre, és mi lehet a probléma? Gyűjtsd össze a lehetséges hibákat és okokat!
A tesztelés végrehajtása előtt meg kell várni, hogy az oldal teljesen betöltődjön. Létezik implicit várakozás, ami minden elemre vonatkozik (meghatározott ideig vár), az explicit várakozás az adott elemekre vonatkozik és addig vár, amíg a megadott feltételek teljesülnek.<br>
Gyakori hibák:
- NoSuchElementException: nem létezik az adott elem, ami meg van adva a tesztben
- ElementNotVisibleException: az elem jelen van a DOM-ban, de valamiért nem látható vagy nem interakcióra kész
- StaleElementReferenceException: az elem jelen volt, de már nem található meg a DOM-ban
- TimeoutException: lejárt a várakozási idő, de a kívánt feltétel nem teljesült
- WebDriverException: A Selenium nem tudott kommunikálni a böngészővel vagy más hiba történt
- InvalidSelectorException: A CSS vagy XPath szelektor hibás vagy érvénytelen.

#### ✅ Hasonlítsd össze a POM és a Keyword Driven Testing megközelítéseket!
A POM-alapú megközelítés az oldal objektumait és elemit használja fel a tesztesetekhez. Ezeket könnyebben lehet újra felhasználni és jobban átláthatóbbak, de az esetek megírásához programozási tudás szükséges.<br>

A Keyword Driven Testing megközelítés kulcsszavakat használ a tesztesetekben (például Click, EnterText). Megírásukhoz nem feltétlenül szükséges programozási tudás.

#### ✅ Mi a különbség a TDD és BDD között?
- TDD: tesztalapú fejlesztés. Automatizált teszteseteket ír meg a fejlesztő a szoftver lefejlesztése előtt és azokra alapozva írja meg a programot. Kódalapú a működése, ezért a fejlesztők használják.
- BDD: viselkedésalapú fejlesztés. Természetes nyelven írja le a várt eredményt, ezért nem csak fejlesztők használják, hanem például üzleti döntéshozók is.

#### ✅ Mi az API tesztelés és miért hasznos?
Az API tesztelés a program API-ait teszteli le több szempont alapján. Ezek közé tartozik a kérések és a kapott válaszok ellenőrzése, megfelelő adatot küld-e vissza a kérésekre, biztonsági és teljesítményi szempontok. Az API-k fontos részei a programnak, melyek lehetővé teszik más programoknak, hogy lekérjék a megfelelő adatokat az eredeti program API-i segítségével. Ezek mellett könnyebben írhatóak tesztesetek az API teszteléséhez.

#### ✅ Mi az adatvezérelt tesztelés és miért hasznos?
Az adatvezérelt tesztelés (Data-Driven Testing, DDT) egy tesztelési módszer, amelyben a tesztelési lépések egyetlen szkriptben vagy programban vannak megírva, de a különböző tesztesetek adatait különböző adatforrásokból (például Excel, CSV fájl, adatbázis vagy XML) töltjük be.<br>
Ahelyett, hogy minden tesztesetet külön kóddal írunk meg, ugyanazt a tesztlogikát használjuk, és különböző bemeneti adatokkal futtatjuk le azt, így egyszerre több esetre tudjuk alkalmazni.

#### ✅ Mik a kihívások és ajánlott eljárások a dinamikusan betöltött webes elemekkel?
A dimanikusan betöltődő webes elemek (pl. JavaScript vagy AJAX által betöltött elemek az oldal eredeti betöltése után) új kihívásokat vezetnek be a szoftvertesztelésben, különösen az automatizált UI tesztelés során.

Kihívások:
- Időzítési problémák/szinkronizáció
- Ingadozó (flaky) tesztek
- Elavult (stale) elem hivatkozások
- Komplex vagy instabil lokátorok
- Aszinkron viselkedés
- Rejtett vagy késleltetve betöltődő (lazy-loaded) elemek

Ajánlott eljárások:
- Explicit várakoztatások használata: Például a javascriptes sleep() helyett érdemes a tesztelési keretrendszer által biztosított várakoztatási elemeket használni (pl.: Selenium: WebDriverWait, ExpectedConditions).
- Fix várakoztatások elkerülése
- Stabil lokátorok használata: például data-testid vagy aria-label attribútumok használata és az XPath helyett érdemes CSS-lokátorok használni
- A láthatóság és az interakcióképesség ellenőrzése: az elem legyen látható és elérhető is
- Automatikus újrapróbálás (retry logic) implementálása
- Page Object Model struktúra használata


#### ✅ Mik a mobil tesztautomatizálás kihívásai?
A mobil tesztautomatizálás számos kihívással rendelkezik, amik nem jellemzőek az asztali, vagy a webes tesztautomatizálásnál.
Ezek a kihívások:
- Rengeteg különböző eszköz és operációs rendszer jelenléte a mobilos piacon
- Sok eltérő UI és képernyőfelbontás
- Bonyolultabbak a tesztelési eszközök és keretrendszerek, mint a webes társaiknál
- Gyakran lassabban futnak le a tesztek a mobileszközökön
- Gesztusok és szenzorok kezelése
- Ingadozó (flaky) tesztek, szinkronizációs hibák
- Engedélykérések és egyéb rendszerüzenetek lekezelése

## Haladó témák
<img src="https://www.softwaretestinghelp.com/wp-content/qa/uploads/2020/05/DevOps-in-a-Selenium-Testing.png" alt="image" width="320" height="220">

#### ✅ Mi a különbség a CI és CD között?
- CI – Continuous Integration:<br>
A CI a több fejlesztőtől származó kódmódosítások automatikus, gyakori (általában naponta többszöri) integrálásának gyakorlata egy közös tárolóba.
- CD – Continuous Delivery vagy Continuous Deployment:  
  - Continuous Delivery:<br>
  Az alkalmazás automatikusan elkészül, tesztelésre és csomagolásra kerül, és készen áll a kézi telepítésre a termelésbe.
  - Continuous Deployment:<br>
  Minden sikeres kódváltozás, amely átmegy az automatizált tesztelésen, automatikusan, kézi jóváhagyás nélkül bekerül a termelésbe.


#### ✅ Írj le egy Continuous Delivery folyamatot!
A Continuous Delivery egy szoftverfejlesztési gyakorlat, amely során a kódváltozások automatikusan tesztelésre kerülnek és kiadásra kész állapotba kerülnek. Habár maga a bevezetés manuálisan történik meg, a folyamat többi része teljesen automatizálva van.

#### ✅ Hasonlítsd össze két népszerű CI rendszert, ezek közül az egyik legyen a Jenkins!
Jenkins (népszerű, nyílt forráskódú CI eszköz) és a GitHub Actions (GitHub-ba integrált, modern CI/CD megoldás) összehasonlítása:
- Típus:<br>
  - Jenkins: Helyi üzemeltetésű vagy felhőalapú, nyílt forráskódú rendszer
  - GitHub Actions: Teljesen felhőalapú
- Beállítás:<br>
  - Jenkins: Manuális telepítés és beállítás
  - GitHub Actions: GitHub-ba integrált eszköz
- Konfiguráció:<br>
  - Jenkins: Jenkinsfile (Groovy syntax), GUI pipelines
  - GitHub Actions: YAML-fájlok itt: .github/workflows/
- Integráció:<br>
  - Jenkins: Bármilyen VCS-t támogat (Git, SVN, Mercurial, stb.)
  - GitHub Actions: Legjobb működés a GitHub repository-kal
- Pluginok:<br>
  - Jenkins: 1800+ közösségi plugin
  - GitHub Actions: Kevesebb plugin
- Biztonság:<br>
  - Jenkins: Manuális beállítást igényel
  - GitHub Actions: A GitHub biztonsági megoldásait használja
- Ár:<br>
  - Jenkins: Ingyenes (helyi), de gondoskodni kell a karbantartásról
  - GitHub Actions: Ingyenes nyilvános repoknál, privát repoknál fizetős
- Kiknek javasolt:<br>
  - Jenkins: Nagyobb vállalatok
  - GitHub Actions: Startupok, hobbi projektek

#### ✅ Mi a Docker és miért hasznos?
Egy nyílt forráskódú platform, ami lehetővé teszi a fejlesztőknek alkalmazások készítését és futtatását külön konténerekben. A konténer egy könnyű és futtatható szoftvercsomag, ami mindent tartalmaz, ami kellhet egy alkalmazás futtatásához (kód, runtime, függőségek, konfigurációs fájlok, stb.).

Ezért hasznos:
- Megoldja a "működik-e a gépemen" problémát - bármilyen környezetben ugyanúgy fut az alkalmazás
- Környezeti izoláció: minden konténer teljesen izolálva fut, ezzel több alkalmazást (különböző verziókkal) lehet futtatni ugyanazon a rendszeren kompatibilitási gondok nélkül
- Gyorsaság és hatékonyság (gyorsabb a virtuális gépeknél)
- CI/CD integráció
- Hordozhatóság
- Könnyebben lehet tesztelni