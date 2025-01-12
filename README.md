# Utilizzo di CNN e GNN per la Predizione dei Docking Score a Partire da Strutture Molecolari
## Descrizione del Progetto

Questo progetto, realizzato per l’esame di **Deep Learning** presso l’**Università degli Studi di Urbino Carlo Bo**, si concentra sulla **predizione dei docking score** a partire da strutture molecolari rappresentate in formato **SMILES** (*Simplified Molecular Input Line Entry System*).

### Obiettivo
L’obiettivo principale del progetto è sviluppare un modello predittivo in grado di stimare il **docking score** delle molecole, un valore critico che misura l’affinità di legame tra una molecola e il suo target biologico.

### Approccio
Per raggiungere questo obiettivo, sono state utilizzate le seguenti tecniche e strumenti:
- **RDKit**: per trasformare le rappresentazioni SMILES in due formati computazionali principali:
  - **Molecular Fingerprint**: una sequenza binaria che codifica le proprietà molecolari.
  - **Molecular Graph**: una rappresentazione grafica che descrive atomi e legami della molecola.
- **Reti Neurali**:
  - **Convolutional Neural Networks (CNN)**: utilizzate per elaborare i *Molecular Fingerprints*.
  - **Graph Neural Networks (GNN)**: utilizzate per elaborare i *Molecular Graphs*.

### Scopo
Il progetto esplora l’efficacia combinata di queste tecniche di **Deep Learning** al fine di migliorare la capacità predittiva del modello e fornire stime accurate dei docking score.

### Contesto e Rilevanza
Nel panorama della ricerca farmaceutica, il processo di sviluppo di nuovi farmaci è lungo, complesso e costoso. Questo progetto si inserisce nel contesto del **virtual screening**, una tecnica computazionale che permette di analizzare grandi librerie di molecole riducendo i costi e i tempi necessari per esperimenti in laboratorio. L’integrazione di tecnologie di deep learning consente di migliorare la precisione e l’efficienza del processo di screening, aprendo nuove possibilità per la scoperta di farmaci innovativi.

### Metodologia
Il progetto si articola in diverse fasi:
1. **Preprocessing dei Dati**: Validazione e trasformazione delle stringhe SMILES in formati computazionali.
2. **Feature Engineering**: Generazione di fingerprint molecolari e grafi molecolari utilizzando la libreria RDKit.
3. **Progettazione delle Architetture**: Implementazione di modelli di deep learning basati su CNN e GNN.
4. **Addestramento e Valutazione**: Ottimizzazione dei modelli e confronto delle prestazioni mediante metriche di valutazione standard (MSE, MAE, R²).

### Autori
Questo progetto è stato realizzato con la collaborazione di [Kevin Attarantato](https://github.com/KevAtta).
