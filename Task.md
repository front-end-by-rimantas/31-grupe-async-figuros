# Užduotis

Sukurti folderi "figuros" (rankiniu budu) .data folderyje.

`figuruDydziai` kintamaji uzpildyti nurodytu kiekiu objektu, kuriu kiekvienas nusako staciakampio dydi

Sugeneruotu figuru krastiniu dydziai turi buti atsitiktiniai ir intervale nuo 1 iki 10 imtinai.

Sukurti failus, kiekvienai figurai:

- irasyti i `figuros` folderi
- failo pavadinimo schema: figura-[index].json
- index yra numeris, kelinta tai figura `figuruDydziai` kintamajame

Perskaitome failus ir juos atnaujiname papildomomis savybemis `plotas` ir `hash`.

Ploto reiksme gauname panaudoje `Figura.size()` metoda

Hash yra apskaiciuojamas naudojant `utils.hash()` metoda, kuriam yra duodama `string` tipo reiksme, kuria sulipdome tokiu principu: figura-[plotis]-[aukstis]-[plotas]

Isspausdinti visu failu pavadinimus kaip `array` su `data.list()` metodu

## Pastabos

Lauztyniai skliaustai neieina i turini, tai tik zymuo, jog toje vietoje yra kintama reiksme.
