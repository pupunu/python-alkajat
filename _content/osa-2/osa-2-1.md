# Totuusarvot

Tähän mennessä meillä on ollut kahdenlaista tietoa: lukuja ja merkkijonoja eli tekstiä. Niiden lisäksi yleisin tietotyyppi on **totuusarvo**, joka kertoo onko jokin totta vai ei. Totuusarvolla on vain kaksi mahdollista arvoa: ```True``` eli tosi tai ```False``` eli epätosi.

Totuusarvoja tuottava muun muassa vertailut. Luvuille on paljon vertailuja, jotka ovat mahdollisesti tuttuja myös matematiikantunneilta. Pythonissa on seuraavat lukujen vertailut, joista tulee aina tulokseksi joko ```True``` eli totta tai ```False``` eli epätotta.

| luku1 == luku2 |  ovatko luvut yhtä suuret|
| luku1 != luku2  |  ovatko luvut erisuuret|
|luku1 < luku2|  onko _luku1_ pienempi kuin _luku2_|
|luku1 <= luku2 |  onko _luku1_ pienempi tai yhtä suuri kuin _luku2_|
|luku1 > luku2 |  onko _luku1_ suurempi kuin _luku2_ |
|luku1 >= luku2 |  onko _luku1_ suurempi tai yhtä suuri kuin _luku2_|

Myös muita asioita kuin lukuja voidaan vertailla. Esimerkiksi merkkijonoja voidaan vertailla, joskin ei yhtä monipuolisesti kuin lukuja. Pythonissa lähes kaikkea voi vertailla kahdella seuraavalla tavalla, joista tulee aina tulokseksi joko ```True``` eli totta tai ```False``` eli epätotta.

| asia1 == asia2 |  ovatko asiat samat|
| asia1 != asia2  |  ovatko asiat eri|

Ehtoja voi myös yhdistellä komennoilla ```and``` ja ```or```. _And_ on englantia ja tarkoittaa _ja_. _Or_ on englantia ja tarkoittaa _tai_.


### Esimerkkejä

| koodi | mitä tekee |
| ----- | ---------- |
| 1 > 2 | vertaa ovatko 1 isompi kuin 2 ja saa arvon ```False``` |
| "lapio" == "lapio" | vertaa ovatko merkkijonot samat ja saa arvon ```True```|
|muuttuja == "sana"| vertaa onko muuttujaan tallennettu arvo sama kuin merkkijono _sana_|
|x > 2 and x < 5| vertaa onko muuttujan _x_ arv suurempi kuin 2 ja pienempi kuin 5|
|sana == "aa" or sana == "bb" | tarkistaa onko muuttujan _sana_ sarvo joko "aa" tai "bb"|

**Esimerkkejä Pythonissa**

```Python3
muuttuja1 = 13
muuttuja2 = 5
sana = "moikka"

muuttuja1 == muuttuja2      # tulostaa False
muuttuja1 > muuttuja2       # tulostaa True
muuttuja1 == 13             # tulostaa True
sana != "hei"               # tulostaa True
muuttuja2 == 5 and sana == "moi"    # tulostaa False
```

## Tehtävät

1. Tee ohjelma, joka kysyy käyttäjältä kaksi erillistä muuttujaa _luku_ ja _toinen_luku_. Muuta luvut kokonaisluvuiksi käyttäen ```int()``` komentoa.

1. Tee ohjelma, joka tarkistaa edellisen tehtävän muuttujilta seuraavat asiat:

    - Ovatko luvut yhtä suuret.

    - Onko onko ensimmänen luvuista suurempi kuin toinen.

    - Onko ensimmäinen luku pienempää tai yhtä suuri kuin toinen luku.

    - Onko toinen luku suurempaa kuin ensimmäinen, jos se kerrotaan kahdella.
