
# Lekker!

Alles staat in Dropbox, onder `lekker.million.nl`.

**Afbeeldingen** komen allemaal in `site/files/`, en dan afhankelijk van type nog de `eten`, `drinken`, of `uit-eten` subfolder.

**Content** (recepten en restaurants en zo) komen in `site/`, en dan afhankelijk van type nog de `eten`, `drinken`, of `uit-eten` subfolder.
Voor elk type content staat er in de bijbehorende folder ook een basis-formaat, bv. `_eten-format.md`. Maak hier een kopie van en pas de naam aan, en daarna de inhoud.

We gebruiken 1Writer op iPad en iPhone voor het bewerken van de content.

De laatste versie van de site is intern te vinden op
[http://lekker.mac.million.local:10002](http://lekker.mac.million.local:10002). De live versie is te vinden op [http://lekker.million.nl](http://lekker.million.nl).

---

## Content types & markdown formats (zie ook `lekker.million.nl/site/` folder):

### eten

    ---
    type: eten

    title: Titel met hoofdletters
    slug: titel-zonder-hoofdletters-en-met-afbreekstreepjes
    date: "2018-02-20"
    description: Korte omschrijving
    image: /files/eten/titel-zonder-hoofdletters-en-met-afbreekstreepjes.jpg

    soort: vlees/vis/vega/vegan/salade/soep
    gang: lunch/voor/hoofd/bij/na
    temperatuur: warm/lauw/koud
    bereidingstijd: korte tekst, bv 45 min, 40 min oven
    keuken: italiaans/frans/spaans/afrikaans/indiaas/portugees/...
    waardering: +/++/+++
    ingredienten:
    - de
    - belangrijkste
    - ingrediënten
    - op een rijtje
    - altijd als enkelvoud

    ---

    Een intro-verhaaltje wat wij ervan vinden?

    ## Ingrediënten

    *voor X personen*

    * 1 ui
    * 400 gr. pastinaak in stukken
    * 1 el muntblaadjes,in fijne reepjes
    * ...

    #### Eventueel tussenkopje voor extra ingrediënten

    * extra
    * ingrediënten
    * ...

    ## Bereiding

    Verhaaltje

    #### Opmerkingen

    Bv in plaats van pastinaak kun je ook doperwtjes gebruiken

    #### Bron

    [Naam van de bron](http://www.website.com/link-naar-de-bron)


### drinken

    ---
    type: drinken

    title: Titel met Hoofdletters
    slug: titel-zonder-hoofdletters-en-met-afbreekstreepjes
    date: "2018-02-20"
    description: Korte omschrijving
    image: /files/drinken/titel-zonder-hoofdletters-en-met-afbreekstreepjes.jpg

    soort: rood/wit/bubbels/bier/grappa/cocktail/overig
    herkomst: italiaans/frans/spaans/afrikaans/...
    prijs: €/€€/€€€
    waardering: +/++/+++

    ---

    **Vet-gedrukt intro**

    Verhaaltje


### uit-eten

    ---
    type: uit-eten

    title: Titel met Hoofdletters
    slug: titel-zonder-hoofdletters-en-met-afbreekstreepjes
    date: "2018-02-20"
    description: Korte omschrijving
    image: /files/uit-eten/titel-zonder-hoofdletters-en-met-afbreekstreepjes.jpg

    plaats: delft/antwerpen/rome/haarlem/rotterdam/den haag/amsterdam/utrecht/...
    keuken: italiaans/frans/spaans/afrikaans/portugees/...
    prijs: €/€€/€€€
    waardering: +/++/+++

    ---

    **Vet-gedrukt intro**

    Verhaaltje

---

