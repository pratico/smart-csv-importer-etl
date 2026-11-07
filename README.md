# Smart CSV Importer

## Panoramica del Prodotto

**Smart CSV Importer** è un'applicazione web progettata per e-commerce, catalog manager e team operativi che gestiscono quotidianamente listini prodotti di grandi dimensioni. L'applicazione automatizza l'intero ciclo di importazione dei listini fornitori: dal caricamento del file all'aggiornamento finale del catalogo aziendale, eliminando il lavoro manuale ripetitivo e riducendo drasticamente il margine di errore umano.

Si rivolge in particolare a:

- **E-commerce e rivenditori online** che ricevono listini fornitori in formati eterogenei;
- **Catalog manager** che devono mantenere migliaia di SKU sempre aggiornati;
- **PMI e agenzie** che gestiscono cataloghi multi-fornitore senza personale IT dedicato.

## Il Problema Risolto

Chi lavora con listini fornitori conosce bene la realtà operativa quotidiana:

- **Ore perse in inserimento manuale:** copiare e incollare righe di prodotti da fogli di calcolo eterogenei consuma giornate intere di lavoro, sottraendo tempo alle attività a valore aggiunto.
- **Errori di formato silenziosi:** prezzi con virgole al posto dei punti, quantità testuali, campi vuoti o malformattati generano cataloghi corrotti e ordini errati, con costi diretti su clienti e fatturato.
- **Duplicati che inquinano il catalogo:** lo stesso prodotto importato più volte (o con codici leggermente diversi) crea doppioni che confondono il team vendite e i clienti finali.
- **Colli di bottiglia operativi:** l'aggiornamento del catalogo diventa dipendente da una sola persona, creando ritardi a cascata su prezzi, disponibilità e pubblicazione online.

Smart CSV Importer trasforma un processo fragile e manuale in un flusso controllato, verificabile e rapido.

## Come Funziona (Flusso Operativo Utente)

Il flusso è pensato per essere completato in pochi minuti, senza competenze tecniche:

1. **Caricamento del file:** l'utente accede all'interfaccia web e carica il listino CSV fornito dal proprio fornitore, così com'è, senza necessità di pre-elaborazione.
2. **Anteprima dei dati:** prima di qualsiasi modifica al catalogo, l'applicazione mostra un'anteprima leggibile dei dati riconosciuti, permettendo all'utente di verificare a colpo d'occhio che il file sia quello giusto e che le colonne siano state interpretate correttamente.
3. **Validazione automatica:** il sistema analizza ogni riga e intercetta gli errori di formato (valori mancanti, numeri malformati, campi incoerenti), segnalandoli in modo chiaro all'utente prima dell'importazione definitiva.
4. **Gestione dei duplicati:** i prodotti già presenti nel catalogo vengono identificati ed eliminati automaticamente, evitando doppioni e incoerenze nei dati.
5. **Conferma e aggiornamento:** una volta verificata l'anteprima e risolti eventuali segnalazioni, l'utente conferma e il catalogo aziendale viene aggiornato in un'unica operazione.
6. **Risultato finale:** il catalogo è pronto, coerente e aggiornato, senza che l'utente abbia mai toccato una riga di codice o un foglio di calcolo.

## Funzionalità Principali & Vantaggi Operativi (ROI)

| Funzionalità | Vantaggio Operativo |
|---|---|
| Caricamento listini complessi | Riduzione da ore a minuti del tempo di aggiornamento catalogo |
| Anteprima pre-importazione | Controllo totale sui dati prima di qualsiasi modifica: zero sorprese |
| Intercettazione errori di formato | Cataloghi puliti e affidabili, meno resi e meno reclami |
| Eliminazione automatica duplicati | Dati coerenti, team vendite più efficiente |
| Aggiornamento catalogo in un'unica operazione | Eliminazione del collo di bottiglia legato a una singola persona |
| Interfaccia web intuitiva | Onboarding immediato, nessuna formazione richiesta al personale |

**ROI immediato:** per una PMI che aggiorna listini settimanalmente, il recupero di anche solo poche ore di lavoro manuale a settimana si traduce in un ritorno sull'investimento quasi immediato, oltre a una riduzione misurabile degli errori sui dati di catalogo.

## Tecnologie Utilizzate (Ad Alto Livello)

L'applicazione è costruita su uno stack tecnologico maturo e consolidato:

- **Node.js / Express:** piattaforma server-side leggera e ad alte prestazioni, ideale per gestire flussi di dati in modo stabile e reattivo.
- **MySQL:** database relazionale di riferimento per l'affidabilità e l'integrità dei dati transazionali, garanzia di coerenza del catalogo anche con volumi elevati.
- **Bootstrap 5:** interfaccia utente moderna, responsive e accessibile da qualsiasi dispositivo, senza dipendenze superflue.

Questa combinazione garantisce stabilità operativa nel tempo, bassi costi di manutenzione e prestazioni costanti anche con listini di grandi dimensioni.

---

🔒 **Asset Software Proprietario:** Questo repository ha finalità di presentazione funzionale per il Portfolio Professionale (antoniangeloflore.com). Per ragioni di sicurezza operativa e accordi di riservatezza (NDA), il codice sorgente e le specifiche infrastrutturali non sono esposti pubblicamente.
