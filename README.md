## Contenuto della Directory

La directory principale contiene le seguenti sottodirectory e file:

### 1. Tuplet Extractor LLM
- **Descrizione**: Questo file si occupa di impostare un modello di linguaggio avanzato (LLM) per l'estrazione di tuple. Permette di configurare la quantizzazione del modello e di regolare la temperatura, per ottenere un'estrazione accurata e personalizzata delle tuple dal testo.
- **Funzionalità principali**:
  - Configurazione LLM con quantizzazione e temperatura.
  - Estrazione automatizzata di tuple dalle stringhe di testo.

### 2. Dataset
- **Descrizione**: Include dati fittizi (Fake CTI) in due formati: 
  - **Fake CTI**: Dati di partenza, strutturati come articoli o documenti.
  - **Fake CTI - Tuples**: Gli stessi dati rappresentati tramite tuple estratte, pronti per l'analisi o la classificazione.
- **Utilizzo**: Questi dataset permettono di testare e valutare i modelli di classificazione e gli algoritmi di estrazione.

### 3. Classificatori
- **Descrizione**: Implementa due approcci per la classificazione CTI:
  - **DNN (Deep Neural Network)**: Modello di rete neurale basato su DistilBERT, pensato per analizzare i contenuti di CTI con un approccio avanzato di deep learning.
  - **Article Based**: Include tecniche NLP tradizionali, come **SBERT** (Sentence-BERT) e **TF-IDF** (Term Frequency-Inverse Document Frequency), per la rappresentazione e l'analisi dei testi.
- **Funzionalità principali**: I classificatori permettono di sperimentare diverse metodologie di classificazione per identificare quale approccio risulta più efficace nel contesto CTI.

### 4. Results
- I risultati degli esperimenti eseguiti.
