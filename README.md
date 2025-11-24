🏠 Energie­bilanz eines Gebäudes (Django)
Webanwendung zur Berechnung der Energiebilanz eines Gebäudes auf Basis von Geometrie, U-Werten, internen Gewinnen und solaren Gewinnen.
Erstellt mit Django, Bootstrap, Chart.js sowie Light/Dark-Mode-Unterstützung.

🚀 Funktionen:
  🔧 Berechnung & Analyse
  - Heizwärmebedarf gemäß:
    Qₕ = Qᵥ + Qₜ – Qᵢ – Qₛ
  - Erfassung der Gebäudedaten:
    - Geometrie (Abmessungen, Geschosse, Raumhöhe)
    - U-Werte aller Bauteile
    - Fensterflächenanteile
    - g-Werte (solare Gewinne)
  - PV-Bilanz:
    - Gesamt-Ertrag
    - Eigenverbrauch
    - Überschuss

  📊 Diagramme & Visualisierung
    - Jahres-Energieflüsse (Balkendiagramm)
    - Solare Gewinne nach Orientierung
    - PV-Bilanzdiagramme
    - Übersichtliche Karten-Darstellung aller Ergebnisse

  🗂️ Gebäudeverwaltung
    - Gebäude speichern
    - Gebäude bearbeiten
    - Gebäude löschen
    - Gesamte Liste exportieren

  📤 Export-Funktionen
    - CSV-Export
    - Excel-Export (.xlsx)
    - PDF-Export
  
  🎨 Benutzeroberfläche
    - Vollständig responsives Design (Bootstrap)
    - Light & Dark-Mode
    - Benutzerfreundliche Navigation

🖥️ Technologien
         Bereich	                   Technologie
Backend	                     Django 5
Frontend	                   Bootstrap 5, Chart.js
Export	                     pandas, openpyxl, reportlab
Datenbank	                   SQLite
Deployment-Vorbereitung	     requirements.txt, venv

.
.
.

📦 Installation

1️. Repository klonen

<img width="636" height="100" alt="image" src="https://github.com/user-attachments/assets/6c0e56a2-571f-49d0-bd6c-72034ebe99ef" />

2️. Virtuelle Umgebung erstellen & aktivieren

<img width="632" height="98" alt="image" src="https://github.com/user-attachments/assets/dd4159b6-535c-4b38-aede-2f6f152e0cd6" />



3️. Abhängigkeiten installieren

<img width="641" height="77" alt="image" src="https://github.com/user-attachments/assets/04774daa-9acf-439a-b6e1-cab441cb62f6" />



4️. Lokalen Server starten

<img width="636" height="75" alt="image" src="https://github.com/user-attachments/assets/ebe8a693-a6c1-4097-bd21-f8ad08475e5c" />




Die App läuft dann unter:
👉 http://127.0.0.1:8000/


👥 Team / Mitwirkende

Philipp 
&
Robin 

📄 Lizenz

Das Projekt ist für Studien-/Lernzwecke erstellt.

✔️ Status

Projekt ist funktionsfähig, vollständig dokumentiert und bereit zur gemeinsamen Weiterentwicklung über GitHub.
