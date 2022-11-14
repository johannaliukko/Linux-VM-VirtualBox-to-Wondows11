# Linux VirtualBox installing to Windows11
Noticed when you install Linux VirtualBox to Windows 11

# Linux VirtualBoxin asentaminen Windows 11
## Huomioitavaa, kun asennat Windows 11 koneeseen VirtualBox

#### Tämä kuuluu kurssiin Configuration Management Systems - Palvelinten Hallinta ict4tn022-3018 - syksy 2022 https://terokarvinen.com/2022/palvelinten-hallinta-2022p2/

Aloitettu 27.10.2022

## Esivalmistelut ennen käyttöönottoa

Tarkista koneen tekniset tiedot, että prosessori on Linuxia tukeva ja muisti riittää. Linuxissa on sellaisia versioita, joita pystyy pienillä muistimäärillä pyörittämään. Jos asennus tapahtuisi pääkäyttöjärjestelmäksi pystyisi jättämään asennuksista jotain osioita pois. Halusin käyttää Windows 11 koneella rinnakkain virtuaalista Linuxia. 
CPU-Z:llä katsoin tarkemmat koneeni spekseistä, jotta varmasti koneeni olisi yhteensopiva valmitsemani Linux-sovelluksen kanssa.

<img src="CPU-Z01.PNG"><img src="CPU-Z02.PNG">

Virtualbox tuli asentaa, jotta pystyisin käyttämään Linuxia ns. aidossa ympäristössä. VirtualBoxin löytää täältä ladattavaksi https://www.virtualbox.org/ 
Sivuilla kerrotaan sopivan eri Windowsseille, mutta Windows 11 ei ollut mainintaa.
Heti etusivuilta löytyy nappi, josta pääsee lataussivuille. Kirjoittaessani tätä raporttia VirtualBox 7.0.2  oli uusin. Jokaiselle käyttöjärjestelmälle on oma tiedostonsa ja klikkaamalla Windows hosts linkkiä ponnahtaa ikkuna, jolla saa tiedoston tallennettua koneelle. Latauksen jälkeen etsin tiedoston ja klikkasin sitä kahteen kertaan, jolloin asentaminen alkaa.

## Asennus
Olin Johdanto ICT-infrastruktuuriin ja pilvipalveluihin - ICI001IT1A-3022 -kurssilla, jonka materiaaleista löytyy ohje "Ubuntun asentaminen VirtualBox:n avulla". Ohje on suomen kielinen. Koska virtuaalisen Linuxin asentaminen jäi kiireen vuoksi tekemättä oli se nyt edessä.




## Asennuksen ongelmat ja siihen ratkaisut

Odotettavissa on, että asennus näyttää onnistuvan siihen saakka, kunnes käynnistät VirtualBoxin. Virheilmoitus on luultavasti 'Kernel' panic, jonka näet alla.

<img src="alku8C.PNG">



