# Pacman knock off

Kopie hry Pacman využívající jazyk C s knihovnou SDL2

## Ovládání

* W/šipka nahoru = nahoru
* S/šipka dolů = dolů
* D/šipka doprava = doprava
* A/šipka doleva = doleva

## NPC

* Blinky - červený, následuje pozici hráče (slepě), rychlostí jen o málo nižší než hráč
* Inky - modrý, následuje pozici hráče (slepě), rychlostí nižší než hráč
* Pinky - růžový, při nárazu do kraje mapy si vybere náhodný směr, kterým bude pokračovat, rychlost stejná jako hráč
* Clyde - oranžový, při nárazu do kraje mapy si vybere náhodný směr, kterým bude pokračovat, rychlost stejná jako hráč

## Mechanismus hry

* skóre je promítáno vpravo nahoře, 1 sebraný point = 50 bodů ke skóre
* konec hry, ať už posbíráním všech bodů nebo ztrátou všech životů, je následován zvukovým efektem a hráč je přesunut doprostřed mapy, odkud se do ukončení programu nedostane

## Herní screenshoty
![alt text](https://github.com/MartinOpa/pacman/blob/master/ukazka1.png?raw=true)
![alt text](https://github.com/MartinOpa/pacman/blob/master/ukazka2.png?raw=true)
![alt text](https://github.com/MartinOpa/pacman/blob/master/ukazka3.png?raw=true)
