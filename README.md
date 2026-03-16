# IRNLP Project

Un progetto completo di **Natural Language Processing (NLP)** che esplora diverse tecniche di elaborazione del linguaggio naturale, dall'analisi semantica alla generazione di testo con modelli di intelligenza artificiale su temi legati alla salute mentale.

## Descrizione del Progetto

Questo progetto implementa un'analisi comprensiva di NLP con le seguenti componenti principali:

- **Clustering Semantico**: Raggruppamento di testi basato su similarità semantica
- **Sentiment Analysis**: Analisi del sentimento e delle emozioni nei testi
- **Classificazione di Risposte**: Categorizzazione automatica di risposte testuali
- **Generazione di Risposte**: Creazione di risposte intelligenti utilizzando modelli avanzati
- **Fine-tuning di Modelli**: Adattamento di modelli pre-allenati per compiti specifici

## Struttura della Repository

### Notebook Principali

#### 1. **`1_nlp-clustering-semantico-sentiment-analysis.ipynb`**
Primo notebook che implementa:
- Analisi semantica di testi
- Clustering basato su similarità coseno
- Sentiment analysis per identificare emozioni positive/negative/neutre
- Visualizzazioni dei risultati

#### 2. **`2_nlp-classificazione-risposte.ipynb`**
Notebook dedicato alla classificazione:
- Preprocessing e tokenizzazione dei dati
- Training di un modello classificatore
- Valutazione delle performance
- Metriche di classificazione (accuracy, precision, recall, F1-score)

#### 3. **`3_nlp-generazione-risposte-senza-finetuing.ipynb`**
Generazione di testo con modelli pre-allenati:
- Utilizzo di modelli base per la generazione di risposte
- Test senza fine-tuning
- Confronto di diverse strategie di generazione

### Notebook di Fine-tuning

#### 4. **`gemma3-finetuning.ipynb`**
Fine-tuning del modello Gemma3:
- Preparazione del dataset
- Configurazione dei parametri di training
- Fine-tuning per compiti specifici
- Salvataggio del modello adattato

#### 5. **`llama-finetuning.ipynb`**
Fine-tuning del modello Llama:
- Setup dell'ambiente per Llama
- Training personalizzato
- Ottimizzazione dei iperparametri
- Evaluazione dei risultati

#### 6. **`qwen-finetuning.ipynb`**
Fine-tuning del modello Qwen:
- Implementazione avanzata di fine-tuning
- Analisi dettagliata dei risultati
- Tecniche di ottimizzazione
- Esperimenti comparativi

### Analisi dei Risultati

#### 7. **`risposte_modelli_post_finetuning.ipynb`**
Analisi comprensiva delle risposte generate:
- Confronto tra modelli fine-tuned
- Valutazione qualitativa delle risposte
- Metriche di performance
- Visualizzazioni comparative

## Tecnologie Utilizzate
- **Librerie NLP**:
  - Hugging Face Transformers
  - NLTK
  - spaCy
  - scikit-learn
- **Modelli**:
  - Gemma3
  - Llama
  - Qwen
- **Visualizzazione**: Matplotlib, Seaborn, Plotly

## Come eseguire l'analisi
Esegui i notebook in ordine:

- Inizia con il notebook 1 per l'analisi semantica
- Prosegui con il notebook 2 per la classificazione
- Continua con il notebook 3 per la generazione base
- Seleziona uno o più notebook di fine-tuning
- Consulta l'ultimo notebook per l'analisi comparativa

## Configurazione e Iperparametri
I parametri principali possono essere configurati direttamente nei notebook:
- Learning rate
- Batch size
- Numero di epoch
- Temperatura di generazione
- Max token length
