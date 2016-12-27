# fudoshin-dojo.github.io

## Wat is github
Zie [howtogeek.com](http://www.howtogeek.com/180167/htg-explains-what-is-github-and-what-do-geeks-use-it-for/).

## Nieuw nieuwsbericht plaatsen
In de map `_posts` klik je op **Create new file**.
![nieuw](images/add-post.png)

Het nieuwe bestand moet opgemaakt worden als: `yyyy-mm-dd-example-post.md` en het moet steeds beginnen 
met volgende regels:
```
---
layout: post
title: Example Post
permalink: /nieuws/example-post
---
```
Hier kan je dan de titel van het nieuwsbericht opgeven en de link naar het bericht. 
De layout moet altijd `post` zijn.

De opmaak van een nieuw bericht is in [Markdown](https://guides.github.com/features/mastering-markdown/), 
dit is een simpele manier om snel teksten van een basisopmaak te voorzien.

Eens je tekst volledig is vul je onderaan de titel van de pagina in als beschrijving, en vul je in 
het tekstveld er onder een korte beschrijving van het bericht.  
Vervolgens zorg je dat "_Commit directly to the master branch_" aangevinkt staat en klik je op 
"_commit new file_".

Na een minuutje controleer je op het [nieuwsoverzicht](http://aikidogent.com/nieuws/overzicht) of het 
bericht correct toegevoegd werd.

## Bestaande teksten aanpassen
### nieuwsbericht
In de map `_posts` klik je op het bestand dat je wil aanpassen, waarna je rechts op een potloodje
kan klikken. Dit opent het bestand in een teksteditor waar je de inhoud kan wijzigen naar believen.

Eens je tekst volledig is vul je onderaan de titel van de pagina in als beschrijving, en vul je in 
het tekstveld er onder een korte beschrijving van het bericht.  
Vervolgens zorg je dat "_Commit directly to the master branch_" aangevinkt staat en klik je op 
"_commit changes_".

Na een minuutje controleer je op het [nieuwsoverzicht](http://aikidogent.com/nieuws/overzicht) of het 
bericht correct aangepast werd.

### webpagina
De pagina's zijn opgemaakt in HTML, maar je kan deze op dezelde manier maken en aanpassen als 
de nieuwsberichten. Het enige waar je op moet letten is dat de structuur van de pagina's behouden 
blijft, anders zou de pagina er best wel eens vreemd kunnen gaan uitzien.