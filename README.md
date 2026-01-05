# S&P 500 Analyse - Diskrete Mathematik und Stochastik

Dieses Repository enthält die Analyse des S&P 500 Index im Rahmen des Moduls "Diskrete Mathematik und Stochastik". Das Ziel des Projekts ist die Untersuchung von Zeitreihenmodellen und Volatilitätsprognosen.

## Inhalt

Das Projekt besteht aus folgenden Jupyter Notebooks:

### 1. `ARIMA.ipynb`
Dieses Notebook befasst sich mit der Modellierung des S&P 500 Kursverlaufs mithilfe von ARIMA-Modellen (AutoRegressive Integrated Moving Average).
- **Ziele:** Untersuchung der Stationarität, Parameterbestimmung und Prognose der Zeitreihe.
- **Methoden:** Differenzierung, ACF/PACF-Analyse, ARIMA-Fitting.

### 2. `garch_analysis.ipynb`
Dieses Notebook führt eine Volatilitätsanalyse unter Verwendung eines GARCH(1,1)-Modells (Generalized AutoRegressive Conditional Heteroskedasticity) durch.
- **Ziele:** Modellierung der bedingten Varianz und Analyse von Volatilitätsclustern.
- **Methoden:** Renditeberechnung, Fitting des GARCH(1,1)-Modells, Visualisierung der Volatilität.

## Voraussetzungen

Um die Notebooks auszuführen, wird eine Python-Umgebung mit folgenden Bibliotheken benötigt:

- Jupyter Notebook / JupyterLab
- pandas
- matplotlib
- numpy
- statsmodels
- arch (für GARCH-Modelle)

## Nutzung

1. Klonen Sie dieses Repository.
2. Installieren Sie die Abhängigkeiten.
3. Öffnen Sie die Notebooks in Jupyter:
   ```bash
   jupyter notebook
   ```
4. Führen Sie die Zellen nacheinander aus, um die Analysen zu reproduzieren.