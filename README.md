# moviessqlitemvvm

# SQLite
è un db di tipo embedded ed è di tipo relazionale
- non richiede un processo server dedicato esterno all'aplicazione

## carattaristiche
- serverless
- embedded
- leggero
- transazionale: supporta le transazioni ACID -> garantice l'integrita dei dati
- SQL standar

## integrazione in una app
-dobbiamo integrare il pachetto sqflite

## vantaggi
- offline data store
- prestazioni
- semplice da utilizzare
- portabilita'

# consiglio
pianificare precedentemente la struttura del database per garantire prestazione ottimali

# database
la base di dati che conterra' i nostri folm
## tabella

abbiamo la tabella dei film
- title -> string
- duration -> in
- plot -> string
- year -> int

il tutto sara' con archittetura Model View ViewModel

- Model -> class Movie
- View -> ad esempio la scherma per l'elento dei fil
- ViewModel -> ModelViewModel si occupa di gestire lo stato della applicazione e fornire i dati alla vista

Utilizzare il pacchetto Provider state management