# Palvelinten hallinta - h3

## a) Tee tämän tehtävän raportti MarkDownina. Helpointa on tehdä raportti GitHub-varastoon, jolloin md-päätteiset tiedostot muotoillaan automaattisesti. Tyhjä rivi tekee kappalejaon, risuaita '#' tekee otsikon, sisennys merkitsee koodinpätkän.

Aloitin asentamalla koneelle gitin komennoilla

> sudo apt-get update

> sudo apt-get install -y git

Ja laitettuani asennuksen päällä siirryin selaimella githubiin ja tein uuden repositorion nimeltä "H3".
Kloonasin repositorion komennolla

> git clone https://github.com/toivanenotto/H3.git

Siirryin kloonaamaani H3-kansioon ja aloin kirjoittamaan tätä raporttia MarkDownina.

## d) Näytä omalla git-varastollasi esimerkit komennoista 'git log', 'git diff' ja 'git blame'. Selitä tulokset.

Aloitin komennolla

> git log

![001](/H3images/001.png)

Komento näyttää repositorion muutokset, niiden tekijät ja tarkan kellonajan.

> git diff

![002](/H3images/002.png)

Komento näyttää erot kahden eri version välillä.

> git blame

![003](/H3images/003.png)

Komento näyttää tiedostojen rivien muokkausajat ja tekijän.

## e) Tee tyhmä muutos gittiin, älä tee commit:tia. Tuhoa huonot muutokset 'git reset --hard'. Huomaa, että tässä toiminnossa ei ole peruutusnappia.

Lisäsin tähän raporttiin pätkän tekstiä

![004](/H3images/004.png)

Ja sitten tein tehtävänannossa mainitus komennon

> git reset --hard

![005](H3images/005.png)

Jolloin palautui viimeisin versio jolle oltiin tehty commit.

## f) Tee uusi salt-moduli. Voit asentaa ja konfiguroida minkä vain uuden ohjelman: demonin, työpöytäohjelman tai komentokehoitteesta toimivan ohjelman. Käytä tarvittaessa 'find -printf "%T+ %p\n"|sort' löytääksesi uudet asetustiedostot. (Tietysti eri ohjelma kuin aiemmissa tehtävissä, tarkoitushan on harjoitella Salttia)


