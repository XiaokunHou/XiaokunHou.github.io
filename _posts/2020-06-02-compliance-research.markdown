---
layout: post
comments: true
hero_height: is-small
title:  "Coronavirus: le basi psicologiche della conformità alle norme di distanziamento sociali"
date:   2020-06-02
categories: coronavirus
description: "Uno studio empirico negli Stati Uniti, Italia e Corea del Sud"
image: 'https://gatravaglino.github.io/img/corona/flat.jpg'
published: true
canonical_url: https://gatravaglino.github.io/coronavirus/2020-06-02-compliance-research.markdown.html
---

Il nuovo coronavirus COVID-19 imperversa nel mondo, e interi Paesi hanno implementato *lockdowns* e norme di distanziamento sociale. Il rispetto di queste norme è estremamente importante, anche - forse soprattutto - ora che il numero di nuovi contagi sta calando. 

Il distanziamento rimane una delle poche strategie a nostra disposizione per maneggiare la convivenza con un virus di cui conosciamo ancora poco. 

Ma quali sono i valori e le credenze che spiegano una maggiore aderenza alle norme di distanziamento?

### La fiducia nel governo e l'aderenza alle norme

Per esaminare questa questione, con il mio collega Chanki Moon, abbiamo recentemente condotto uno studio volto ad indagare le basi psicologiche della conformità alle norme di distanziamente sociale. Lo studio (al momento, in *peer review*) ha coinvolto circa 1800 persone da Stati Uniti, Italia e Corea del Sud, e prende in esame molti costrutti diversi (tra cui anche le response emotive di vergogna e colpa, di cui parleremo in futuro). Una bozza completa dell'articolo è possibile leggerla (in inglese) [qui](https://psyarxiv.com/8yn5b/).

In questo post, intendo parlare degli effetti della **fiducia** nell'azioni governative - a parer mio una delle variabili più interessanti tra quelle incluse nello studio. 

La fiducia nelle azioni governative rappresenta la percezione che il governo stia agendo in maniera competente e onesta. La ricerca indica che questa variabile ha un ruolo molto importante perché, come dimostrato in molti contesti diversi, dalle emergenze sanitarie a quelle terroristiche, il grado di fiducia nel governo è solitamente associato ad un maggiore rispetto delle regole. 

### Lo studio empirico
Nel nostro studio, abbiamo chiesto ai partecipanti quanto loro si fidano delle azioni prese dal governo nei confronti del coronavirus (*1 = per nulla, 7 = completamente*). Il grafico sottostante mostra le medie delle risposte divise per Paese:

<p align="center">
  <img src="/img/res/trust.png" width="400" />
</p>

Le persone riportano una fiducia abbastanza alta in Italia (*M =* 5.32) e Corea del Sud (*M =* 5.27). La fiducia è minore negli Stati Uniti (*M =* 3.43). Per chi ha seguito la risposta al coronavirusdell'amministrazione federale statunitense, questo risultato non dovrebbe risultare sorprendente. 

Ai partecipanti è stato anche chiesto la loro aderenza alle norme di distanziamento sociale utilizzando sei items diversi (ad esempio, l'aderenza alle richieste di uscire il meno possibile, di lavarsi le mani spesso etc.). Di questi sei items (misurati su una scala da 1 a 7) è stata fatta la media che rappresenta, quindi, un punteggio complessivo di aderenza alle norme. I risultati, divisi per Paese, sono rappresentati nel grafico sottostante:[^1] 

<p align="center">
  <img src="/img/res/compliance.png" width="400" />
</p>

I livelli di aderenza alle norme sono molto alti in Italia (*M =* 6.39) e Stati Uniti (*M =* 6.27), ancor più che in Corea (*M =* 5.68). Questo probabilmente riflette la situazione oggettiva nei diversi Paesi, nei quali - al momento di raccolta dati, in Aprile - le restrizioni imposte e le strategie di contenimento del coronavirus erano diverse.

### L'associazione tra fiducia e aderenza alle norme

Abbiamo poi testato se esistesse un'associazione tra le due misure di fiducia e aderenza alle norme. Come ipotizzato, i dati mostrano l'esistenza di un'associazione positiva tra le due variabili. Le persone che hanno maggiore fiducia nel governo, dichiarano anche un grado di aderenza maggiore alle norme di distanziamento sociale. Con un'importante eccezione, come il grafico sottostante mostra. 

<p align="center">
  <img src="/img/res/regr.png" width="400" />
</p>

Il grafico mostra sull'asse delle ordinate la fiducia, su quello delle ascisse l'aderenza alle norme, e la relazione lineare tra le due variabili in ogni Paese. Mentre la relazione tra le variabili è positiva sia in Italia che in Corea del Sud (all'aumentare del punteggio di una variabile, aumenta anche il punteggio dell'altra), la relazione negli Stati Uniti è piatta, praticamente indistinguibile (da un punto di vista statistico) dallo zero.[^2]

### Le basi della fiducia

L'ultimo punto riguarda i valori socio-culturali che predicono la  fiducia nel governo nei diversi paesi. Per esplorare questa questione, in questo studio, abbiamo misurato l'approvazione di una combinazione di valori riguardanti sia eguaglianza-diseguaglianza (orizzontalità-verticalità) sia independenza-interdipendenza (individualismo-collettivismo). I risultati hanno mostrato che, mentre in Italia e in Corea i valori di orizzontalità e interdipendenza sono associati ad una maggiore fiducia nelle azioni del governo, negli **Stati Uniti** sono i valodi di verticalità e interdipendenza che sono associati alla fiducia. 

In altre parole, la percezione della fiducia nel governo è guidata da sentimenti di connessione agli altri e eguaglianza in Italia e Corea, mentre è guidata dall'approvazione delle diseguaglianze tra gruppi negli Stati Uniti. 

### Per concludere

Le associazioni tra valori culturali, fiducia nel governo e aderenza alle norme sociali mostrano un pattern abbastanza chiaro. Da questi risultati - dati i metodi utilizzati - non possiamo trarre conclusioni di causa-effetto. Possiamo tuttavia affermare che, ove la fiducia è radicata in solidarietà con gli altri, essa predice una maggiore aderenza a norme che - oltre a proteggere la propria persona - proteggono anche il prossimo. Ove invece questa fiducia è legata alla prevaricazione e l'approvazione di relazioni gerarchiche tra i gruppi, essa non si associa in maniera statisticamente significativa con le norme di distanziamento sociale.



[^1] Le medie presentate nello studio originale sono lievemente diverse da quelle rappresentate qui perché nello studio stimiamo variabili latenti che hanno maggiore precisione. L'interpretazione dei risultati è identica.
[^2] Le bande intorno alle linee rappresentano gli intervalli di confidenza delle nostre stime. Intervalli più stretti indicano un dato più 'preciso'.

***
- Img: Photo by [United Nations COVID-19 Response](https://unsplash.com/@unitednations) on [Unsplash](https://unsplash.com)
- Grafici e analisi statistiche prodotti con R and ggplot2
