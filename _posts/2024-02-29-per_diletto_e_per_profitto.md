---
layout: post
title:  "Per diletto e per profitto"
date:   2024-02-29 14:00:00 +0100
categories: [OSR, House Rules]
tags: [ladro, system-agnostic]
published: false # false: esclude il post dalla pubblicazione 
---

...ma soprattutto per profitto.

### Nuove regole system-agnostic per onesti Scassinatori

> Tranquilli, non ho la minima intenzione di tradurre tutto quello che stava sul vecchio blog. Ma non potevo aprire degnamente <span style="color:#EB5E28">**Dungeon Keys**</span> se non con un articolo che parla di serrature ostinate e grimaldelli. Più che un blog OSR, questa è una ferramenta. 

> Queste regole sono praticamente un mini-gioco che unisce dadi e ragionamento per imitare l'approccio di uno scassinatore a una serratura a pistoncini (ma vanno bene anche i classici lucchetti). Dedicare un mini-gioco all'arte del grimaldello può avere senso con alcuni regolamenti e meno con altri, ma chiaramente mettere sul tavolo i dadi significa che qualsiasi approccio puramente descrittivo va a farsi benedire. 

> Poco importa, se anche voi (come me) avete pensato "beeeh diamine la giocherei proprio una bella avventura ispirata a *Thief*". In questo caso, continuate a leggere.

![Desktop View](/assets/img/lockpicking.png){: width="972" height="589" .w-50 .left} 

## La serratura

Quando un Personaggio tenta di scassinare una serratura, il GM dispone fisicamente sul tavolo una serie di d6 per rappresentare la **difficoltà** del dispositivo. Ciascun d6 rappresenta un <span style="color:#EB5E28">*pin*</span> (un pistoncino) all'interno della serratura, e ciascun pin è in una precisa <span style="color:#EB5E28">*posizione*</span> (il numero sul dado, che può andare da 1 a 5). Più d6/pin ci sono in una serratura, più è difficile scassinarla. Anche i numeri sui d6 contribuiscono alla difficoltà della serratura: più sono bassi, peggio è per lo scassinatore.

Ecco qualche esempio.

Serratura grossolana
: [ 4 ] [ 5 ]

Meccanismo complesso
: [ 3 ] [ 3 ] [ 4 ]

Il peggior incubo di un ladro
: [ 2 ] [ 2 ] [ 2 ] [ 2 ]

### Il lavoro di fino

Per scassinare la serratura e partecipare così alla gloriosa redistribuzione del reddito, il ladro deve tirare un certo numero di d6, meglio ancora se di colore diverso (ma non fossilizziamoci sui dettagli). In questo esempio, il numero di d6 dipende dalla <span style="color:#EB5E28">*qualità*</span> del grimaldello utilizzato, perché da queste parti ci piace l'idea che i Personaggi facciano cose in base al loro equipaggiamento. Nulla impedisce di rendere il numero di d6 più dipendente dalle capacità dello scassinatore, dalla pratica o da quant'altro volete. 

Attrezzo improvvisato, neanche un vero grimaldello
: 1d

Grimaldello vecchio e consumato
: 2d

Arnesi approvati dalla Gilda
: 4d

(*e così via*)

Una volta che questi dadi sono stati tirati, il giocatore li assegna liberamente a ogni *pin* per fare in modo che il totale (valore sul pin + valore sul d6 assegnato) corrisponda a 6 o più. Se tutti i pin arrivano a 6+, *poof*, ecco che scatta la magia, apriti sesamo e tutta quella roba lì. 

Esempi:

La serratura mostra un [ 4 ] [ 4 ]. Un gioco da ragazzi.
: Ma il nostro scassinatore è un vero pollo. Usando alcuni attrezzi da scasso di base (qualità 2d) tira e ottiene un 1 e un 2. Nessuna combinazione può portare entrambi i pin a 6+: il tentativo fallisce. 

La serratura è un [ 3 ] [ 2 ]. Una noce più dura da spaccare.
: Lo scassinatore, usando un grimaldello di precisione nuovo di zecca (4d) tira e ottiene un 1, un 3, un 4 e un altro 1. Ecco: alcune combinazioni qui consentono di portare entrambi i pin a 6+. Il giocatore assegna il 4 al secondo pin (portandolo a 6) e 3 al primo pin (stesso risultato). Gli 1 tirati non sono necessari.

<span style="color:#EB5E28">Importante!</span>
: Il giocatore è libero di usare più di un d6 tirato sullo stesso pin. Anzi, questo può rivelarsi addirittura necessario per oltrepassare le serrature più difficili.

### Due parole su tutto questo

Questo sistema mi piace per tre motivi.

1. È veloce, ma non è *troppo* veloce. Una volta che il giocatore sa quanti d6 deve tirare, è solo questione di assegnare i risultati ai dadi/pin disposti dal GM. Il calcolo è triviale e richiede giusto il minimo sindacale di logica (e un bacetto dalla dea bendata).
2. È fisico, quasi tangibile. Ogni dado rappresenta un pin. I pin devono andare in posizione. Le regole aderiscono all'esperienza dello scassinatore in maniera abbastanza intuitiva (ma non chiedetemi come faccio a saperlo).
3. C'è parecchio spazio per interazioni più approfondite (vedi sotto)

Ovviamente, questo sistema rende la difficoltà di una serratura *immediatamente nota* ai giocatori che tentano l'effrazione. Non credo che questo sia un lato negativo: un buon ladro dovrebbe essere in grado di giudicare quanto è rognosa una serratura dopo una rapida occhiata al meccanismo. Un GM più stronzo di me potrebbe persino decidere di rendere noto solo il *numero dei pin* e non il loro valore di partenza, replicando l'esperienza dell'apertura di una serratura a cilindri in maniera ancora più precisa: basta dire al giocatori quali pin sono nella corretta posizione dopo ogni tentativo. Però credo che così si rischi di scadere nel Simon Says e io dopo un po' mi romperei le palle. 

