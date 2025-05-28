# Stroke_Prediction_ML_Project
## Descrizione

Questo progetto implementa diversi modelli di machine learning per la predizione del rischio di ictus (stroke prediction) basati su due dataset clinici:
* [Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)
* [Stroke Risk Prediction Dataset based on Literature](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset), chiamato *Stroke Prediction Dataset v2*


  
L'obiettivo è classificare correttamente i pazienti in base al rischio di ictus utilizzando tecniche di preprocessing, bilanciamento del dataset e modelli di classificazione avanzati come XGBoost, CatBoost, LightGBM.

Il notebook `stroke_prediction.ipynb` contiene l'intero workflow: dalla preparazione e pulizia dei dati, all'addestramento dei modelli, fino alla valutazione e interpretazione dei risultati.

## Struttura del progetto

<font color="lightblue">**Stroke Prediction Dataset:**</font> 
* Visualizzazione del dataset
* Preprocessing dei dati
* Bilanciamento tramite SMOTEEN
* Costruzione di tre modelli dei predizione
* Grid Search con cross validation
* Commento e conclusioni

<font color="salmon">**Stroke Prediction Dataset v2**</font>
* Visualizzazione del dataset
* Preprocessing dei dati
* Costruzione di un modello XGBoost
* Troubleshooting
* Random Search con nested cross validation
* Commento e conclusioni

## Tecnologie e librerie utilizzate

- Python 3.8+
- Pandas
- NumPy
- Scikit-learn
-XGBoost
- CatBoost
-LightGBM
- Imbalanced-learn (SMOTENN)
- Matplotlib e Seaborn per visualizzazioni

## Come utilizzare il progetto

1. Clona o scarica il repository.
2. Assicurati di avere installato Python 3 e tutte le dipendenze elencate nel file `requirements.txt` (se presente). 
3. Esegui il notebook `stroke_prediction_finito.ipynb` in ambiente Jupyter Notebook,  JupyterLab o Google Colab.
4. Segui passo passo il flusso di lavoro per caricare i dati, effettuare il preprocessing, addestrare il modello e valutarlo.

## Possibili miglioramenti
Nel progetto sono suggeriti alcuni possibili miglioramenti per rendere i modelli proposti più performanti e affidabili.



