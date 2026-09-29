# Istruzioni per Claude

Questo repository è il sito «Doppia Lettura» di MEDyLAB (Giuseppe Cardillo) e Self Coherence (Pino Di Ionna). Ci lavorano due persone, ciascuna con il proprio Claude.

## Prima di fare qualsiasi cosa

1. Esegui `git pull`.
2. Leggi tutto `README.md`: contiene le decisioni prese, i prezzi, i link ai negozi e le regole di scrittura.
3. Rispetta la **regola del turno** descritta nel README:
   - se nella cartella principale esiste `lockme.md`, **non modificare niente**: di' all'utente chi sta lavorando e da quando, e fermati;
   - se non esiste, crealo (chi, data e ora, cosa), fai commit e push del solo `lockme.md` **prima** di ogni altra modifica; se il push viene rifiutato, rifai `git pull` e ricontrolla;
   - a lavoro finito, pubblica le modifiche e cancella `lockme.md`;
   - non cancellare mai il `lockme.md` dell'altro senza il suo consenso esplicito.

## Come si lavora sul sito

- Il sito è un solo file, `index.html`, con stile, testi e illustrazioni SVG al suo interno. I font sono in `fonts/`, le immagini in `img/`.
- Non caricare risorse da siti esterni (font, immagini, script): tutto deve stare nel repository.
- Non pubblicare cambiamenti che l'utente non ha chiesto: proponi e aspetta il via libera.
- Testi in italiano, secondo le regole di scrittura del README. Mai consigli alimentari. Il preprint su Zenodo si cita sempre come preprint.
- Aggiorna il README quando cambia una decisione (prezzi, link, contenuti del protocollo, cose da fare).