Questo sistema implica anche che tirare 2d o 3d su una serratura a 4 pin equivale a un fallimento automatico: non hai l'attrezzo giusto per questo lavoro. Di nuovo, nel framework di una campagna ispirata a *Thief* io tendo a considerare la cosa una feature, non un bug. *Working as intended!*

Ma c'è ancora spazio per un po' di *spippolamenti*. 

### Spippolare il sistema

Quella che ho descritto finora è la base, il cosiddetto *nitty-gritty*. La matematica funziona, più o meno. Forse c'è da alzare un pelo la difficoltà (e dire che il successo per ogni pin è al 7+, per esempio). In ogni caso, il bilanciamento del sistema si può misurare facendo qualche calcolo, e la prima grandezza che mi viene in mente è *numero di dadi tirati* vs *totale richiesto*.

Ora, cosa dovremmo farci con questo sistema? Di base **nulla**, soprattutto se il nostro regolamento è un generico rules-light non particolarmente incentrato sul ladrocinio. Queste regole per le serrature possono essere un add-on per diversi giochi e già così possono introdurre un po' d'aria fresca a una situazione che a volte sa di già visto.

Ma per un'avventura dove la furtività e le azioni clandestine sono il punto di tutta la faccenda, allora abbiamo molto più spazio per giochicchiare con le regole e rendere le interazioni un po' più interessanti. Ecco un po' di possibilità da contemplare.

Dadi bonus al tiro
: Forse il tuo grimaldello da 3d non è abbastanza ganzo per quella cassaforte da 4d, ma tu sai fare miracoli. Se un'abilità o una specializzazione da Ladro ti permettono di tirare un dado bonus o due, questo significa che non solo hai *maggiori probabilità di successo* per ogni effrazione, ma anche che per te è possibile aprire serrature che sarebbero normalmente al di fuori dalla tua portata. 

Bonus di +X a un dado
: Ti serviva un 3, hai tirato un 2. Poco male! Anche questo può dipendere dalle abilità del ladro. Un vantaggio minore ma sempre valido.

Alzare il valore di un pin
: Guarda, questo bonus è esattamente identico al precedente, ma si applica ai pin anzichè ai tiri. Tra le due, userei questa variante.

Ritirare un dado
: Anche questo è un grande classico del design semplice e immediato. 

Ignorare uno o più pin
: Questa è la roba che scotta. Un'abilità del genere pootrebbe essere position-based (come *Ignori sempre il primo pin di una serratura*, da sinistra verso destra). Oppure potrebbe addirittura essere *Ignori un pin a tua scelta*. Roba da Arsenio Lupin.

Dadi di taglia diversa
: E se uno dei dadi di un grimaldello speciale fosse un d8, invece che un d6? Particolarmente utile per quei pin con un valore di partenza più basso, meno utile per le serrature con molti pin con valori di partenza alti, e con altre applicazioni interessanti (ci arriviamo subito).

Dato che abbiamo ideato tutto quest'arsenale per i nostri cari ladri, ora andiamo a complicargli la vita.

Consumo
: I grimaldelli possono consumarsi con l'utilizzo, magari a ogni fallimento. Possono subire penalità ai dadi (-1, -2, etc.) oppure aggiungere direttamente un dado in meno. 

Serrature di precisione
: Alcuni meccanismi avanzati richiedono un *posizionamento preciso* dei pin. In questo caso, non basta ottenere un 6+ su ogni pin: il totale deve rientrare in un certo range. Un pin viene considerato posizionato solo se il suo totale è 6-8. Se raggiungi il 9, sei andato troppo in alto.

Serrature combinate
: Alcuni meccanismi estremamente avanzati, come le serrature naniche, potrebbero presentare delle stack di *più di un dado sullo stesso pin* e finire per avere questo aspetto:
<div style="margin-bottom:0px;margin-left:30px;line-height:1">[ 2 ]</div>
<div style="margin-bottom:20px;margin-left:30px;line-height:1.3">[ 1 ] [ 3 ]</div>

Avere valori di 1 e 2, uno sopra l'altro, significa che il ladro deve raggiungere un totale di 12+ (6+ e 6+) per quel pin. In questo caso, dato che i valori di partenza sono 1 e 2, la base del pin è 3, quindi bisogna aggiungere dadi dal tiro per un valore di 9 o più! Meglio cercarsi qualche ferro di qualità.

### In chiusura

Ecco fatto. Un mini-gioco di effrazione, dalla semplicità regolabile, per tutti quei personaggi tradizionalmente meno rispettosi della proprietà privata. 

Non offro una guida al bilanciamento delle serrature perché penso davvero che una buona occhiata iniziale alla matematica dovrebbe consentire a un GM di prendere confidenza con il sistema in poco tempo (e siamo un po' tutti abituati ai d6). Io sto usando il target 6+ perché è facile da memorizzare (6+ su d6). Se le cose sono troppo facili, allora si può puntare al 7+. Il resto del bilanciamento si gioca tutto sul numero dei dadi che è possibile tirare, aggiungere, ritirare grazie a strumenti, competenze, capacità di classe, tricchetracche e bombe a mano. 

Fatemi sapere!

#### Illustrazioni

Arthur Rackham
: in T. Ingoldsby, *The Ingoldsby legends; or, Mirth & marvels*. London, New York: E. P. Dutton & Co., J. M. Dent & Co., 1907. Pubblico dominio.