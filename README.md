# Git-versionhallinta

**Kurssin toteutus:** [SOF013AS2A-3001/Git-versionhallinta]

**Tekijä:** Liisa Davydov

## Repositorion sisältö

## Harjoitus 2
### Perustoiminnot
- Perustetaan Git-repositorio.
- Tehdään repositorioon tiedosto (esim. test.txt) ja kirjoita tiedostoon jotain. Talleta tiedosto Git-hallintaan.
- Tehdään repositorioon tiedosto hello.html.
- Viedään nämä muutokset Git-hallintaan.
- Lisätään tekstiin h1-merkkaus, jolloin siitä tulee HTML-elementti:
```<h1>Hei maailma!</h1>```
- Viedään muutos versionhallintaan.
- Muutetaan hello.html-tiedoston nimeksi index.html ja tallennetaan muutos.
- Poistetaan text.txt versionhallinnasta ja tallennetaan muutos. 
- Lisätään vielä tiedostoja ja talletaan ne versionhallintaan.
- Tarkastele tekemiäsi talletuksia komennolla git log. Kokeile myös komentoa laajentimella --stat. Mitä lisätietoa saat?

```
commit 00da2819e8f642a322e3ab4400e9f2d4a18e8918 (HEAD -> main)
Author: Liisa Davydov <liisamuttonen@gmail.com>
Date:   Wed Oct 15 15:03:01 2025 +0300

    lisää muita tiedostoja

commit a723756f9ff4da1f2b1b8c64c6a695397cd49806
Author: Liisa Davydov <liisamuttonen@gmail.com>
Date:   Wed Oct 15 15:02:25 2025 +0300

    poista test

commit d00dd3b2885e96126fae9fc1a6a7ff85bbfeebeb
Author: Liisa Davydov <liisamuttonen@gmail.com>
Date:   Wed Oct 15 15:01:40 2025 +0300

    nimeä uudelleen html

commit f319d8b6d5d280d453c2579262c2479dd5f1bb86
Author: Liisa Davydov <liisamuttonen@gmail.com>
Date:   Wed Oct 15 14:56:15 2025 +0300

    html lisää

commit 044109e407491c9e77e1001ff843eb44e4f5b78b (origin/main)
Author: Liisa Davydov <liisamuttonen@gmail.com>
Date:   Wed Oct 15 14:47:20 2025 +0300

:
commit 00da2819e8f642a322e3ab4400e9f2d4a18e8918 (HEAD -> main)
Author: Liisa Davydov <liisamuttonen@gmail.com>
Date:   Wed Oct 15 15:03:01 2025 +0300

    lisää muita tiedostoja

commit a723756f9ff4da1f2b1b8c64c6a695397cd49806
Author: Liisa Davydov <liisamuttonen@gmail.com>
Date:   Wed Oct 15 15:02:25 2025 +0300

    poista test

commit d00dd3b2885e96126fae9fc1a6a7ff85bbfeebeb
Author: Liisa Davydov <liisamuttonen@gmail.com>
Date:   Wed Oct 15 15:01:40 2025 +0300

    nimeä uudelleen html

commit f319d8b6d5d280d453c2579262c2479dd5f1bb86
Author: Liisa Davydov <liisamuttonen@gmail.com>
Date:   Wed Oct 15 14:56:15 2025 +0300

    html lisää

commit 044109e407491c9e77e1001ff843eb44e4f5b78b (origin/main)
Author: Liisa Davydov <liisamuttonen@gmail.com>
Date:   Wed Oct 15 14:47:20 2025 +0300

:
commit 00da2819e8f642a322e3ab4400e9f2d4a18e8918 (HEAD -> main)
Author: Liisa Davydov <liisamuttonen@gmail.com>
Date:   Wed Oct 15 15:03:01 2025 +0300

    lisää muita tiedostoja

commit a723756f9ff4da1f2b1b8c64c6a695397cd49806
Author: Liisa Davydov <liisamuttonen@gmail.com>
Date:   Wed Oct 15 15:02:25 2025 +0300

    poista test

commit d00dd3b2885e96126fae9fc1a6a7ff85bbfeebeb
Author: Liisa Davydov <liisamuttonen@gmail.com>
Date:   Wed Oct 15 15:01:40 2025 +0300

    nimeä uudelleen html

commit f319d8b6d5d280d453c2579262c2479dd5f1bb86
Author: Liisa Davydov <liisamuttonen@gmail.com>
Date:   Wed Oct 15 14:56:15 2025 +0300

    html lisää

commit 044109e407491c9e77e1001ff843eb44e4f5b78b (origin/main)
Author: Liisa Davydov <liisamuttonen@gmail.com>
Date:   Wed Oct 15 14:47:20 2025 +0300

    tekstitiedosto
(END)
Author: Liisa Davydov <liisamuttonen@gmail.com>
Date:   Wed Oct 15 15:03:01 2025 +0300

    lisää muita tiedostoja

commit a723756f9ff4da1f2b1b8c64c6a695397cd49806
Author: Liisa Davydov <liisamuttonen@gmail.com>
Date:   Wed Oct 15 15:02:25 2025 +0300

    poista test

commit d00dd3b2885e96126fae9fc1a6a7ff85bbfeebeb
Author: Liisa Davydov <liisamuttonen@gmail.com>
Date:   Wed Oct 15 15:01:40 2025 +0300

    nimeä uudelleen html

commit f319d8b6d5d280d453c2579262c2479dd5f1bb86
Author: Liisa Davydov <liisamuttonen@gmail.com>
Date:   Wed Oct 15 14:56:15 2025 +0300

    html lisää

commit 044109e407491c9e77e1001ff843eb44e4f5b78b (origin/main)
Author: Liisa Davydov <liisamuttonen@gmail.com>
Date:   Wed Oct 15 14:47:20 2025 +0300

    tekstitiedosto
```

