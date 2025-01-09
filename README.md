# Projekt-Python

Projekt iz kolegija Strojno učenje i inteligentni sustavi. 

Prva faza projekta podrazumijeva sljedeće: Faza 1: Razumijevanje domene, razumijevanje podataka i deskriptivno modeliranje
1. Razumijevanje domene (istraživanje poslovanja/pregled literature):
▪ Odaberite 3-5 relevantna znanstvena ili stručna članka na temu vašeg skupa
podataka koristeći izvore poput ScienceDirect i Google Scholar.
▪ Usredotočite se na analizu sličnih podataka u prethodnim istraživanjima i
zabilježite:
▪ Koji su se podaci koristili u prethodnim istraživanjima na ovu temu?
▪ Koje metode strojnog učenja su primijenjene?
▪ Koje su evaluacijske metrike korištene i rezultati dobiveni u tim
istraživanjima?
▪ Kakva je kvaliteta razvijenih modela i/ili inteligentnih sustava i koje
smjernice autori preporučuju za buduća istraživanja?
2. Razumijevanje podataka:
o Opis skupa podataka:
▪ Opišite skup podataka koji ćete koristiti, uključujući informacije o tipovima
varijabli (npr. numerička, kategorijska) te osnovni opis varijabli.
o Prikaz deskriptivnih statistika i distribucija varijabli
▪ Napravite deskriptivnu statistiku za svaki tip varijable: za numeričke varijable
uključite srednju vrijednost, medijan, standardnu devijaciju, donji i gornji kvartil
te minimum i maksimum, a za kategorijske varijable mod i frekvenciju
pojavljivanja.
▪ Grafički prikažite prikladnim grafičkim dijagramima distribuciju varijabli.
o Analiza odnosa među varijablama
▪ Prikažite i opišite matricom korelacije i/ili dijagramom raspršenja (engl. scatter
plot) odnos između numeričkih varijabli.
o Provjera kvalitete podataka
▪ Provjerite i zabilježite prisutnost nedostajućih vrijednosti, dupliciranih zapisa i
ekstremnih vrijednosti (engl. outliers) te navedite kako ćete s njima postupiti u
pripremi podataka.
3. Deskriptivno modeliranje (klasteriranje):
o Priprema podataka:
▪ Uklonite duplicirane zapise, nepotrebne stupce (npr. ID) i odaberite
relevantne varijable za analizu.
▪ Provedite imputaciju nedostajućih vrijednosti.
▪ Pripremite podatke za klasteriranje (npr. skaliranje numeričkih varijabli)
o Klasteriranje
▪ Primijenite algoritam klasteriranja (npr. K-means) na skupu podataka te
optimizirajte hiperparametre.
o Evaluacija klastera
▪ Procijenite kvalitetu klastera pomoću mjera kao što je Silhouette Score.
▪ Prikažite rezultate klasteriranja pomoću vizualizacija (npr. 2D ili 3D prikazi
klastera).
▪ Interpretirajte dobivene klastere, identificirajući obrasce ili grupe unutar
podataka te njihove ključne karakteristike.
4. Odabir ciljanih varijabli:
o Na temelju razumijevanja domene i rezultata klasteriranja odaberite ciljne varijable za
prediktivno modeliranje:
▪ Jednu za regresijski model: kontinuirana varijabla.
▪ Jednu za klasifikacijski model: binarna ili kategorijska varijabla.
2
Napomena: Ako nema varijable za klasifikacijski model, neka se varijabla koja
se koristila za regresijski model, transformira na smislen način tako da se
može koristiti za klasifikacijski model.

Skup podatak korišten za izradu projekta preuzet je s https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset

Skup podataka „Online Shoppers Purchasing Intention Dataset“ sadrži informacije o
ponašanju posjetitelja online trgovine tijekom njihovih sesija. Cilj ovog skupa podataka je
predviđanje hoće li posjetitelj završiti s kupnjom (varijabla Revenue). Varijable obuhvaćaju
različite informacije o stranicama koje su posjetitelji pregledavali, duljinu sesije, izvore prometa
i druge čimbenike koji mogu utjecati na namjeru kupnje. Popis i opis svih varijabli u skupu
podataka je prikazan u tablici ispod.
