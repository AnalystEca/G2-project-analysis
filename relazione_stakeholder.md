---
title: "LEC 2025 — Cosa ci dicono i dati"
subtitle: "Sintesi per stakeholder"
author: "Eca"
date: "Maggio 2026"
lang: it
geometry: margin=2.4cm
fontsize: 12pt
mainfont: "TeX Gyre Termes"
linkcolor: "blue!60!black"
---

# Executive summary

Abbiamo analizzato tutte le **306 partite** giocate nella *League of Legends EMEA
Championship* del 2025. La fotografia che ne emerge è chiara: il LEC è un
campionato veloce e aggressivo, dove le partite si decidono presto e dove un
piccolo gruppo di team controlla sistematicamente le fasi iniziali. **G2 Esports**
e **Karmine Corp** si confermano i team più solidi: G2 è l'unico che riesce a
costruire vantaggio anche nelle partite che poi perde, Karmine è il miglior team
nel controllo del drago e nel recupero dello svantaggio. Le metriche individuali
classiche (come il rapporto fra uccisioni e morti) restano un forte indicatore
delle squadre vincenti, mentre la sola "quantità di danno" fatta da un giocatore
non basta a spiegare il successo. Infine, già **al minuto 15** disponiamo di
informazioni sufficienti per prevedere con buon margine l'esito della partita.

\vspace{1em}

\hrule

# 1. Contesto e obiettivo

Per quattro mesi all'anno il campionato europeo di *League of Legends* — il
LEC — è uno dei prodotti competitivi più seguiti del panorama esports. Ogni
partita produce centinaia di metriche di gioco. Abbiamo raccolto tutti i dati
ufficiali della stagione 2025 e li abbiamo analizzati con un duplice obiettivo:

- capire **come si gioca** nel LEC e cosa caratterizza il campionato;
- capire **chi gioca meglio** e perché, distinguendo fra fattori superficiali
  e fattori sostanziali della vittoria.

Il lavoro è stato impostato come progetto di portfolio personale: ci siamo
posti le stesse domande che un team analyst, un giornalista esports o un
operatore di betting si farebbero davanti a questi dati.

# 2. Cosa abbiamo scoperto

## 2.1 Il LEC è un campionato veloce

La partita media dura circa **33 minuti**, con un ritmo di gioco di poco meno
di **una uccisione al minuto**. Il grafico delle durate mostra che la maggior
parte delle partite si chiude tra i 27 e i 32 minuti: molto raramente i match
superano i 45 minuti.

Questo è un dato di carattere: il LEC non è un campionato in cui le squadre
giocano a lungo per consolidare un vantaggio, ma uno in cui le scelte
aggressive degli inizi pesano molto sul risultato finale.

## 2.2 Il lato della mappa pesa, ma non sempre

Nel campionato di *League of Legends* le squadre giocano metà delle partite dal
lato "blu" e metà dal lato "rosso" della mappa. In molti campionati il lato blu
è considerato avvantaggiato.

Nel LEC 2025 questo è vero **soprattutto nello Spring Split**, dove il blu vince
circa 20 punti percentuali in più rispetto al rosso. Nelle altre fasi della
stagione la differenza si riduce. E, soprattutto, **nelle partite più lunghe il
vantaggio si inverte**: il rosso vince leggermente di più. È un'evidenza utile
per chi prepara le partite: il "vantaggio del lato blu" è un effetto reale ma
limitato, non automatico.

## 2.3 Chi parte bene di solito vince — ma non sempre

I team che ottengono la prima uccisione della partita vincono il 55% delle
volte, contro il 45% di chi non la ottiene. È una differenza significativa, ma
non dirompente: il LEC non è un campionato dove "chi parte bene chiude".

Anche il dato sul primo *Baron Nashor* — l'obiettivo neutrale che dà un grosso
boost alla squadra — è meno conclusivo di quanto sembri. Chi ottiene il primo
Baron vince l'**84%** delle partite. Sembra enorme, ma a guardare meglio: chi
ha un vantaggio economico solido già a 15 minuti vince circa nella stessa
percentuale, e il Baron arriva tipicamente dopo. Significa che il **primo
Baron è più una conseguenza** del fatto di stare già vincendo che la causa
della vittoria.

## 2.4 I team di vertice si distinguono per due cose: convertire e recuperare

Tutte le squadre, quando vincono, hanno in media un vantaggio economico a 15
minuti. Tutte, quando perdono, sono in svantaggio o in parità. **Una sola
eccezione: G2 Esports**, che riesce a costruire vantaggio anche nelle partite
che poi perde.

Questo ci porta a due metriche più sofisticate:

- **Capacità di chiudere quando si è avanti** (in inglese: *conversion rate*).
  Tre team la dominano: **Fnatic** (oltre l'80% di vittorie quando è in
  vantaggio a 15 minuti), **G2 Esports** e **Team Vitality**.
- **Capacità di rimontare quando si è indietro** (*recovery rate*). Quasi tutti
  i team del LEC, sotto il 50%, raramente vincono quando partono male. Solo
  due squadre fanno eccezione: **Karmine Corp** e **G2 Esports**.

Questi due indicatori, presi insieme, dicono che G2 e Karmine sono i team
strutturalmente più solidi del campionato.

## 2.5 Il controllo del drago è un indicatore-bandiera

