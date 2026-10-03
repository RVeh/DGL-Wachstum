# Wachstumsmodelle und Differentialgleichungen im Mathematikunterricht



## GeoGebra: Wachstumsmodelle

Die [GeoGebra-Dateien](https://rveh.github.io/DGL-Wachstum/) lassen sich direkt im Browser öffnen. Sie veranschaulichen die zufällige Neuanordnung von Niederschlagswerten und die Untersuchung von Anstiegen und Rekorden.

Alternativ können die [GeoGebra-Dateien heruntergeladen](https://github.com/RVeh/DGL-Wachstum/tree/main/geogebra) und in GeoGebra Classic geöffnet werden. Für die eingebettete Browseransicht werden eine Internetverbindung und aktiviertes JavaScript benötigt.


## Python-Notebook mit Binder ausführen

[![Mit Binder öffnen](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/RVeh/dwd-niederschlag/main?labpath=notebooks%2FDWD_Niederschlag_Ebene1.ipynb)

Binder öffnet eine ausführbare Arbeitsumgebung im Browser; eine lokale Python-Installation ist nicht erforderlich. Der Start kann mehrere Minuten dauern.

1. Binder über die Schaltfläche öffnen. Das zentrale Notebook `DWD_Niederschlag_Ebene1.ipynb` wird direkt aufgerufen.
2. Die einleitenden Erläuterungen und Einstellungen lesen. Für eine andere Messstation die Stationskennung an der vorgesehenen Stelle ändern.
3. Die Zellen der Reihe nach ausführen. Für einen vollständigen Durchlauf im Menü **Run → Run All Cells** wählen.
4. Neu erzeugte Excel-Dateien, Grafiken und Quellennachweise im Ordner `ausgabe/` der Arbeitsumgebung öffnen und bei Bedarf herunterladen.

**Binder-Sitzungen sind vorübergehend:** Änderungen am Notebook und neu erzeugte Dateien vor dem Beenden herunterladen. Sie werden nicht automatisch in diesem Repository gespeichert.

Das Notebook erläutert den Weg vom Datenzugang bis zum Urteil: Station auswählen, historische und aktuelle Daten laden, Daten prüfen und aufbereiten, Ergebnisse nach Excel exportieren, Niederschläge beschreiben und beobachtete Rekord- und Anstiegszahlen mit simulierten Vergleichsverteilungen untersuchen. Die Lernenden müssen die Verarbeitung nicht selbst programmieren; sie können die zugrunde liegenden Entscheidungen anhand der Erläuterungen und Ausgaben nachvollziehen.

### Optional: lokal ausführen

Wer mit einer eigenen Jupyter-Umgebung arbeitet, kann das Repository herunterladen und die benötigten Python-Pakete installieren:

```bash
python -m pip install -r requirements.txt
```

Anschließend `notebooks/DWD_Niederschlag_Ebene1.ipynb` in Jupyter öffnen und die Zellen der Reihe nach ausführen. Eine Jupyter-Umgebung wird hierbei vorausgesetzt; `requirements.txt` enthält die zusätzlichen Pakete für die Datenverarbeitung und Auswertung.



## Aufbau des Repositorys

```text
README.md          Orientierung und Zugänge zu den Materialien
index.html         Browseransicht der GeoGebra-Simulation
requirements.txt   Python-Pakete für das Notebook
notebooks/         Zentrales Python-Notebook
geogebra/          GeoGebra-Datei zu Wachstumsmodellen
pdf/               Artikel und PDF-Fassung des Notebooks
```
