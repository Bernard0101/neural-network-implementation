
# Implementazione di una Rette Neurale da Zero in Puro Python

Questo progetto è una dimostrazione pratica dell'implementazione di una rete neurale **da zero** utilizzando solo Python e NumPy, senza librerie esterne dedicate all machine learning. Il progetto è stato creato per applicare concetti di machine learning, matematica avanzata, e programmazione in Python.

## 1. Conoscenze Utilizzate

Il progetto copre tre principali aree di conoscenza:
- **Funzionamento delle reti neurali**: Capire come una rete neurale apprende tramite il forward pass, backpropagation, e aggiornamento dei pesi.
- **Concetti matematici**: Principalmente calcolo differenziale (derivate) e algebra lineare (matrici e prodotti).
- **Python e le sue librerie**: Uso di Python e librerie come NumPy per gestire matrici, vettori e operazioni numeriche avanzate.

## 2. Struttura del Codice

Il progetto è organizzato in diversi file che implementano la rete neurale e i relativi componenti:

- **`NeuralNetwork.py`**: Il file principale che contiene l'architettura della rete e i suoi componenti. È suddiviso in tre classi:
  1. **Architettura della rete**: Implementa gli strati della rete neurale, inclusi input layer, hidden layer e output layer.
  2. **Funzionamento della rete**: Include tre metodi principali:
     - **Forward Pass**: Propaga i dati in avanti attraverso la rete.
     - **Calcolo della perdita**: Utilizza funzioni di perdita come MSE.
     - **Backward Pass**: Implementa la backpropagation per aggiornare i pesi.
  3. **Allenamento della rete**: Una classe separata che gestisce il ciclo di allenamento della rete neurale, utilizzando l'algoritmo di Stochastic Gradient Descent (SGD).

- **`Perceptron.py`**: Un'implementazione di un Perceptron, il modello di base di una rete neurale, con i suoi metodi e funzioni.
- **`function.py`**: dove tissono tutte le funzione e algoritmi matematici utilizati.
- **`Dataset_Legge_Di_Coulomb`**: Il dataset utilizzato per addestrare la rete neurale. Il dataset contiene informazioni sopra la formula fisica di forza elettrica, dove la forza elettrica e inversamente proporzionale alla distanza
- **`VisualizzareDatti.py`**: il file che costroi gli grafici, e possibilita di fare la splorazione dei dati permetendo di avere insight sull stesso

## 4. Funzionalità Future

Queste sono alcune idee che potrei aggiungere in futuro:
- Supporto per altre funzioni di attivazione (Sigmoid, Tanh).
- Integrazione di altre tecniche di ottimizzazione (es. Adam).
- Visualizzazione delle prestazioni della rete tramite grafici di loss e accuratezza.


