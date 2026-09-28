# Doppia Lettura

Sito comune di **MEDyLAB** (Giuseppe Cardillo) e **Self Coherence** (Pino Di Ionna) sullo studio integrato di variabilità cardiaca (HRV) e cortisolo salivare.

- Indirizzo pubblico: https://dnafinder.github.io/doppia-lettura/
- QR code da usare agli incontri: `qr-doppia-lettura.png` (per stampe grandi c'è anche la versione SVG, fuori dal repository)

Il sito non vende niente: spiega perché conviene leggere insieme cuore e saliva e rimanda ai due negozi. Acquisti, fatture e referti restano sui siti madre.

## Cosa c'è nella pagina

1. **Apertura**: «Lo stress si misura due volte: dal cuore e dalla saliva», con un'illustrazione del sensore HRV e della provetta.
2. **Una giornata, due tracciati**: grafico schematico di 24 ore con HRV e cortisolo. I valori sono tipici e dichiarati come illustrativi.
3. **Due sistemi, due tempi**: sistema nervoso autonomo (rapido) contro asse ipotalamo-ipofisi-surrene (lento).
4. **Perché leggerli insieme**: concordanza, discordanza, stessa settimana, piano verificabile.
5. **Protocollo Doppia Lettura**: il prodotto comune, spiegato nella sezione successiva.
6. **Esami e servizi**: link diretti ai prodotti dei due negozi, per chi vuole partire da un lato solo.
7. **Professionisti**, **Chi siamo**, avvertenza medica e dati societari.

## Il Protocollo Doppia Lettura

Si presenta come un prodotto unico: cinque giorni di monitoraggio HRV che si chiudono di domenica con la raccolta della saliva per il profilo del cortisolo; i due tracciati sono letti insieme nella consulenza finale da cui nasce il piano di 90 giorni.

Si attiva con **due ordini separati** perché le prestazioni di MEDyLAB sono sanitarie ed esenti IVA mentre quelle di Self Coherence no: vanno fatturate da due soggetti diversi. Sul sito questo è spiegato in una riga, senza farne un problema.

| Ordine | Dove | Contenuto | Link |
|---|---|---|---|
| 1 · Il cuore | Self Coherence | Bodyguard 3 per 5 giorni, consulenza nutrizionale, advisor, piano di 90 giorni | vedi «Da fare» |
| 2 · La saliva | MEDyLAB | kit e referto Adrenal Stress Index | `https://www.medylab-na.it/carrello/?add-to-cart=4100` |

Il prodotto MEDyLAB ha ID **4100**. È nascosto dal catalogo e raggiungibile solo da questo sito: il link lo mette direttamente nel carrello.

- Prezzo con PayPal: **134.94 €**
- Prezzo con bonifico: **130.00 €** (il negozio toglie il 3.4% e poi 0.35 €)

Il vecchio codice sconto `selfcoherence10` non compare più sul sito.

## Da fare

- [ ] **Pino**: creare la versione del percorso Wellness **senza** il test Adrenal Stress Index, che adesso si compra su MEDyLAB. Finché il sito punta al Wellness attuale, chi segue il protocollo pagherebbe l'ASI due volte. Appena c'è il nuovo link va sostituito nell'ordine 1.
- [ ] **Pino**: la pagina Wellness attuale parla di uno sconto riservato ai partecipanti al Passatore. Nella versione nuova va tolto.
- [ ] **Pino**: confermare la qualifica da scrivere accanto al suo nome (oggi: «Specialista di HRV e sistema nervoso autonomo»).
- [ ] **Entrambi**: decidere chi avvisa chi quando arriva un ordine. I kit partono da due magazzini diversi e la saliva va raccolta l'ultimo giorno di monitoraggio, la domenica, quando il sensore è ancora addosso.

## Come modificare il sito

Il sito è un solo file, `index.html`, con testi, stile e illustrazioni dentro. I font sono nella cartella `fonts/` e non si caricano da Google: per la privacy dei visitatori è meglio così.

- Per cambiare un testo o un link basta modificare `index.html` e salvare. GitHub Pages ripubblica da solo in un paio di minuti.
- Le foto di Giuseppe Cardillo e del laboratorio arrivano da medylab-na.it, quella di Pino dal sito di Self Coherence. Se un file viene rinominato o cancellato, al suo posto compare un'illustrazione e la pagina non si rompe.
- La pagina non usa cookie e non raccoglie dati: non serve un banner.

Se usate Claude per le modifiche, dategli questo file da leggere prima di iniziare: contiene tutte le decisioni prese finora.

## Regole di scrittura

- Italiano curato, frasi asciutte, niente toni da televendita.
- Niente virgola prima di «e», «ma», «o», «perché» e simili.
- Separatore decimale: il punto (134.94, non 134,94).
- Nessun consiglio alimentare nei testi: la nutrizione resta affidata ai professionisti del percorso.
- Non si scrive «percorso clinico»: il protocollo è orientato al benessere e non sostituisce il medico.
