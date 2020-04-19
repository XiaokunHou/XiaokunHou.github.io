---
layout: post
hero_height: is-small
title:  "Coronavirus: Andamento regionale in Italia"
date:   2020-04-19
categories: coronavirus
description: "I dati sul coronavirus in Italia, regione per regione"
image: 'https://gatravaglino.github.io/img/corona/cov.jpg'
published: true
canonical_url: https://gatravaglino.github.io/coronavirus/2020/04/19-andamento-coronavirus-regionale.markdown.html
---

In questi giorni si vedono numeri ovunque. Quando si parla di COVID19, si parla innanzitutto di numeri. Ed i numeri vengono usati per fare paragoni, stilare classifiche. È quindi necessario fare un po' di chiarezza. I numeri assoluti di casi sono veramente poco utili per fare paragoni fra regioni. Molto più utile è la prevalenza di casi in relazione al numero di abitanti (che varia molto, da regione in regione in Italia). 

## La situazione regione per regione

Ecco, ad esempio, il primo grafico che mostra la prevalenza di casi per 100.000 abitanti diviso per regioni. Sappiamo già della Lombardia. Ma quello colpisce sono la P.A. di Trento, la Valle d'Aosta, la P.A. di Bolzano e le Marche.

![Grafico 1](/img/corona/graph1.jpg)

Chiaramente, il numero di casi positivi è associato al numero di tamponi fatti. E nel secondo grafico possiamo vedere la prevalenza di tamponi ogni 100.000 abitanti. Il grafico ricalca bene il primo. Con qualche variazione: il Veneto è la regione con il maggior numero di tamponi ogni 100.000 persone. La Campania l'ultima.

![Grafico 2](/img/corona/graph2.jpg)

A costo di confermare l'ovvio, la associazione tra prevalenza di tamponi e prevalenza di casi è visibile a occhio nudo nel terzo grafico. Quello che sorprende un po' è il dato della Lombardia. La Lombardia ha molti più casi di quelli che uno si aspetterebbe dato il numero di tamponi. Per intenderci, se l'associazione tra prevalenza di casi e prevalenza di tamponi fosse perfetta, tutti i pallini dovrebbero posarsi sulla linea blu al centro. 

![Grafico 3](/img/corona/graph3.jpg)

Un certo grado di errore (sia sovrastima che sottostima) è da aspettarselo. Ma l'errore del dato della Lombardia (la distanza dalla retta centrale) è veramente ampio. Questo è  in linea con l'idea, espressa da molti, che i casi in Lombardia sono parecchi di più di quelli riportati. Guardate invece come il Veneto ha una minore prevalenza di casi rispetto quelli che ti aspetteresti dato il numero di tamponi.

## Il rapporto tra casi e tamponi

C'è un'ultima statistica da prendere in considerazione, forse la più interessante di tutte. Si tratta della proporzione di casi positivi riscontrati, in relazione al numero di tamponi fatti. Il dato non è affatto privo di difetti, perché i tamponi non sono fatti in maniera random nella popolazione. Tuttavia, ci permette di superare parzialmente il problema della grande differenza di tests che vengono fatti in ciascuna regione.

![Grafico 4](/img/corona/graph4.jpg)

Il quarto grafico riporta il numero di positivi ogni 100 tamponi. Sappiamo già della Lombardia. Ma povere Marche. E, soprattutto, osservate la Campania (dal grafico 2 che la Campania è la regione dove si fanno meno tamponi). Infine guardate il Veneto. In altre parole, gli amministratori di alcune regioni del sud fanno bene a chiedere un trasferimento immediato di materiale e risorse. 

## Commenti finali
Un paio di lezioni da tutto ciò:
1. A meno di numeri così evidenti da risaltare immediatamente (la Lombardia), l'emergenza esiste, almeno in parte, dove la si cerca. 
2. I dati crudi non servono per fare confronti. 

E forse i giornali dovrebbero cambiare strategia se vogliono informare a dovere.


***
- Dati: Protezione civile Italiana
- Img: Photo by [Fusion Medical Animation](https://unsplash.com/@fusion_medical_animation) on [Unsplash](https://unsplash.com)
- Grafici prodotti usando R and ggplot2
