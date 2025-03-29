# Monster Survivors

## Trailer

Launch Trailer - [trailer](https://youtu.be/HQ4NfrJCAhM)

## Videa
1. Prototyp - https://youtu.be/RDF0BJynKNI?si=RMEFsZWtxLZ7DesB
2. Prototyp - https://youtu.be/fZDbZ-dyOqo

## 1. Základní koncepce

Projekt „Monster Survivors“ je realizován v herním enginu Godot s využitím skriptovacího jazyka GDScript. Hra spadá do žánru roguelike s prvky „survivor“, inspirovaného principy her jako je „Vampire Survivors“. Hráč se ujímá role postavy, která čelí neustále narůstajícím vlnám nepřátelských monster. Cílem je přežít po stanovenou dobu. Za eliminaci monster hráč získává zkušenostní body (XP), které slouží k vylepšování zbraní a brnění, čímž se zvyšuje šance na přežití v náročnějších fázích hry.

## 2. Game Design

„Monster Survivors“ nabízí intuitivní, ale komplexní herní mechanismy. Hráč ovládá postavu, která se pohybuje po aréně a automaticky útočí na nepřátele. Každý nepřítel má specifické atributy, jako je životnost (HP), rychlost pohybu a útočná síla. Hráčova postava má dva hlavní atributy, zbraň a brnění, které lze vylepšovat za získané XP.

* **Atributy:**
    * Životnost (HP) nepřítele: Určuje, kolik zásahů nepřítel vydrží.
    * Útočná síla nepřítele: Určuje, kolik poškození nepřítel způsobí hráči.
    * Síla zbraně hráče: Určuje poškození, které hráč způsobí nepřátelům.
* **Systém vylepšování:** S každým dosaženým levelem hráč obdrží možnost vylepšit si jeden ze svých dvou atributů.
* **Vlny nepřátel:** Nepřátelé se objevují ve vlnách, jejichž obtížnost se postupně zvyšuje.

## 3. Grafika

Hra využívá minimalistickou 2D grafiku s jednoduchým pixelartovým stylem. Grafické zpracování je čisté a přehledné, což umožňuje hráči snadno se orientovat v herním prostředí. Pro tvorbu grafických prvků byly použity dostupné assety z online zdrojů, s uvedením autorů:

* Nepřátelé: [https://free-game-assets.itch.io/free-low-level-monsters-pixel-icons-3232?download](https://free-game-assets.itch.io/free-low-level-monsters-pixel-icons-3232?download)
* Vzhled postavy: [https://otsoga.itch.io/free-medieval-npcs-witch-and-swordswoman](https://otsoga.itch.io/free-medieval-npcs-witch-and-swordswoman)

## 4. Zvuky

Zvukové efekty (SFX) byly vytvořeny pomocí softwaru Audacity, kde byl použit záznam vlastního hlasu. Zvuky jsou navrženy tak, aby podtrhovaly dynamiku hry a poskytovaly hráči zpětnou vazbu na jeho akce.

* Zvukové efekty pro útoky, zásahy, a pohyb.
* Zvukové efekty pro herní prostředí.

## 5. Hudba

Hudební podklad hry byl vybrán z platformy YouTube, konkrétně skladba: [https://youtu.be/9r8VtP5kdoo?si=-NwzwuVlb6hXvM_X](https://youtu.be/9r8VtP5kdoo?si=-NwzwuVlb6hXvM_X). Hudba je použita k vytvoření atmosféry a podtržení herního zážitku. Hlasitost a intenzita hudby se dynamicky mění v závislosti na dění ve hře.

## 6. Implementace

Implementace hry probíhá v herním enginu Godot. Byla vytvořena řada prototypů pro testování jednotlivých herních mechanismů, jako je pohyb postavy, útoky, a interakce s nepřáteli. Godot umožňuje efektivní správu grafických a zvukových assetů, stejně jako implementaci herní logiky pomocí GDScriptu.

* Prototypy pro pohyb postavy, útoky, a interakce s nepřáteli.
* Integrace grafických a zvukových assetů.
* Implementace herní logiky pomocí GDScriptu.

## 7. Propagace

Pro propagaci hry bude vytvořen trailer, který představí herní mechanismy a vizuální styl. Trailer bude zveřejněn na YouTube.

* Koncepce traileru: Dynamické záběry z hraní, ukázka herních mechanismů a vizuálního stylu.
* Platformy pro zveřejnění: YouTube, sociální sítě.

## 8. Finální hra

Finální verze hry „Monster Survivors“ nabízí kompletní herní zážitek s vyváženou obtížností a dynamickým vývojem postavy.

![screenshot1](https://github.com/user-attachments/assets/2903192c-3e52-4ccb-882d-2708fa1ae4d9)
![upgrade](https://github.com/user-attachments/assets/74610e18-76e9-4f18-ab9a-01e8d77fa5ab)
![menu](https://github.com/user-attachments/assets/7c934b03-a6cd-4c3b-8196-d0c07f0cf5fe)



## 9. Závěr

Vývoj hry „Monster Survivors“ byl náročným, ale obohacujícím procesem. Největší výzvou bylo vyvážení herních mechanismů a zajištění plynulého herního zážitku. Tento problém byl vyřešen iterativním testováním a úpravami herních parametrů. Dalším úskalím bylo nalezení a integrace vhodných grafických a zvukových assetů, což bylo vyřešeno pečlivým výběrem z dostupných online zdrojů.
