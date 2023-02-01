# Analyse der Verspätungen bei Pendlerverbindungen
Die Verspätungen auf den wichtigsten Pender Verbindungen sollen analysiert werden. In unsere Analyse wurden die Monate Juni bis November 2022 berücksichtigt.

Die Erkenntnisse aus der Analyse wurden am XX.XX.XXX [auf den Tamedia Newsportalen publiziert](https://www.tagesanzeiger.ch "Artikel Tamedia").

Die Analyse findet in zwei Teilen statt:

1. Auslesen der relevanten Verbindungen aus den Rohdaten (R-Script)
2. Analysieren und Aufbereiten dieser Verbindungen (R-Script)

Es wurden Daten aus dem Open-Transport-Data Portal verwendet: https://opentransportdata.swiss/de/dataset/istdaten.

# 1. Auslesen der relevanten Verbindungen
--> R-Script "[SBB_Verspätung_git.Rmd](SBB_Versp%C3%A4tung_git.Rmd)"
Daten müssen zuerst aus dem Open Data Archiv der SBB heruntergeladen und entpackt werden. 
https://opentransportdata.swiss/de/ist-daten-archiv/
Das Skript sucht nun alle relevanten Verbingungen und speichert diese wiederum in einem CSV file (ein file pro Tag).


# 2. Analysieren der Verbindungen
--> R-Script "[SBB_Analyse_git.Rmd](SBB_Analyse_git.Rmd)"
