#https://mega.nz/#!UR4yHZRD!jroqGBecQCf7q4gwCjNCz7S5e7eXL9mm-OkG_a5GPec

#KGameProject - a strategy online game for Android

#Sistemos dokumentacija

*Android aplikacija nėra platinama Google Store todėl norint ją išbandyti reikės leisti nežinomų šaltinių diegimą į savo Android įrenginį (Android 3.0 arba naujesnės versijos).

*Žaidimą galima testuoti ir Windows aplinkoje.

Įdiegus žaidimą, jame užsiregistravus ir prisijungus būsite nukeltas į savo naujai sukurtą miestą. Mieste galima kurti pastatus, kurie per laiką gamina resursus ir tuos pastatus yra galimybė tobulinti. Tarp šių pastatų yra kareivinės, kur galima išleisti savo resursus samdant armiją. Pasamdyta armija yra matoma žemėlapyje, virš savo miesto. Ji gali judėti ir užimti kitus miestus (užvedant armiją ant kito miesto hex langelio). Žemėlapis susidaro iš X ir Y koordinačių ir kekvienas hex langelis turi savo skirtingą koordinatę. Kovos tarp dviejų armijų vyksta labai paprastai, kiekviena armija turi savo gyvybių ir atakos skaičių, o veiksmas vyksta ėjimais. Norint nugalėti priešą užtenka laikyti savo armiją virš jo miesto nugalėjus priešo kariuomėnę.

#Kas buvo realizuota ir galimos sistemos tobulinimo galimybės?
Realizuota - vartotojo prisijungimas ir registracija, kovos prieš kitus žaidėjus ir kompiuterį mechanika.
Tobulinimo galimybės - kompiuterio valdomų priešų tobulinimas, žaidimo dizaino tobulinimas, palaikymas dideliui kiekiui žaidėjų vienu metu, daugiau žaidimo mechanikų (aliansai tarp žaidėjų, gildijos), miestų valdymas ir kūrimas, daugiau žaidimo rėžimų (pvz. užimti tam tikrą miestą ir jį laikyti ~savaitei norint laimėti), daugiau tipų resursų ir galimybė į žaidimą pristatyti "microtransactions" (galimybė už realius pinigus nusipirkti virtualius resursus).

#Ką būtumėte darą kitaip, jei galetumėte daryti sistemą iš naujo. Kodėl?
Nustatyčiau daugiau kaip vieną žaidėjo samdomos armijos (karių) tipą.

#High Level User Stories
1. As a player I can register via an unused nickname and a password
2. As a player I can use the map interface to locate nearby enemy settlements
3. As a player I can capture and battle other players and AI computer enemies
4. As a player I can have various currencies 
5. As a player I can spend those currencies to produce troops for defence and offense purposes
6. As a player I can send my troops to various locations for scouting, battle or capture purposes
7. As a player I can construct and capture mines which increase my passive currency income
8. As a player I can actively steal currencies from other players by capturing their settlements
9. As a player I can my own troops by color, blue stands for friendly, red for hostile
10. As a player I can respawn in a random location in case my settlement ever gets captured

#Technologies
1. Unity 5.3.5f1 Personal Edition 
2. Java, C#
3. Database Control 

#Copyright
Hex Models - HexGrid template by Daniel Carrier

Icons - Ikariam MMO by Gameforge

DB network template by Unity Solution Studios