I draghi del Rift sono obiettivi neutrali che richiedono tempo e coordinazione.
Chi li controlla è quasi sempre nel team più forte del campionato. La
classifica del dragon control rate è una sintesi pulita delle forze del LEC:

- **Karmine Corp** è al primo posto, con il 59% dei draghi controllati;
- **G2 Esports** e **Fnatic** seguono, entrambe sopra il 56%;
- in coda troviamo **SK Gaming** e **Natus Vincere**, che hanno disputato meno
  partite e che si sono trovate in fondo alla classifica.

## 2.6 Le statistiche dei giocatori: cosa conta davvero

Per i singoli giocatori, due indicatori sono particolarmente parlanti:

- **Il rapporto uccisioni/morti (KDA)** è **fortemente legato alla vittoria**:
  chi ha un KDA alto è quasi sempre in una squadra che vince. È una
  correlazione molto solida.
- **La percentuale di danno generato** (damage share) è invece **scollegata
  dalla vittoria**: si può fare moltissimo danno e perdere comunque la
  partita, oppure farne poco e vincere. Il danno da solo non spiega chi vince.

Una considerazione di metodo: il fatto che KDA sia legato al win rate non
significa che "fare bene il KDA" causi la vittoria; può essere semplicemente
che chi sta vincendo muore meno e quindi ha un KDA migliore. È utile come
indicatore, non come obiettivo da inseguire individualmente.

Altri punti che vale la pena segnalare:

- I ruoli **Bot (ADC) e Mid** producono insieme oltre il 50% del danno della
  squadra: confermano il loro ruolo di *carry*.
- Il miglior support per controllo della *vision* sulla mappa è **Fleshy**,
  unico oltre la soglia "premium" delle 4 unità per minuto.
- I giocatori che migliorano di più nelle partite lunghe — i cosiddetti
  *clutch* — sono **Carlisen**, **Flakked** e **Sheo**.

## 2.7 Possiamo prevedere chi vincerà già al minuto 15?

Sì, e con una buona affidabilità. Abbiamo addestrato un modello statistico
(*Random Forest*) usando solo i dati disponibili al minuto 15: differenza di
oro, di esperienza, di punteggi di "primato" (first dragon, first tower, ecc.).
Il modello prevede l'esito della partita con un'accuratezza nettamente
superiore al puro caso. Significa che, anche senza vedere il resto della
partita, **già un terzo del match contiene la maggior parte dell'informazione
che serve a sapere come finirà**.

# 3. Impatto e implicazioni pratiche

Cosa possiamo fare con questi risultati?

- **Per le squadre**: le metriche di conversion e recovery rate sono migliori
  indicatori della forza strutturale di una squadra rispetto al semplice record
  vittorie/sconfitte. Suggeriamo di tenerle d'occhio come *KPI* di stagione.
- **Per la preparazione delle partite**: l'esito si gioca in larga parte nei
  primi 15 minuti. Investire risorse di scouting nell'analisi dell'early game
  ha un valore informativo molto superiore all'analisi del *late game*.
- **Per la narrazione sportiva**: il *first Baron* è un evento "fotografabile"
  ma in larga parte epifenomenico. È più informativo raccontare cosa è successo
  prima del Baron — il vantaggio economico costruito o subito — che il Baron
  stesso.
- **Per gli analisti individuali**: il KDA è un indicatore utile, il damage
  share da solo no. Suggeriamo di non confrontare i giocatori per damage share
  in isolamento, ma di abbinarlo sempre a metriche di efficacia.

# 4. Raccomandazioni

- **Adottare conversion e recovery rate come KPI primari** nelle valutazioni di
  team — più informativi del solo win rate.
- **Affinare lo scouting dell'early game** con tracking dedicato delle
  differenze a 10/15 minuti su gold, esperienza e visione.
- **Trattare il "primo Baron" come un effetto, non come una causa**: nella
  comunicazione e nella formazione interna, evitare di promuoverlo come "leva
  per vincere".
- **Distinguere chiaramente fra metriche correlate e metriche causali**: la
  correlazione KDA → vittoria è altissima, ma il KDA non è una leva attivabile
  da un giocatore — non si "decide" di avere un buon KDA.
- **Allargare l'analisi alle altre regioni** (LCK, LPL, LCS) prima di
  trasformare gli insight di questo studio in convinzioni assolute: alcuni
  effetti — come quello del Blue side — potrebbero essere specifici del LEC.

# 5. Prossimi passi

- **Costruire un modello predittivo dinamico** che aggiorni la probabilità di
  vittoria minuto per minuto, e non solo a 15 minuti.
- **Replicare l'analisi su altre leghe** per stabilire quali risultati sono
  generali e quali sono peculiarità del LEC.
- **Profilazione automatica degli stili di gioco** dei giocatori, basata su
  raggruppamenti statistici delle loro metriche per ruolo.
- **Approfondire i casi anomali**: G2 che genera vantaggio anche in sconfitta,
  Natus Vincere con il suo campione ridotto, l'inversione del lato blu nelle
  partite più lunghe.

\vspace{2em}

\hrule

\textit{Per i dettagli tecnici, il dataset e la metodologia, si rimanda alla
relazione tecnica completa \texttt{relazione\_tecnica.pdf} e al notebook di
analisi \texttt{G2\_analisi\_clean.ipynb}.}
