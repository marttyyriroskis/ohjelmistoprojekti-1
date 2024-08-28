# README

## Scrum-syklin yleiskuvaus

## Sprintit

## Työjonot

## Roolit

## Kokoukset

## Miksi Scrum toimii?

Scrum toimii, koska se luo systemaattisen prosessin, jossa yhteistyön tuotoksia tarkastellaan riittävän usein, jotta virheet ja epäjohdonmukaisuudet eivät kulkeudu liian pitkälle.

Harjoitellaan tunnilla Git-versionhallintaa harjoituksella, johon kaikki osallistuvat.

Ohje laaditaan yhdessä Markdown-dokumenttina git-repositoryyn. Kuka tahansa saa muuttaa mitä tahansa!  Harjoituksen lopuksi julkaistaan ohjeen ensimmäinen versio GitHub Pages -palvelussa.

Noudatetaan seuraavaa käytäntöä:

    Kaikki muutokset kehitetään omassa feature-haarassa.
    Valmiit muutokset viedään develop-haaraan –no-ff -laajentimella (merge –no-ff), jolloin aina tehdään merge-commit, vaikka fast-forward olisi mahdollinen. Näin kaikki merget tulevat näkyviksi historiassa.
    Master-haaraan viedään vain dokumentin valmiita versioita (julkaisu). Dokumentti kehitetään develop-haarassa valmiiksi julkaisua varten.
    Jokainen tiimin jäsen tekee muutoksia, muutoin ei saa harjoitusta. Mitä enemmän tehdään muutoksia, sitä enemmän tulee kokemusta!

Harjoitus aloitetaan lähitunnilla, jotta muutoksia tulee yhtaikaa ja saadaan aikaan konflikteja. Työ viimeistellään seuraavaan kertaan mennessä.

# Ohjeita

    Perustakaa hankkeelle projekti-repository GitHubiin ja kutsukaa ryhmän jäsenet projektiin.
    Haaran luonti ja vaihto: git switch –c feat123
    Feature-haaran yhdistäminen:
        Tee talletus (commit) feature haaraan
        Siirry develop haaraan: git switch develop
        Yhdistä: git merge –no-ff feat123
