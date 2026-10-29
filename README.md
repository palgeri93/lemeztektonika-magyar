# Lemeztektonika – magyar interaktív tananyag

A `module04swf.swf` magyar adaptációja. A HTML-oldal a mellékelt Ruffle JavaScript/WebAssembly lejátszóval futtatja a magyarított eredeti SWF-et. Ez nem teljes JavaScript-újraírás.

## Használat

A GitHub Pages oldalon közvetlenül használható. Helyben Windows alatt az `inditas.cmd` indítja (Python 3 szükséges). Másik lehetőség: `python -m http.server 8000`, majd `http://localhost:8000/`. A HTML közvetlen megnyitása helyett HTTP-kiszolgáló szükséges.

A Kezdőlap a bevezetőt mutatja. A Részletek nézet a kilenc lemeztektonikai folyamatot szemléltető rajzokhoz vezet. A Mozgás nézetben az idővonal nyilával a 150 millió évvel ezelőtti állapot és a jelen között válthatsz. A Térképek nézetben alaptérképet és lemeztektonikai rétegeket választhatsz, valamint megnyithatod a hozzájuk tartozó magyarázatokat. A hosszú szövegek görgethetők. A Ma rövidítés millió évet jelent.

## Magyar adaptáció

Magyar feliratok, lemeznevek, jelmagyarázat, 18 magyarázó szöveg és magyar tizedesvesszők a sebességadatokban. Az eredeti programkód szerkezetét megtartva a parancskód szöveges állandóit fordítottuk.

A magyarázatok szerkesztett magyar átdolgozások. Az eredeti néhány félrevezető példáját pontosítottuk: a hasadékvölgyi tavaknál a Tanganyika- és a Bajkál-tó szerepel; a forrópontok mozdulatlanságát nem tekintjük abszolútnak. Az eredeti térképek és rekonstrukciók szemléltető, történeti tananyagok, nem élő földrengés- vagy vulkánadatok és nem előrejelzések. A térképen a Pacifikus név a Csendes-óceáni-lemezt jelöli.

Forrás: a felhasználó által átadott `module04swf.swf` (Plate Tectonics Module). A kapott fájlból az eredeti jogosult és a felhasználási engedély pontos adatai nem voltak azonosíthatók. Az eredeti program és képek jogai az eredeti jogosultaknál maradnak; az adaptáció nem hivatalos kiadás. A fordítási jegyzéket a `forditas.json` tartalmazza.

Ruffle: MIT / Apache-2.0; a licencek a `ruffle` mappában találhatók.
