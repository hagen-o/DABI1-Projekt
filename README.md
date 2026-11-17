# DABI1-Projekt

Gruppe 4: Nicolas Breitner, Joshua Maile, Pascal Ganal, Hagen Oberacker

## Notebook starten

Python 3.11 oder neuer verwenden. Im Projektordner unter Windows/PowerShell:

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
```

[Notebook Abgabe.ipynb](./Notebook%20Abgabe.ipynb) in VS Code oder Jupyter öffnen,
den Python-Interpreter aus `.venv` als Kernel auswählen und alle Zellen von oben
nach unten ausführen. Das Arbeitsverzeichnis muss dieser Projektordner sein,
damit die relativen Pfade nach `data/` stimmen. In VS Code werden die Erweiterungen
Python und Jupyter benötigt; eine Aktivierung der virtuellen Umgebung per
PowerShell-Skript ist für die obigen Befehle nicht nötig.

Die Pakete und Versionsbereiche stehen in [requirements.txt](./requirements.txt).
Die Prüfung wurde mit Python 3.14, pandas 3.0 und statsmodels 0.14 durchgeführt.
Andere Versionen innerhalb der angegebenen Bereiche wurden nicht einzeln geprüft.

## Daten und Bearbeitungsstand

Benötigt werden die zehn CSV-Dateien `orders`, `customers`, `items`, `sellers`,
`reviews`, `products`, `categories`, `service_observation`, `pilot_support` und
`service_experiment` im Unterordner [data/](./data/). `payments` und `geolocation`
sind laut Aufgabe optional und werden im aktuellen Notebook nicht eingelesen.
Die Rohdateien bleiben unverändert; die Bereinigung erfolgt im Notebook.

Das Notebook enthält die Datenvorbereitung, erste Data Stories und berechnete
Antworten auf 3.1 a/b für den ersten Meilenstein. Noch offene Teilaufgaben,
Dashboard und PDF-Annahmen sind am Ende des Notebooks aufgeführt. Ein
Power-BI-Projekt und die abschließende Dashboard-Dokumentation sind noch offen.

Die externe eigene Projektversion wurde hinsichtlich Tabellenübersichten,
Schlüsselkonflikten, Lieferstatus und Plausibilitätsprüfungen abgeglichen.
Die wichtigsten KI-Beiträge und noch fachlich zu prüfenden Annahmen stehen
direkt im Notebook.

## Quelle und Lizenz

Olist / André Sionek: [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce),
für die Lehrfallstudie aufbereitet und ergänzt.
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
Eigene Änderungen: die im Notebook dokumentierte Aufbereitung und Analyse.
