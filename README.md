# HoGent LaTeX-sjablonen

In deze repository vind je enkele sjablonen voor LaTeX documenten die de HoGent huisstijl (proberen te) volgen.

Momenteel zijn er drie beschikbaar:

* Een presentatie gebaseerd op de `beamer`-klasse
* Een sjabloon voor de bachelorproef toegepaste informatica (aanpasbaar voor andere bachelorproeven of scripties)
* Een examenopgave (wellicht enkel nuttig voor lectoren...)

## Aan de slag

Je kan de sjablonen zelf gebruiken, hetzij door de Git-repository te klonen

    git clone https://github.com/bertvv/hogent-latex-sjablonen

hetzij door alles in een zip-bestand te downloaden via de link in het infovak rechts onderaan.

Ik raad je ten zeerste aan om je LaTeX-documenten in een versiebeheersysteem te steken (bv. Git, Mercurial, Subversion, enz.).

LaTeX genereert een hele hoop hulpbestanden die eigenlijk niet in versiebeheer thuishoren. Je kan je versiebeheersysteem vragen bepaalde files te negeren, a.h.v. patronen. Bij Git, bijvoorbeeld, steek je die in een bestand `.gitignore` in de root van je project. Je kan een voorbeeld vinden in de source, op https://gist.github.com/bertvv/4460239 of https://github.com/github/gitignore. I het huidige project zit er al een `.gitignore`.

## Referenties

De template maakt gebruik van BibLatex en Biber. Ik raad aan om op Windows de **x86 versie van MiKTeX** te gebruiken en TeXstudio als "IDE" voor beginners. Je moet instellen om de .bib bestanden te compilen met **Biber**, in TeXstudio is dat als volgt: Options > Configure TeXStudio > Build > Default Bibliography > Biber.

## Vragen, bugs, verbeteringen

Heb je vragen over het gebruik van de sjablonen, kan je me contacteren. Bugs, vragen voor verbeteringen, enz. kan je registreren via de Issues. Je kan zelf ook patches doorsturen via Pull Requests.

## Credits

Bedankt aan diegenen die bijgedragen hebben aan het verbeteren van deze sjablonen:

* Jeroen Maelbrancke
* Matts Devriendt
* Niels Corneille
* [Patrick Van Brussel](https://github.com/VuokkoVuorinnen)
* [Simon Rondelez](https://github.com/simonrondelez)
