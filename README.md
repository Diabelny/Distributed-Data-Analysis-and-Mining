# Distributed-Data-Analysis-and-Mining-Project

La cartella progettuale è suddivisa in due folder principali contenenti i datasets e i codici  per ognuno dei quattro casi di studio: Nord, Sud, Est, Ovest del problema affrontato. Contiene inoltre un report in formato pdf dell'attività svolta.

In particolare la cartella Codes è stata suddivisa in ulteriori 4 cartelle contenenti ciascuna le logiche relative ai task conseguiti nei 4 differenti casi di studio:

- Data Understanding & Feature Extraction
- Data Preparation
- Clustering
- Classification

Il codice è stato interamente sviluppato in ambiente Spark utilizzando le principali librerie associate al modulo pyspark:

- ml -> per concatenare in apposite Pipeline attività di normalizzazione, vettorizzazione e allenamento dei modelli.
- mllib -> per applicare i principali algoritmi di Machine Learning e valutarne le performance tramite le metriche principali.
- sql -> per eseguire operazioni SQL su dati distribuiti.
 
Ulteriori librerie come Seaborn e Pandas sono state utilizzate all'occorrenza per visualizzare determinati risultati in modo appropriato.