## Harjoitus 3
### Peruutus
- Tee repositorioosi useita muutoksia: muuta talletettuja tiedostoja ja lisää uusia tiedostoja. Älä talleta!
- Kokeile add-toiminnon peruuttamista.
- Lisää muutokset seuraavaan talletukseen (add).
- Poista muutoksia yksittäin seuraavasta talletuksesta.
- Poista kaikki loput muutokset seuraavasta talletuksesta.
- Sinulla pitäisi nyt olla työtilassa useita tallettamattomia muutoksia, joista mikään ei ole menossa seuraavaan talletukseen.
- Kokeile työtilaan tehtyjen muutosten peruuttamista. Tarkista tilanne joka välissä komennolla status.
- Peruuta jonkin talletetun tiedoston muutokset työtilasta.
- Poista kaikki loput muutokset työtilasta.
- Mitä tapahtui uusille untracked-tilassa oleville tiedostoille?
```Ne eivät muuttuneet eivätkä poistuneet komennolla git restore.```
- Kokeile talletuksen peruuttamista.
- Tee useita muutoksia ja talleta ne.
- Peruuta talletus komennolla revert.
```
harjoitus2 % --> git log --oneline

fad4cdf (HEAD -> main) Revert "muutos"
2afb1be muutos
00da281 (origin/main) lisää muita tiedostoja
a723756 poista test
d00dd3b nimeä uudelleen html
f319d8b html lisää
044109e tekstitiedosto
√ harjoitus2 % --> git checkout master
git status
```
        Mitä näyttää komento log?

## Harjoitus 4
### Ominaisuushaarojen (feature branch) käyttöä kehityksessä
- Lisätään siihen HTML-sivun perusrakenne index.html:
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hello</title>
</head>

<body>
  <main>
    <h1>Hei maailma!</h1>
  </main>

</body>

</html>

Talleta muutokset master-haaraan.

Lisätään tyylejä. Lisää projektiin tiedosto styles.css, jonka sisältö voi olla esim.

html {
  height: 100%;
}

body {
  background-color:linen;
  display: flex;
  flex-direction: column;
  justify-content: center;
  height: 100%;
}

main {
  text-align: center;
}
```
- Tyylit pitää vielä liittää hello.html-tiedostoon. Lisää sen head-osioon määritys
```
<link rel="stylesheet" href="styles.css">
```
- Testaa selaimessa, että sivun tyylit toimivat.
- Käytetään ominaisuushaaraa: Luo muutosta varten uusi haara esim. nimellä tyylit ja talleta tyylimuutokset sinne.
- Kokeile vaihtaa aktiivista haaraa haarojen master ja tyylit välillä ja lataa sivu selaimessa aina uudelleen. Miten sivu muuttuu?
```Näen valkoisen taustan ja otsikon “Hei maailma!” ilman keskitystä. ja tyyleissä styles.css käytössä```
- Yhdistä se master-haaraan.
- Kokeile nyt vaihtaa aktiivista haaraa haarojen master ja tyylit välillä ja lataa sivu selaimessa aina uudelleen. Miten sivu muuttuu?
```se on molemmissa sama```
