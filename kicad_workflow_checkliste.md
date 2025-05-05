
# 🧩 KiCad-Workflow: Von Schaltplan bis Gerber (Checkliste)

## 🧭 1. Projekt anlegen
- [ ] Neues Projekt erstellen (Datei > Neues Projekt)
- [ ] Projektname und Speicherort festlegen

## 🧮 2. Schaltplan erstellen
- [ ] Eeschema öffnen
- [ ] Bauteile einfügen (Taste `A`)
- [ ] Verbindungen mit `W` ziehen
- [ ] Power-Flags (`PWR_FLAG`) für GND, VCC etc. setzen
- [ ] Netznamen mit Labels (`L`) vergeben

## 🏷️ 3. Bauteile zuweisen
- [ ] Schaltplan annotieren (Werkzeuge > Schaltplan annotieren)
- [ ] Footprints zuweisen (Werkzeuge > Bauteilen Footprints zuweisen)
- [ ] Optional: 3D-Modelle prüfen

## 📤 4. Netzliste erzeugen und ins PCB übernehmen
- [ ] Elektrische Prüfung (ERC) ausführen
- [ ] Netzliste generieren
- [ ] PCB-Editor (Pcbnew) öffnen
- [ ] Netzliste importieren / aktualisieren

## 🧱 5. PCB platzieren
- [ ] Platinenumriss auf Edge.Cuts zeichnen (z. B. 100x50 mm)
- [ ] Bauteile platzieren (Drag & Drop, `M`)
- [ ] Bauteile drehen (`R`), spiegeln (`F`)

## 🔗 6. Leiterbahnen routen
- [ ] Manuell routen mit `X`
- [ ] Vias mit `V` setzen
- [ ] GND-Plane ggf. per „Füllen“ (z. B. mit `GND`-Netz) erstellen

## 🧰 7. Maße, Bohrungen, Ecken abrunden
- [ ] Bohrungen (NPTH) platzieren
- [ ] Maße einfügen über „Maße > Abstand/Kante“
- [ ] Ecken abrunden mit „Bogen zeichnen“ auf Edge.Cuts

## 🎯 8. DRC & Validierung
- [ ] DRC ausführen und Fehler korrigieren
- [ ] Min.-Abstände und Überlappungen prüfen

## 📦 9. Gerber-Export
- [ ] Datei > Plotten > Gerber auswählen
- [ ] Wichtige Layer aktivieren: F.Cu, B.Cu, Edge.Cuts, F.SilkS etc.
- [ ] „Kompatibel mit Fertiger“ aktivieren
- [ ] Bohrdaten generieren (Excellon)
- [ ] ZIP-Archiv für Fertiger erstellen

## 👀 10. Kontrolle vor Produktion
- [ ] Gerber-Dateien mit GerbView prüfen
- [ ] Silkscreen, Bohrungen und Maße checken
