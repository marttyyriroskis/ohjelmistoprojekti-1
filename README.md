# README

## Scrum-syklin yleiskuvaus

Scrum on ketterä projektinhallintamenetelmä, joka keskittyy ohjelmistokehitykseen ja tuotehallintaan. Se perustuu iteratiiviseen ja inkrementaaliseen lähestymistapaan, jossa työtä tehdään lyhyissä jaksoissa, joita kutsutaan sprinteiksi.

Scrum-sykli toistuu, kunnes tuote on valmis tai projektin päämäärä on saavutettu. Jokaisen sprintin jälkeen tuote on entistä valmiimpi ja sisältää lisää toiminnallisuuksia. Tämän iteratiivisen lähestymistavan ansiosta tuote kehittyy jatkuvasti, ja tiimi voi mukautua uusiin vaatimuksiin ja muutoksiin nopeasti.

## Sprintit

Sprint Planning (Sprintin suunnittelu):
Kuvaus: Sprint Planning on sprintin alussa pidettävä kokous, jossa koko Scrum-tiimi määrittelee, mitä töitä tullaan tekemään seuraavan sprintin aikana. Tavoitteena on valita Product Backlogista ne tehtävät, jotka ovat tärkeitä ja realistisesti saavutettavissa sprintin aikana.
Tulokset: Sprintin tavoite (Sprint Goal) ja Sprint Backlog, joka on lista tehtävistä, joita tiimi aikoo toteuttaa sprintin aikana.

Sprint:
Kuvaus: Sprint on ennalta määritelty ajanjakso (yleensä 1–4 viikkoa), jonka aikana tiimi työskentelee Sprint Backlogin tehtävien parissa. Sprintin aikana tiimi keskittyy vain valittuihin tehtäviin ilman ulkopuolisia häiriöitä.
Sprintin säännöt:
Sprintin kesto on vakio, eikä sitä muuteta kesken projektin.
Sprintin aikana ei tehdä uusia lisäyksiä tai muutoksia Sprint Backlogiin ilman erityistä syytä.

Sprint Review (Sprintin katselmointi):
Kuvaus: Sprintin lopussa pidettävä kokous, jossa tiimi esittelee valmiin työnsä (esim. toiminnallisia ominaisuuksia tai muita valmiita tehtäviä) sidosryhmille ja Product Ownerille.
Tavoite: Saada palautetta tuotteen nykytilasta ja mahdollisista parannuksista tai muutoksista. Päivittää Product Backlog tarvittaessa perustuen saatuun palautteeseen.

Sprint Retrospective (Sprintin retrospektiivi):
Kuvaus: Sprint Review -kokouksen jälkeen pidettävä kokous, jossa Scrum-tiimi arvioi sprintin suoritusta ja tunnistaa parannuskohteita.
Tavoite: Parantaa tiimin työskentelytapoja ja prosesseja tulevia sprinttejä varten, esimerkiksi lisäämällä tehokkuutta, vähentämällä jännitteitä tai optimoimalla työnkulkua.

Uusi Sprint:
Kuvaus: Sprint Retrospective -kokouksen jälkeen alkaa uusi sprintti, ja sykli alkaa alusta Sprint Planning -kokouksella.

## Työjonot

Product Backlog (Tuotteen tehtävälista):
Kuvaus: Product Backlog on priorisoitu lista kaikista tehtävistä, ominaisuuksista, parannuksista ja korjauksista, jotka tarvitaan tuotteen kehittämiseen.
Omistaja: Product Owner (tuoteomistaja) vastaa Product Backlogin ylläpidosta ja priorisoinnista.

## Roolit

### Product Owner (Tuoteomistaja)

    Vastaa tuotteen kehityksen suunnasta ja Product Backlogin ylläpidosta, priorisoi tehtävät ja varmistaa, että tiimi työskentelee liiketoiminnan kannalta tärkeimpien asioiden parissa.

### Scrum Master

    Facilitoi Scrum-prosessia ja varmistaa, että tiimi noudattaa Scrum-viitekehystä. Poistaa esteitä tiimin työskentelyn tieltä ja auttaa tiimiä parantamaan prosesseja.

### Development Team (Kehitystiimi)

    Monialainen, itseohjautuva tiimi, joka vastaa tuotteen toteutuksesta ja toiminnallisuuksien kehittämisestä sprinttien aikana.

### Sidosryhmät

    Antavat palautetta ja asettavat vaatimuksia tuotteen kehitykselle.

## Kokoukset

Scrum-sykliin kuuluu olennaisesta päivittäiset scrum-kokoukset (daily scrum). Päivittäiset scrum-kokoukset ovat lyhyitä 15 minuutin mittaisia kokouksia scrumiin osallistuville kehittäjille, ja kokouksen aikana tarkastellaan sprintin tavoitteen (sprint goal) saavuttamista sekä springin työjonoa (backlog). Kokous tulisi pitää päivittäin samaan aikaan.

Kokouksen toteutustapa on vapaa, mutta sen tulee edistää sprintin tavoitteen toteutumista. Kokouksen jälkeen jokaisella kehittäjällä on työsuunnitelma seuraavaksi työpäiväksi. Kehittäjät ovat myös tietoisia toistensa työtilanteesta ja seuraavista askelista.

On huomioitavaa, että scrum-kokous ei ole ainoa hetki päivässä, jolloin kehittäjät tapaavat toisiaan. Kommunikaation ylläpitäminen on tärkeää koko työpäivän ajan, ja muutoksia suunnitelmiin voi joutua tekemään varsinaisen scrum-kokouksen ulkopuolella.

## Miksi Scrum toimii?

Scrum toimii, koska se luo systemaattisen prosessin, jossa yhteistyön tuotoksia tarkastellaan riittävän usein, jotta virheet ja epäjohdonmukaisuudet eivät kulkeudu liian pitkälle.

Harjoitellaan tunnilla Git-versionhallintaa harjoituksella, johon kaikki osallistuvat.

Ohje laaditaan yhdessä Markdown-dokumenttina git-repositoryyn. Kuka tahansa saa muuttaa mitä tahansa! Harjoituksen lopuksi julkaistaan ohjeen ensimmäinen versio GitHub Pages -palvelussa.

Noudatetaan seuraavaa käytäntöä:

    Kaikki muutokset kehitetään omassa feature-haarassa.
    Valmiit muutokset viedään develop-haaraan –-no-ff -laajentimella (merge -–no-ff), jolloin aina tehdään merge-commit, vaikka fast-forward olisi mahdollinen. Näin kaikki merget tulevat näkyviksi historiassa.
    Master-haaraan viedään vain dokumentin valmiita versioita (julkaisu). Dokumentti kehitetään develop-haarassa valmiiksi julkaisua varten.
    Jokainen tiimin jäsen tekee muutoksia, muutoin ei saa harjoitusta. Mitä enemmän tehdään muutoksia, sitä enemmän tulee kokemusta!

Harjoitus aloitetaan lähitunnilla, jotta muutoksia tulee yhtaikaa ja saadaan aikaan konflikteja. Työ viimeistellään seuraavaan kertaan mennessä.

# Ohjeita

    Perustakaa hankkeelle projekti-repository GitHubiin ja kutsukaa ryhmän jäsenet projektiin.
    Haaran luonti ja vaihto: git switch –c feat123
    Feature-haaran yhdistäminen:
        Tee talletus (commit) feature haaraan
        Siirry develop haaraan: git switch develop
        Yhdistä: git merge -–no-ff feat123
