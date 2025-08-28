# Intro_to_DS
# 📊 Introduzione all'Algebra Lineare e Calcolo Scientifico con Python

Un corso pratico e interattivo per imparare i fondamenti dell'algebra lineare utilizzando Python, NumPy e Jupyter Notebook.

## 🎯 Obiettivi del Corso

Questo repository contiene una serie di notebook Jupyter progettati per introdurre studenti e sviluppatori ai concetti fondamentali dell'algebra lineare attraverso un approche pratico con Python. Il corso copre dalla configurazione dell'ambiente di sviluppo fino alle applicazioni avanzate con accelerazione GPU tramite CUDA.

## 📚 Struttura del Corso

### Capitolo 1: Introduzione e Setup
- **File:** `Capitolo 1. .ipynb`
- Configurazione dell'ambiente di sviluppo con Python e Jupyter
- Creazione e gestione di ambienti virtuali (venv)
- Introduzione teorica all'algebra lineare
- Implementazione di classi personalizzate per vettori e matrici

### Capitolo 2: Fondamenti di NumPy
- **File:** `Capitolo 2. .ipynb`
- Operazioni base con array NumPy
- Creazione e manipolazione di matrici
- Operazioni matriciali: somma, prodotto, trasposizione
- Differenze tra prodotto matriciale e prodotto di Hadamard
- Esercizi pratici progressivi

### Bonus: Applicazioni Avanzate
- **File:** `Bonus1.ipynb`
- Risoluzione di sistemi lineari con pseudoinversa di Moore-Penrose
- Visualizzazione con Matplotlib
- Introduzione a CUDA e CuPy per accelerazione GPU
- Confronto prestazioni CPU vs GPU

## 🚀 Come Iniziare

### Prerequisiti
- Python 3.8+
- Conoscenze base di matematica (algebra lineare consigliata ma non obbligatoria)

### Installazione

1. **Clona il repository:**
```bash
git clone https://github.com/OmarDernjani/Intro_to_DS.git
cd Intro_to_DS
```

2. **Crea un ambiente virtuale:**
```bash
python3 -m venv myenv
source myenv/bin/activate  # Su Linux/macOS
# oppure
myenv\Scripts\activate     # Su Windows
```

3. **Installa le dipendenze:**
```bash
pip install jupyter numpy matplotlib pandas
```

4. **Per il capitolo bonus (opzionale):**
```bash
# Verifica la versione CUDA
nvidia-smi
# Installa CuPy (sostituire XX con la versione CUDA)
pip install cupy-cuda12x
```

5. **Avvia Jupyter Notebook:**
```bash
jupyter notebook
```

### Configurazione Avanzata con ipykernel

Per collegare l'ambiente virtuale a Jupyter:
```bash
pip install ipykernel
python -m ipykernel install --user --name=myenv --display-name "Python (ML)"
```

## 📖 Contenuti Dettagliati

### Concetti Teorici Trattati
- Spazi vettoriali e proprietà dei vettori
- Operazioni matriciali fondamentali
- Sistemi di equazioni lineari
- Pseudoinversa di Moore-Penrose
- Condizioni di Moore-Penrose
- Complessità computazionale

### Tecnologie e Librerie
- **NumPy**: Calcolo scientifico e algebra lineare
- **Matplotlib**: Visualizzazione e heatmap
- **Jupyter Notebook**: Ambiente interattivo
- **CuPy**: Accelerazione GPU (opzionale)
- **CUDA**: Computing parallelo (opzionale)

### Funzionalità Pratiche
- Implementazione di classi personalizzate
- Visualizzazione matrici come heatmap
- Confronto prestazioni algoritmi
- Esempi di codice commentati
- Esercizi graduali con soluzioni

## 🔧 Esercizi e Attività

Ogni capitolo include esercizi pratici di difficoltà crescente:
- Creazione e manipolazione di matrici
- Operazioni algebriche fondamentali
- Implementazione di algoritmi personalizzati
- Analisi delle prestazioni
- Visualizzazione dei risultati

## ⚡ Prestazioni e Ottimizzazione

Il corso include una sezione dedicata all'ottimizzazione:
- Analisi della complessità algoritmica O(mn² + n³)
- Confronto CPU vs GPU
- Utilizzo di CUDA per accelerazione
- Best practices per matrici di grandi dimensioni

## 🤝 Contributi

I contributi sono benvenuti! Se hai suggerimenti, correzioni o miglioramenti:

1. Fai un fork del repository
2. Crea un branch per le tue modifiche (`git checkout -b feature/miglioramento`)
3. Commit le modifiche (`git commit -am 'Aggiunge nuovo esercizio'`)
4. Push al branch (`git push origin feature/miglioramento`)
5. Apri una Pull Request

## 📝 Licenza

Questo progetto è distribuito sotto licenza MIT. Vedi il file `LICENSE` per i dettagli.

## 🎓 Target

- Studenti universitari di ingegneria, matematica, fisica
- Sviluppatori interessati al machine learning
- Chiunque voglia apprendere l'algebra lineare con un approccio pratico
- Professionisti che necessitano di rinnovare le proprie conoscenze

## 📞 Contatti

Per domande, suggerimenti o collaborazioni:
- GitHub Issues per problemi tecnici
- Discussioni per domande generali sul corso

---

*Buon apprendimento! 🚀*
