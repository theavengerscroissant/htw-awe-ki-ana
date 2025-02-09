# Notebooks

## Notebooks zum Einstieg in pandas, numpy und matplotlib

[numpy](https://colab.research.google.com/github/ageron/handson-ml3/blob/main/tools_numpy.ipynb)
[matplotlib](https://colab.research.google.com/github/ageron/handson-ml3/blob/main/tools_matplotlib.ipynb)
[pandas](https://colab.research.google.com/github/ageron/handson-ml3/blob/main/tools_pandas.ipynb)

## Notebooks zwischen den Lektüren

## Notebook 1: Grundlagen & Datenimport für Regression

### Datenimport & erste Schritte

- Laden von Beispieldatensätzen aus scikit-learn (z. B. California Housing Dataset).
- Nutzung von pandas zur Darstellung der Daten (`df.head()`, `df.info()`).
- Berechnung erster statistischer Kennzahlen mit numpy oder `df.describe()`.

### Erste Visualisierungen

- Erstellung von Histogrammen und Boxplots zur Darstellung der Feature-Verteilungen (mit matplotlib).
- Scatterplots zwischen ausgewählten Features und dem Zielwert plotten.

[Notebook 1](https://colab.research.google.com/github/theavengerscroissant/htw-awe-ki-ana/blob/main/notebooks/lecture_1_visualization.ipynb)

---

## Notebook 2: Explorative Datenanalyse (EDA) und Datenvorverarbeitung

### Detaillierte EDA

- Berechnung und Visualisierung von Korrelationen
- Identifikation von Ausreißern und fehlenden Werten

### Datenvorverarbeitung

- Umgang mit fehlenden Werten durch Imputationstechniken
- Feature Scaling: Normalisierung oder Standardisierung (z. B. mit dem `StandardScaler` aus scikit-learn).
- Aufteilung der Daten in Trainings-, Test- und Validierungsdaten

[Notebook 2](https://colab.research.google.com/github/theavengerscroissant/htw-awe-ki-ana/blob/main/notebooks/lecture_2_preparation.ipynb)

---

## Notebook 3: Training und Evaluierung von Regressionsmodellen

### Modelle im Vergleich

- Einfache lineare Regression als Baseline-Modell
- Entscheidungsbaum-Regressor oder Random Forest

### Modelltraining

- Aufteilen der Daten in Trainingsdaten und Validierungs-Sets
- Training der Modelle mithilfe von scikit-learn

### Evaluierung

- Berechnung relevanter Metriken wie RMSE, MAE, R²
- Visualisierung der Ergebnisse durch Scatterplots (Vorhersagen vs. tatsächliche Werte)

[Notebook 3](https://colab.research.google.com/github/theavengerscroissant/htw-awe-ki-ana/blob/main/notebooks/lecture_3_regression.ipynb)

---

## Notebook 4: Hyperparameter-Tuning und Modelloptimierung

### Hyperparameter-Tuning

- Einführung in GridSearchCV bzw. RandomizedSearchCV
- Anwendung des Tunings auf Modelle wie Entscheidungsbäume

### Kreuzvalidierung

- Einsatz von k-fold Cross Validation für stabilere Ergebnisse
- Visualisierung der Tuning-Ergebnisse, z. B. durch Heatmaps oder Linienplots, die Metriken in Abhängigkeit zu den Parametern zeigen

### Modelloptimierung

- Vergleich optimierter Modelle mit den Baseline-Modellen aus Notebook 3

[Notebook 4](https://colab.research.google.com/github/theavengerscroissant/htw-awe-ki-ana/blob/main/notebooks/lecture_4_optimization.ipynb)
