Tämä kuuluu kurssiin Configuration Management Systems - Palvelinten Hallinta ict4tn022-3018 - syksy 2022 https://terokarvinen.com/2022/palvelinten-hallinta-2022p2/

<i>Aloitettu 27.10.2022</i>

<h2>Esivalmistelut ennen käyttöönottoa</h2>

<p>Tarkista koneen tekniset tiedot, että prosessori on Linuxia tukeva ja muisti riittää. Linuxissa on sellaisia versioita, joita pystyy pienillä muistimäärillä pyörittämään. Jos asennus tapahtuisi pääkäyttöjärjestelmäksi pystyisi jättämään asennuksista jotain osioita pois. Halusin käyttää Windows 11 koneella rinnakkain virtuaalista Linuxia. CPU-Z:llä katsoin tarkemmat koneeni spekseistä, jotta varmasti koneeni olisi yhteensopiva valmitsemani Linux-sovelluksen kanssa.</p>
<img src="CPU-Z01.PNG"><img src="CPU-Z02.PNG">
Virtualbox tuli asentaa, jotta pystyisin käyttämään Linuxia ns. aidossa ympäristössä. VirtualBoxin löytää täältä ladattavaksi https://www.virtualbox.org/ Sivuilla kerrotaan sopivan eri Windowsseille, mutta Windows 11 ei ollut mainintaa. Heti etusivuilta löytyy nappi, josta pääsee lataussivuille. Kirjoittaessani tätä raporttia VirtualBox 7.0.2 oli uusin. Jokaiselle käyttöjärjestelmälle on oma tiedostonsa ja klikkaamalla Windows hosts linkkiä ponnahtaa ikkuna, jolla saa tiedoston tallennettua koneelle. Latauksen jälkeen etsin tiedoston ja klikkasin sitä kahteen kertaan, jolloin asentaminen alkaa.

## Asennus

Olin Johdanto ICT-infrastruktuuriin ja pilvipalveluihin - ICI001IT1A-3022 -kurssilla, jonka materiaaleista löytyy ohje "Ubuntun asentaminen VirtualBox:n avulla". Ohje on suomen kielinen. Koska virtuaalisen Linuxin asentaminen jäi kiireen vuoksi tekemättä oli se nyt edessä. Asennus alkoi hyvissä merkeissä, kuten seuraavista kuvista huomataan. Kunnes sarjan viimeisessä kuvassa näkyy virheilmoitus: Kernel panic.
