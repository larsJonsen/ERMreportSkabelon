ERMreportSkabelon
=================

Templates for the ermreport class and lyx layout

## Skabeleonen

filer:

```
master.lyx
kapitel01.lyx
note.lyx
```

```master.lyx``` er hoveddokument der ikke skal indeholde brødtekst men blot henvise til andre filer. Der er en henvisning i dokumentet og det er til ```kapitel01.lyx```.

```kapitel01.lyx``` er et underdokument og det er her brødtekst skal være i. I får brug for mere end et kapitel, så når der er brug for mere kopierer i ```kapitel01.lyx```under et nyt navn. Det er nok fornuftigt at navngive efter indhold som ```indledning.lyx, metode.lyx, diskussion.lyx, ...``` så der kan indsættes nye kapitler uden at de gamle skal omdøbes.

Der er behov for at man helle tiden tager noter og skriver ned, og arbejder med noter der bearbejdes til arbejdspapire der tilsidst indgår med dele i den færdige rapport. Hvis man skriver noter og arbejdspapire i standard opsætning af klassen får man forside, tro og love osv med hver gang man udskriver pdf. Derfor har klasen en option der heder ```note```. Den er slået til i ```note.lyx```. Her kan man skrive i sammen klasse men når det konverteres til pdf bliver det sat som en almindelig artikel med overskrift navn og forfatter.

## Figure

Det er hensigtsmæssigt at holde bunden af mappe systemt ren, så det kun indeholder ```*.lyx``` filer. Derfor er der en undermappe ```fig``` som er bergnet til grafik. Hvis tabeller bliver lavet som selvstændige filer bør de også opbevares i egne mappe osv.

## Litteratur Database 

den hedder i ERMreportSkabelon
```
litteratur.bib 
```
