# Autos-Datensatz Analyse und Preisvorhersage

## Projektübersicht
Dieses Projekt analysiert den Autos-Datensatz von Kaggle, der Daten zu Autos aus den Jahren 2010 bis 2020 umfasst. Ziel des Projekts ist es, anhand von Merkmalen wie Hersteller, Modell, Baujahr, Motorgröße und Kraftstoffart den Preis von Autos vorherzusagen.

## Datenquelle
Der Datensatz wurde von der Plattform Kaggle bezogen und kann über den folgenden Link eingesehen werden:
[Autos-Datensatz 2010-2020](https://www.kaggle.com/datasets/waqi786/cars-dataset-2010-2020/data)

## Dateistruktur
Das Dataset beinhaltet folgende Spalten:
- `Make`: Hersteller des Autos (z.B. Toyota, Ford)
- `Model`: Modell des Autos (z.B. Camry, Focus)
- `Year`: Baujahr des Autos
- `Engine Size (L)`: Motorgröße in Litern
- `Fuel Type`: Kraftstoffart (z.B. Petrol, Diesel)
- `Price (USD)`: Preis des Autos in USD

## Methodik
### Explorative Datenanalyse (EDA)
Zunächst wurde eine explorative Datenanalyse durchgeführt, um Einblicke in die Verteilung und Beziehungen der verschiedenen Merkmale zu gewinnen. Dies umfasste:
- Untersuchung der Verteilung von numerischen und kategorialen Variablen.
- Analyse der Beziehungen zwischen den Features und dem Autopreis.

### Datenvorbereitung
Die Daten wurden vorbereitet, indem kategoriale Variablen mittels One-Hot-Encoding in numerische umgewandelt wurden, um sie in das Regressionsmodell einbeziehen zu können.

### Modellbildung
Es wurde ein lineares Regressionsmodell entwickelt, um die Preise basierend auf den verfügbaren Merkmalen vorherzusagen. Die Modellevaluation erfolgte anhand der Metriken Mean Squared Error (MSE) und R²-Score.

### Preisvorhersage
Ein interaktives Skript wurde implementiert, um Benutzern die Eingabe von Fahrzeugmerkmalen zu ermöglichen und den erwarteten Preis basierend auf dem trainierten Modell vorherzusagen.

## Ergebnisse
Die Ergebnisse der Modellbewertung und die Genauigkeit der Vorhersagen wurden dokumentiert. Die Effektivität des Modells wurde durch Vergleich der vorhergesagten Preise mit den tatsächlichen Werten bewertet.

## Technologien
- Python
- Pandas, NumPy für Datenmanipulation
- Scikit-learn für Modellbildung und Vorhersagen
- Jupyter Notebook als Entwicklungsumgebung

## Ausführung
Um dieses Projekt auszuführen, stellen Sie sicher, dass Sie Python und die erforderlichen Bibliotheken installiert haben. Das Notebook kann dann über Jupyter Notebook geöffnet und ausgeführt werden.

## Lizenz
Dieses Projekt ist lizenziert unter der MIT Lizenz. Details finden Sie in der LICENSE Datei.
