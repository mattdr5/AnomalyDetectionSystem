# AnomalyDetectionSystem - Corso di Reti Geografiche: Struttura, Analisi e Prestazioni

## Descrizione del Progetto
Il progetto si concentra sulla creazione di un sistema avanzato per rilevare attività dannose nel traffico di rete, con l'obiettivo di proteggere le reti da accessi non autorizzati e comportamenti dannosi, considerando il crescente aumento delle minacce informatiche. Il sistema si basa su una metodologia di apprendimento metrico profondo, originariamente combinando autoencoder e reti di triplette, tratta dal paper "Autoencoder-based deep metric learning for network intrusion".

Questo progetto è stato sviluppato come parte dell'esame del corso di Reti Geografiche: Struttura, Analisi e Prestazioni per il programma di Laurea Magistrale in Informatica presso l'Università degli Studi di Salerno, in collaborazione col prof.Zaccagnino e la prof.ssa Delfina Malandrino.

Il dataset utilizzato è il KDDCUP99, un ampio insieme di dati progettato per valutare i sistemi di rilevamento delle intrusioni nelle reti informatiche.

## Obiettivi del Progetto

L'obiettivo principale del processo di evoluzione del sistema è stato apportare modifiche mirate al modello proposto nel paper di riferimento, cercando di migliorarne le prestazioni complessive. Gli obiettivi perseguiti includono:

- Utilizzo di una singola rete Siamese: utilizzando la funzione di perdita contrastive loss su coppie 
- Riaddestramento degli autoencoder
- Cambiamento nel sistema di rilevazione: adattamento del sistema di rilevazione all'utilizzo della contrastive loss 

## Installazione

Questo progetto è stato sviluppato utilizzando Python 3.10.12. È consigliato utilizzare Google Colab per eseguire gli esperimenti. Ecco come puoi eseguire il progetto su Google Colab:

1. Esporta la cartella principale del progetto nel tuo Google Drive.
2. Esegui il mount del tuo Google Drive utilizzando il seguente codice:

```python
from google.colab import drive
drive.mount('/content/drive')
```
3. Spostati nella cartella principale del progetto utilizzando il comando cd seguito dal percorso della cartella. Ad esempio:
```bash
cd /content/drive/MyDrive/path_to_your_project
```
4. Divertiti!