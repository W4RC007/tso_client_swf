# Changes

Changes compared with the original `client.swf` by fodorvvl.

## v0.18.60

- Aktualizovaná kompatibilita s aktuálnou LIVE verziou hry (`6093fccd209dd3fb9db975e25d5bc45df9a0ebf3`) bez zmeny funkcií W4 klienta.

## v0.18.59

- Okno Poslať armádu možno zväčšovať, filtrovať podľa mena a hromadne označiť zobrazených generálov; ich predvolené poradie zodpovedá Hviezde.
- Vyhľadávanie vo Hviezde zahŕňa lokalizované popisy špecialistov a buffov a filter možno vymazať jedným tlačidlom.
- Opakované avatarové oznámenia sa zoskupujú s počítadlom a obnoveným časom zobrazenia.
- Obnovuje sa uložený filter Pathfinder/PvP úloh a správne sa prepína tlačidlo zaplatenia úlohy.
- Pozvanie do dobrodružstva je dostupné aj z kontextového menu hráča mimo chatu.
- Opravený pád pri skorom otvorení tooltipu prehľadu populácie.
- Zachované sú W4 skupiny prieskumníkov, manuálne pole Mystery Boxov, presúvanie a pripínanie okien aj rozšírenia cechu.

## v0.18.58

- Stĺpec Aktívne dobrodružstvá v zozname členov cechu podporuje triedenie kliknutím na hlavičku vrátane šípky smeru.

## v0.18.57

- Opravené zatváranie pripnutých okien Kniha úloh, Kolonie, Kupec, Prehľad ekonomiky a Pošta; po zatvorení už nezostane blokujúca tmavá vrstva.
- Pripnutie uvoľní modálnu vrstvu a odopnutie ju obnoví iba pri oknách, ktoré ju štandardne používajú.

## v0.18.56

- Knihu úloh, Kolonie, Kupca, Prehľad ekonomiky a Poštu možno presúvať za hornú titulkovú lištu a pripnúť.
- Pripnuté okno zostane otvorené pri otvorení ďalšieho okna; krížik alebo vlastné zatváracie tlačidlo ho vždy zavrie a zruší pripnutie.

## v0.18.55

- Krížik vždy zavrie konkrétny Strom vlastností, aj keď je okno pripnuté.
- Pripnutie už znamená iba to, že strom zostane otvorený pri otvorení druhého stromu.
- Nepripnutý strom sa pri otvorení iného stromu nahradí, takže bez pripnutia zostáva otvorené iba nové okno.

## v0.18.54

- Strom vlastností podporuje dve samostatné plne editovateľné, presúvateľné a nezávisle pripínateľné okná pre geológov, prieskumníkov a generálov.
- Pripnutý Strom vlastností zostáva otvorený pri otvorení iných okien a druhý strom sa otvorí vycentrovaný nezávisle od polohy prvého.
- Potvrdenie, zrušenie a serverové spracovanie zmien sú oddelené pre správny strom; rozpracované body druhého stromu sa zachovajú aj pri obnovení dát.
- Hlavné okno geológa, prieskumníka a generála možno presúvať za hornú lištu.
- Okná pri prvom otvorení už krátko neprebliknú v ľavom hornom rohu; vytvorenie, rozloženie a umiestnenie prebehne ešte pred ich zobrazením.

## v0.18.49

- Opravená kompatibilita s aktuálnou LIVE verziou hry; klient teraz obsahuje správny herný hash a aktuálne mapovanie súborov.

## v0.18.48

- Mystery Box odmeny správne zobrazujú XP a PvP XP, zoskupujú rovnaké položky a formátujú veľké množstvá; manuálne číselné pole a synchronizovaný posuvník zostali zachované.
- Pridané voliteľné trvalé zobrazovanie času buffu nad budovami.
- Doplnené hromadné serverové akcie, nastaviteľné filtrovanie avatarových správ a odovzdávanie nových logových riadkov externým doplnkom.
- Obchodný filter bezpečne zvláda neúplný stav a obchodné požiadavky sa mimo domovskej zóny neposielajú.
- Zachované všetky W4 úpravy prieskumníckych skupín, Hviezdy, Hospody, presúvania okien a questových tlačidiel.

## v0.18.47

- Opravená zelená dvojpostavičková značka členstva prieskumníkov v skupine v okne Hviezda; modrá ikonka urýchlenia návratu za diamanty zostala nezmenená.

## v0.18.46

- Opravené zelené označenie prieskumníkov zaradených do skupiny v okne Hviezda; členstvo sa načíta z rovnakých skupinových dát ako položky skupín.

## v0.18.45

- Rozšírené okno cechu o nastaviteľné stĺpce s trvalým uložením šírok a lokalizovaným názvom aktívneho dobrodružstva každého člena.
- Obnovená pôvodná zelená fajka na potvrdenie splnených questov; diamantové okamžité dokončenie zostáva samostatné.

- Presúvanie vybraných herných okien vrátane okien budov a Excelsioru.
- Skupiny prieskumníkov priamo v Hviezde, ich vlastné usporiadanie, premenovanie a otvorenie správy skupiny v Hospode.
- Zelené označenie prieskumníkov, ktorí sú pridelení do skupiny.
- Zobrazenie stavu, členov a reálneho trvania skupinového hľadania vrátane bonusov a schopností.
- Stabilné spúšťanie skupinového hľadania kompatibilné s používaným herným serverom.
- Hromadné otváranie Mystery Boxov a balíkov s manuálnym číselným poľom, validáciou množstva a synchronizovaným posuvníkom.
- Zlúčenie rovnakých odmien z Mystery Boxov a vodorovné zobrazenie v presúvateľnom a škálovateľnom okne.
- Upravené rozloženie receptov kultúrnych budov, ktoré centruje obsah do jedného riadka, ak sa zmestí.
