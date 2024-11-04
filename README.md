# DBS Projekt

Dieses Projekt ist ein Datenbank- und Datenanalyse-Projekt, welches im Rahmen meines Studiums entstanden ist.

## Übersicht
1. [Installation](#installation)
2. [Verwendung](#verwendung)
3. [Ergebnisse](#ergebnisse)
4. [Quellen](#quellen)

## Installation

### Mit pip

```bash
pip install -r requirements.txt
```

### Mit mamba wie im Jupyter Notebook beschrieben

```bash
mamba create -n dbs python pony psycopg2 jupyterlab pandas seaborn numpy colorcet geopandas
```
### Mit Nix

1. Folge den [Nix-installations-anweisungen](https://nixos.org/download/) um `nix` zu installieren.

2. Starte die Entwicklungsumgebung aus der Datei flake.nix mit:

```bash
nix develop
```

## Verwendung

Starte Jupyter Lab mit dem folgenden Befehl:

```bash
jupyter lab
```

## Ergebnisse

### Visualisierung des Verhältnisses von Studierenden zur Gesamptbevölkerung nach Bundesland
![Plot](/media/plot01.png)

### Visualisierung der Städte in Deutschland mit dem Größten Anteil an Studierenden an der Gesamptbevölkerung
![Plot](/media/plot02.png)

## Quellen
[https://regionalatlas.statistikportal.de/](https://regionalatlas.statistikportal.de/)
