# Clustering_Sonnenspektren
Clustering_Sonnenspektren mit verschiedenen Methoden


Dieses Projekt befasst sich mit der Analyse und Clusterung von Sonnenspektren, um Muster in den Daten zu identifizieren und die Spektren in sinnvolle Gruppen zu unterteilen.

Hauptschritte des Projekts:
1. Datenvorverarbeitung und Visualisierung:
Zunächst werden Sonnenspektren geladen, die einen bestimmten Wellenlängenbereich abdecken. Die Intensität der Spektren ist normiert. Um erste Einblicke in die Daten zu erhalten, werden zufällig ausgewählte Spektren visualisiert.

<div style="display: flex; gap: 20px;">
  <img src="https://github.com/user-attachments/assets/a232ce1b-fc1e-468d-9fa2-1266d7371d15" alt="image" width="1000"/>
</div>

2. Dimensionreduktion mittels Hauptkomponentenanalyse (PCA):
Zur Reduktion der hohen Dimensionalität der Spektrendaten wird die PCA angewendet. Diese Methode extrahiert die wichtigsten Komponenten, die den Großteil der Varianz in den Daten erklären. Dies erleichtert die spätere Clusterung und Visualisierung der Daten.

<div style="display: flex; gap: 20px;">
  <img src="https://github.com/user-attachments/assets/32ecdd78-637f-4df1-b633-bcb99357b015" alt="image" width="540"/>
  <img src="https://github.com/user-attachments/assets/df12a4f5-adf7-482a-b2a6-0ef9604f5193" alt="image" width="460"/>
</div>



3. Clusteranalyse:
Anschließend werden verschiedene Clusterverfahren (z. B. K-Means, DBSCAN) angewendet, um ähnliche Spektren zu gruppieren. Die Daten werden in den Hauptkomponenten-Raum projiziert, um die Cluster besser sichtbar zu machen und Muster in den Spektren zu erkennen.

<div style="display: flex; gap: 20px;">

  <img src="https://github.com/user-attachments/assets/20c86fdc-baab-42e8-a456-87f70a940632" alt="image" width="500"/>
  <img src="https://github.com/user-attachments/assets/1ec4f530-5fd6-4852-89b3-08a9d93384c3" alt="image" width="500"/>
</div>


Ergebnis:
Das Projekt ermöglicht eine effiziente Reduktion der Datenkomplexität und bietet einen Einblick in die Struktur und Clusterung der Sonnenspektren, was für weiterführende Analysen und Anwendungen nützlich ist.

<div style="display: flex; gap: 20px;">
  <img src="https://github.com/user-attachments/assets/06169a34-b1b7-4425-a5fd-88d416ed7eb3" alt="image" width="550"/>
</div>
