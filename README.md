# Progetto - Introduzione alla Data Science e al Pensiero Computazionale

## Membri del gruppo 6
**Gaia Bellomo**: matricola 1226500, gaia.bellomo4@studio.unibo.it \
**Carlotta Forza**: matricola 1230704, carlotta.forza@studio.unibo.it \
**Federica La Braca**: matricola 1216267, federica.labraca@studio.unibo.it 

## Descrizione del progetto 
Il presente progetto è stato realizzato come prova finale del corso di Introduzione al Pensiero Computazionale e alla Data Science (a.a. 2025/2026).
L'obiettivo consiste nello sviluppo di un progetto completo di Data Science, comprendente tutte le principali fasi del processo analitico: comprensione del dataset, analisi esplorativa dei dati, preparazione del dataset, addestramento di modelli di Machine Learning, valutazione dei risultati e interpretazione critica delle prestazioni ottenute.
L'analisi è stata svolta utilizzando Python e le principali librerie per la Data Science, seguendo la struttura e i requisiti previsti dal progetto di fine corso.

## Dataset
**Nome dataset:** Online Shoppers Purchasing Intention Dataset \
Il dataset raccoglie informazioni relative alle sessioni di navigazione degli utenti su una piattaforma di e-commerce e descrive il comportamento dei visitatori attraverso variabili riguardanti:
- caratteristiche della sessione di navigazione;
- tempo trascorso nelle diverse tipologie di pagine;
- indicatori di comportamento (Bounce Rate, Exit Rate, Page Values);
- informazioni sul visitatore;
- informazioni temporali (mese, weekend, giornate speciali);
- caratteristiche tecniche della navigazione (browser, sistema operativo, regione, tipologia di traffico).
La variabile target è **Revenue**, che indica se la sessione si è conclusa con un acquisto (True) oppure senza conversione (False).
**Obiettivo:** l'obiettivo principale consiste nella previsione dell'intenzione di acquisto degli utenti durante una sessione di navigazione. Per arrivare a comprendere ciò, il progetto è stato articolato nelle seguenti fasi:

1. analisi e comprensione del dataset;
2. analisi esplorativa e visualizzazione dei dati;
3. preprocessing e preparazione delle variabili;
4. addestramento di diversi modelli di classificazione;
5. confronto delle prestazioni dei modelli mediante le principali metriche di valutazione;
6. interpretazione critica dei risultati ottenuti.

## Struttura del repository

├── data/                                *dataset utilizzato durante il progetto*  \
│ └── Online_Shoppers.csv  \
├── figures/                             *grafici e immagini prodotti durante le analisi* \  
├── notebooks/                           *notebook contenente l'intero sviluppo del progetto* \
│ └── Progetto_IntroDSePC_Gruppo_6.ipynb  \
├── report/                              *relazione in formato PDF e relativi file LaTeX* \
│ ├── Report_Online<-Shoppers_Intentions.pdf  \
│ └── sorgenti LaTeX  \
└── README.md                            *descrizione generale del progetto*

## Modelli utilizzati
Per affrontare il problema di classificazione sono stati sviluppati e confrontati quattro modelli di Machine Learning: Logistic Regression, Random Forest, k-Nearest Neighbors (k-NN) e Support Vector Machine (SVM).
Prima della fase di addestramento il dataset è stato sottoposto a un processo di preprocessing comprendente la conversione delle variabili categoriche, la suddivisione in training e test set e la standardizzazione delle feature quando richiesta dall'algoritmo.
Le prestazioni dei modelli sono state confrontate attraverso le principali metriche di classificazione:
- Accuracy
- Precision
- Recall
- F1-score 
- Confusion Matrix
al fine di individuare l'approccio più efficace per la previsione dell'intenzione di acquisto.

## Istruzioni per l'esecuzione
Il progetto è stato sviluppato in ambiente Google Colab utilizzando Python. Per riprodurre l'analisi è sufficiente:
1. clonare o scaricare il repository;
2. aprire il notebook contenuto nella cartella `notebooks/`;
3. verificare che il dataset `Online_Shoppers.csv` sia presente nella cartella `data/`;
4. eseguire il notebook dall'inizio alla fine.
Il notebook contiene tutte le fasi del progetto: analisi descrittiva del dataset, analisi esplorativa, preprocessing, addestramento dei modelli e valutazione dei risultati.
