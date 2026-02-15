# Akku-Craft Schaltpläne

Hier findest du die Schaltpläne und PCB-Layouts für das Akku-Craft Projekt.

## Übersicht

Das Projekt enthält KiCad-Dateien für die Entwicklung von Akku-Management- und Überwachungssystemen. Der Hauptschaltplan sowie ein separater Stromsensor sind enthalten.

![Schaltplan](schaltplan.png)

## Projektstruktur

```
Schaltplan/
├── Schaltplan.kicad_sch      # Haupt-Schaltplan
├── Schaltplan.kicad_pcb      # PCB-Layout
├── Schaltplan.kicad_pro      # KiCad Projektdatei
├── sensor_corrente.kicad_sch # Stromsensor Schaltplan
├── sensor_corrente.kicad_pcb # Stromsensor PCB-Layout
└── Schaltplan-backups/       # Automatische Backups
```

## Software

Das Projekt wurde mit KiCad erstellt. Empfohlen wird Version 9.x oder höher.

Download: https://www.kicad.org/

## Installation

Repository klonen und die Datei `Schaltplan/Schaltplan.kicad_pro` in KiCad öffnen.

## Komponenten

Der Hauptschaltplan befindet sich in `Schaltplan.kicad_sch`.

## Workflow

Typischer Arbeitsablauf bei Änderungen:

1. Schaltplan in KiCad öffnen und bearbeiten
2. PCB-Layout entsprechend aktualisieren
3. Design-Rule-Check durchführen
4. Gerber-Dateien für die Fertigung exportieren

## Backups

KiCad erstellt automatisch Backups im Ordner `Schaltplan-backups/`. Die ZIP-Dateien enthalten Snapshots des Projekts zu verschiedenen Zeitpunkten.
