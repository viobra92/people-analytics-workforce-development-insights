# 📊 People Analytics: Workforce-Struktur, Fluktuation und Kompetenzrisiken

## 🎯 Projektübersicht

Dieses Projekt wurde im Rahmen meiner Weiterbildung im Bereich **Data Analytics & Power BI** erstellt.

Ziel der Analyse ist es, Zusammenhänge zwischen **Fluktuation**, **Workforce-Struktur** und potenziellen **Kompetenzrisiken** sichtbar zu machen. Neben klassischen HR-Kennzahlen wurden zusätzliche **Skill Cluster** und **Future Skills** modelliert, um die Analyse um eine strategische Kompetenzperspektive zu erweitern.

Die Analyse basiert auf dem Datensatz **IBM HR Analytics Employee Attrition & Performance** von Kaggle (_Quelle: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset?resource=download_).

## 🔧 Datenaufbereitung & Modellierung

Für die Analyse wurden:

- Datentypen geprüft und angepasst
- Zentrale KPIs und Measures in DAX erstellt
- Kategorien für Zufriedenheit und Work-Life-Balance aufbereitet
- Jobrollen zu übergeordneten Skill Clustern zusammengefasst
- Future Skills modelliert und den Rollen zugeordnet

### Wichtige KPIs

- 👥 Headcount
- 🔄 Fluktuationsrate
- 💰 Durchschnittliches Monatseinkommen
- 🎓 Durchschnittliche Trainings pro Jahr

## 📈 Analysebereiche

### 1️⃣ Executive Overview

- Überblick über die Organisationsstruktur
- Headcount, Einkommen und Trainingsaktivitäten
- Fluktuation nach Rollen und Abteilungen
- Erste Identifikation kritischer Bereiche

### 2️⃣ Attrition Drivers

Analyse möglicher Einflussfaktoren auf Fluktuation:

- ⏰ Überstunden
- ⚖️ Work-Life-Balance
- 😊 Jobzufriedenheit

### 3️⃣ Workforce Structure

- Verteilung der Mitarbeitenden auf Skill Cluster
- Vergleich von Einkommen, Fluktuation und Mitarbeiterzahl nach Rolle
- Identifikation zentraler Kompetenzbereiche

### 4️⃣ Competency Risks

- Fluktuationsraten innerhalb der Skill Cluster
- Analyse ausgewählter Future Skills
- Identifikation potenzieller Kompetenzrisiken

## 🔍 Zentrale Erkenntnisse

### Vertrieb zeigt die höchsten Fluktuationsraten

- Die Rolle **Sales Representative** weist die höchste Fluktuationsrate im Datensatz auf.
- Auch die Vertriebsabteilung ist überdurchschnittlich stark betroffen.

### Überstunden zeigen den stärksten Zusammenhang

- Mitarbeitende mit Überstunden weisen eine deutlich höhere Fluktuationsrate auf als Mitarbeitende ohne Überstunden.

### Zufriedenheit und Work-Life-Balance spielen ebenfalls eine Rolle

- Niedrige Jobzufriedenheit geht mit erhöhter Fluktuation einher.
- Der Zusammenhang ist jedoch weniger eindeutig als beim Faktor Überstunden.

### Konzentration auf wenige Kompetenzbereiche

- Die Workforce konzentriert sich auf einige dominante Skill Cluster.
- Besonders große Bereiche sind:
  - Commercial Excellence
  - Technical Operations
  - Research & Innovation

### Potenzielle Kompetenzrisiken

- Vertriebsnahe Future Skills wie **Digital Sales Tools** und **Customer Analytics** zeigen erhöhte Risikowerte.
- Die Analyse ermöglicht eine erste Risikobetrachtung möglicher Kompetenzverluste.

---

## 🚀 Ausblick

Mögliche Erweiterungen des Projekts:

- Detailliertere Kompetenzmodelle mit Skill Levels
- Analyse von Karrierewegen und interner Entwicklung
- Erweiterung um Zeitreihenanalysen
- Untersuchung von Talent- und Nachfolgerisiken
- Entwicklung prädiktiver Modelle zur Vorhersage von Fluktuations- und Kompetenzrisiken
