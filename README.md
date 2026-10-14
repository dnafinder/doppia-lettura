# Doppia Lettura

Sito comune di **MEDyLAB** (Giuseppe Cardillo) e **Self Coherence** (Giuseppe «Pino» Di Ionna) sullo studio integrato di variabilità cardiaca (HRV) e cortisolo salivare.

- Indirizzo pubblico: https://dnafinder.github.io/doppia-lettura/
- QR code da usare agli incontri: `qr-doppia-lettura.png` (per stampe grandi c'è anche la versione SVG, fuori dal repository)

Il sito non vende niente: spiega perché conviene leggere insieme cuore e saliva e rimanda ai due negozi. Acquisti, fatture e report restano sui siti madre.

## Cosa c'è nella pagina

1. **Apertura**: «Lo stress si misura due volte: dal cuore e dalla saliva», con la foto di Pino e Giuseppe insieme (`img/doppia.jpg`). Se la foto non si carica compare l'illustrazione del sensore HRV e della provetta.
2. **Una giornata, due tracciati**: grafico schematico di 24 ore con HRV e cortisolo. I valori sono tipici e dichiarati come illustrativi.
3. **Due sistemi, due tempi**: sistema nervoso autonomo (rapido) contro asse ipotalamo-ipofisi-surrene (lento).
4. **Due freni sulla stessa infiammazione**: il razionale scientifico, con bibliografia.
5. **Tre profili, due tracciati**: i tre stati ASI (A coordinato, B alto carico e disorganizzato, C basso buffering) affiancati al profilo HRV atteso per ciascuno. Ridisegna l'infografica di Pino con curve schematiche senza scala numerica. Le percentuali (59.2%, 16.8%, 24.0%) vengono dai 2505 profili del preprint. I profili HRV sono **attesi**, non ancora verificati: va sempre detto.
6. **Perché leggerli insieme**: concordanza, discordanza, stessa settimana, piano verificabile.
7. **Metodo Doppia Lettura**: il prodotto comune, spiegato nella sezione successiva.
8. **Esami e servizi**: link diretti ai prodotti dei due negozi, per chi vuole partire da un lato solo.
9. **Professionisti**, **Chi siamo**, avvertenza medica e dati societari.

Sul sito il nome è sempre **Giuseppe Di Ionna** (non «Pino») con la qualifica **Specialista HRV**. Self Coherence si presenta come «Centro specializzato nella valutazione della Heart Rate Variability per applicazioni benessere e performance». Qui nel README e in `lockme.md` resta «Pino» per distinguerlo da Giuseppe Cardillo.

## Il razionale scientifico

L'ASI è una misura della **resilienza dell'organismo ai processi infiammatori**, non un test di «stanchezza surrenalica». È la tesi dell'articolo di Giuseppe Cardillo su Frontiers in Endocrinology (2026;17:1785454, doi:10.3389/fendo.2026.1785454): un profilo appiattito segnala che il cortisolo attivo fatica ad arrivare ai tessuti infiammati, con un meccanismo che passa dai neutrofili. Il preprint su Zenodo (doi:10.5281/zenodo.20447005) mostra che su 2505 profili i dati si distribuiscono in tre stati che cambiano nel tempo. Il preprint va sempre citato come preprint.

L'HRV si legge negli stessi termini: misura il tono del nervo vago, che attraverso il riflesso infiammatorio frena la produzione di citochine (Tracey, Nature 2002). Una variabilità bassa si associa a marcatori infiammatori più alti (Williams et al., Brain Behav Immun 2019).

Sul sito la sezione si chiama «Due freni sulla stessa infiammazione»: l'HRV legge il freno nervoso e veloce, l'ASI quello ormonale e lento. Per questo i due esami si completano.

## Il Metodo Doppia Lettura

Si chiama «metodo» e non «protocollo» perché «protocollo» suona come un termine medico. Su Shopify il prodotto si chiama «Monitoraggio HRV 5 giorni - Metodo doppia lettura».

Si presenta come un prodotto unico: cinque giorni di monitoraggio HRV che si chiudono (di solito la domenica) con la raccolta della saliva per il profilo del cortisolo; i due tracciati sono letti insieme nella consulenza finale con Pino e Giuseppe.

**Il messaggio chiave:** chi segue il metodo riceve tre documenti. Il report HRV di Self Coherence, il report del cortisolo di MEDyLAB e un **report combinato** che sovrappone i due tracciati e li legge insieme. Il report combinato è ciò che rende il metodo un prodotto unico e non la somma di due servizi.

Si attiva con **due ordini separati** perché le prestazioni di MEDyLAB sono sanitarie ed esenti IVA mentre quelle di Self Coherence no: vanno fatturate da due soggetti diversi. Sul sito questo è spiegato in una riga, senza farne un problema.

I contenuti dell'ordine 1 sul sito seguono la pagina Shopify: niente consulenza nutrizionale, niente advisor né piano di 90 giorni. Se Pino cambia la pagina Shopify va aggiornato anche il sito.

| Ordine | Dove | Contenuto | Link |
|---|---|---|---|
| 1 · Il cuore | Self Coherence | Bodyguard 3 per 5 giorni, app Firstbeat Life, consulenza finale con Pino e Giuseppe · **170.00 €** IVA inclusa | `https://www.selfcoherence.com/products/monitoraggio-hrv-5-giorni-adrenal-stress-index` |
| 2 · La saliva | MEDyLAB | kit e report Adrenal Stress Index | `https://www.medylab-na.it/carrello/?add-to-cart=4100` |

Schema tipo: il monitoraggio parte il mercoledì e si chiude la domenica con la raccolta della saliva. Non è una regola rigida: calendario e istruzioni li gestisce Self Coherence e il sito lo presenta come schema indicativo.

Il prodotto MEDyLAB ha ID **4100**. È nascosto dal catalogo e raggiungibile solo da questo sito: il link lo mette direttamente nel carrello.

- Prezzo con PayPal: **134.94 €**
- Prezzo con bonifico: **130.00 €** (il negozio toglie il 3.4% e poi 0.35 €)

Il prodotto Self Coherence dell'ordine 1 **non** comprende il test Adrenal Stress Index, che si compra su MEDyLAB. Il vecchio Wellness non va più usato.

Il vecchio codice sconto `selfcoherence10` non compare più sul sito.

## Da fare

- [ ] **Entrambi**: definire formato, contenuti e firma del report combinato e chi lo prepara.
- [ ] **Entrambi**: decidere chi avvisa chi quando arriva un ordine. Sensore e kit salivare partono insieme in un'unica spedizione: serve sapere chi la prepara. La saliva va raccolta l'ultimo giorno di monitoraggio, di solito la domenica, quando il sensore è ancora addosso.

## Regola del turno: un Claude alla volta

Sul sito lavorano due persone con due Claude diversi. Per non sovrascriversi a vicenda vale questa regola, per le persone come per Claude.

1. **Prima di toccare qualsiasi file** si scarica l'ultima versione del repository (`git pull`).
2. **Se nella cartella principale c'è `lockme.md`, ci sta lavorando l'altro.** Non si modifica niente: si legge il file per sapere chi è e da quando; poi si aspetta.
3. **Se `lockme.md` non c'è, lo si crea** con tre righe: chi lavora (Giuseppe o Pino), data e ora di inizio, cosa si sta facendo. Poi si fa subito commit e push del solo `lockme.md`, **prima** di qualsiasi altra modifica. Se il push viene rifiutato vuol dire che l'altro è arrivato prima: si scarica di nuovo e si torna al punto 2.
4. **A lavoro finito** si pubblicano le modifiche e, nello stesso commit o subito dopo, si **cancella** `lockme.md`.
5. **Se un `lockme.md` resta lì da più di 24 ore**, prima di toglierlo si chiede all'altro. Non si cancella mai il lucchetto altrui senza il suo via libera.

Esempio di `lockme.md`:

```
Chi: Giuseppe
Da: 2026-09-29 19:30
Cosa: aggiornamento dei prezzi del metodo
```

## Come modificare il sito

Il sito è un solo file, `index.html`, con testi, stile e illustrazioni dentro. I font sono nella cartella `fonts/` e non si caricano da Google: per la privacy dei visitatori è meglio così.

- Per cambiare un testo o un link basta modificare `index.html` e salvare. GitHub Pages ripubblica da solo in un paio di minuti.
- Le foto di Giuseppe Cardillo e del laboratorio arrivano da medylab-na.it, quella di Pino dal sito di Self Coherence. Se un file viene rinominato o cancellato, al suo posto compare un'illustrazione e la pagina non si rompe.
- La pagina non usa cookie e non raccoglie dati: non serve un banner.

Se usate Claude Code, il file `CLAUDE.md` gli dice da solo di leggere questo README e di rispettare la regola del turno. Con altri strumenti dategli voi questo file da leggere prima di iniziare.

## Regole di scrittura

- Italiano curato, frasi asciutte, niente toni da televendita.
- Niente virgola prima di «e», «ma», «o», «perché» e simili.
- Separatore decimale: il punto (134.94, non 134,94).
- Nessun consiglio alimentare nei testi: la nutrizione resta affidata ai professionisti del percorso.
- Non si scrive «referto» né «protocollo», che suonano medici: si usano «report» e «metodo».
- Non si scrive «percorso clinico»: il metodo è orientato al benessere e non sostituisce il medico.
