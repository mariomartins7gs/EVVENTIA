# Politica di pubblicazione

Il repository pubblico è costruito mediante una lista esplicita di contenuti ammessi. Nessun file proveniente da ambienti operativi viene pubblicato automaticamente.

## Ammesso

- documentazione architetturale provider-neutral;
- diagrammi e contratti con placeholder;
- esempi sintetici privi di dati personali;
- roadmap e stato espressi per Gate e ruolo;
- test o prove riproducibili che non rivelino configurazioni operative.

## Escluso

- esportazioni applicative legate a un ambiente, incluso `*.msapp`;
- codice applicativo non ancora approvato per la pubblicazione;
- dati grezzi, dati cliente e identificativi personali;
- credenziali, token, URL firmati, ID di tenant, ambiente o connessione;
- hostname di sviluppo e riferimenti a infrastrutture attive;
- assegnazioni individuali, valutazioni, recovery log e comunicazioni interne;
- riferimenti agli strumenti usati durante progettazione e sviluppo quando non necessari al prodotto.

## Controlli prima del push

1. Verifica della lista dei file candidati.
2. Ricerca di segreti, dati personali e identificativi di ambiente.
3. Controllo dei metadati dei file binari.
4. Revisione manuale di README, diagrammi e schermate.
5. Verifica che ogni URL operativo sia sostituito da un placeholder.
6. Push da una cronologia pulita, senza importare commit dal repository di controllo.
