---
layout: post
comments: true
hero_height: is-small
title:  "Coronavirus: Le basi psicologiche della conformità alle norme di distanziamento sociali"
date:   2020-06-02
categories: coronavirus
description: "I dati sul coronavirus in Italia, regione per regione"
image: 'https://gatravaglino.github.io/img/corona/flat.jpg'
published: false
canonical_url: https://gatravaglino.github.io/coronavirus/2020-06-02-compliance-research.markdown.html
---

Con il nuovo coronavirus COVID-19 che imperversa nel mondo, interi Paesi hanno implementato *lockdowns* e norme di distanziamento sociale. Il rispetto di queste norme è estremamente importante, anche - forse soprattutto - ora che il numero di nuovi contagi sta calando (almeno in Italia). 

Il distanziamento rimane una delle poche strategie a nostra disposizione per maneggiare la convivenza con un virus di cui conosciamo ancora poco. Ma quali sono i valori e le credenze che si associano ad una maggiore aderenza alle norme di distanziamento?

## La fiducia nel governo e l'aderenza alle norme

Per rispondere a questa questione, con il mio collega Chanki Moon, abbiamo recentemente condotto uno studio volto ad indagare le basi psicologiche della conformità alle norme di distanziamente sociale. Lo studio (al momento in *peer review*) ha coinvolto circa 1800 persone da Stati Uniti, Italia e Corea del Sud, e prende in esame molti costrutti diversi (tra cui anche le response emotive di vergogna e colpa). Una bozza completa dell'articolo è possibile trovarla [qui](https://psyarxiv.com/8yn5b/).

In questo post, intendo mostrare gli effetti della **fiducia** nell'azioni governative - a parer mio una delle variabili più interessanti tra quelle incluse nello studio. La fiducia nelle azioni governative indica quanto le persone ritengono che il governo stia agendo in maniera competente e onesta. La ricerca indica che questa variabile ha un ruolo molto importante perché, in molti contesti diversi, il grado di fiducia è solitamente associato alla volontà di rispettare le regole. 

Ai partecipanti allo studio è stato chiesto quanto loro si fidano dell'azione del loro governo nei confronti del coronavirus (*1 = per nulla, 7 = completamente*). Il grafico sottostante mostra le loro risposte:

<p align="center">
  <img src="/img/res/tm/trust.png" width="400" />
</p>

Quattro rappresenta il punto neutrale della scale. Le persone si fidano dell'azione governativa in Italia (*M =* 5.32) e Corea del Sud (*M =* 5.27). La fiducia è tuttavia minore negli Stati Uniti (*M =* 3.43). Per chi ha seguito la risposta dell'amministrazione federale statunitense al coronavirus, questo risultato non è sorprendente. 

Ai partecipanti è stato anche chiesto la loro aderenza a sei norme di distanziamento sociale (ad esempio, quanto loro evitano di uscire inutilmente, quanto spesso si lavano le mani etc). La media di queste sei misure (scala 1-7) rappresenta il punteggio di aderenza alle norme. Le medie divise per paese sono rappresentaste nel grafico sottostante.[^1] 

<p align="center">
  <img src="/img/res/tm/compliance.png" width="400" />
</p>

I livelli di aderenza alle norme sono molto alti, in Italia (*M =* 6.39) e Stati Uniti (*M =* 6.27), ancor più che in Corea (*M =* 5.68). Questo probabilmente riflette la situazione oggettiva nei diversi Paesi, nei quali - al momento di raccolta dati, in Aprile - le restrizioni imposte e le strategie di contenimento del coronavirus erano diverse.

## L'associazione tra fiducia e aderenza alle norme

Come ipotizzato, i dati mostrano che la fiducia è associata all'aderenza alle norme. Le persone che hanno maggiore fiducia nel governo, riportano anche un grado di aderenza maggiore alle norme di distanziamento sociale. Con un'importante eccezione, come il grafico sottostante mostra. 

Il grafico rappresenta sull'asse delle ordinate la fiducia e su quello delle ascisse l'aderenza alle norme. Mentre la relazione tra le due variabili è positiva in Italia e Corea (all'aumentare del punteggio di una variabile, aumenta anche il punteggio dell'altra), la linea è piatta negli Stati Uniti, indicando una relazione non distinguibile dallo zero.[^2]  


<p align="center">
  <img src="/img/res/tm/regr.png" width="400" />
</p>



[^1] Le medie presentate nello studio originale sono lievemente diverse da quelle rappresentate qui perché nello studio stimiamo variabili latenti che hanno maggiore precisione. L'interpretazione dei risultati è identica.
[^2] Le bande intorno alle linee rappresentano gli intervalli di confidenza delle nostre stime. Intervalli più stretti indicano un dato più 'preciso'.

***
- Img: Photo by [United Nations COVID-19 Response](https://unsplash.com/@unitednations) on [Unsplash](https://unsplash.com)
- Grafici e analisi statistiche prodotti con R and ggplot2
