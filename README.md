# 3D-Drucker (CoreXY-Konversion)


Dieses Projekt ist der Umbau eines 3D-Druckers auf Basis des Tronxy Crux 1.

Der ursprüngliche Drucker verwendete eine klassische bed-slinger-Kinematik, bei der sich das Druckbett entlang der Y-Achse bewegt. Im Rahmen dieses Projekts wurde die gesamte mechanische Struktur überarbeitet und auf eine CoreXY-Kinematik umgestellt.

Der Hauptgrund für diesen Umbau war die Reduzierung der bewegten Masse sowie die Verringerung von Vibrationen und Resonanzen. Dadurch sollen bessere dynamische Eigenschaften und eine höhere Druckgeschwindigkeit bei gleichzeitig stabiler Druckqualität erreicht werden.

Das Projekt konzentriert sich vor allem auf die mechanische Konstruktion und die saubere Strukturierung der Baugruppen im CAD.

CAD-Modell ansehen: https://a360.co/40W8220

---

*Projektziele*

- Reduzierung der bewegten Masse
- Minimierung von Vibrationen und Resonanzen
- Verbesserung der Dynamik des Systems
- Umstellung auf CoreXY-Kinematik

---

*Systemübersicht*

Der Drucker ist in mehrere funktionale Baugruppen unterteilt:

- Frame (Rahmen)
- CoreXY_System (Riemensystem für X/Y)
- X_Axis
- Y_Axis
- Z_Axis
- Extruder
- Build_Plate
- Electronics (in Entwicklung)

---

*Kinematik*

Es wird eine CoreXY-Kinematik verwendet.

Dabei steuern zwei Schrittmotoren über ein Riemensystem die Bewegung in X- und Y-Richtung. Dieses Konzept ermöglicht eine geringere bewegte Masse und sorgt für stabilere Bewegungen, insbesondere bei höheren Geschwindigkeiten.

(CoreXY-Schema kann hier ergänzt werden)

---

### Mechanischer Aufbau

*Rahmen*
- Aluminiumprofil 2020

*Führungen*
- Linearschienen MGN12H (300 mm, 350 mm, 400 mm)
- Rundwellen 8 mm (4 × 350 mm)
- Linearlager LM8UU (4 Stück)

*Antrieb*
- GT2-Zahnriemen
- GT2-Riemenscheiben

*Z-Achse*
- Schraube T8 (350 mm)
- T8-Mutter
- Kupplung

## CAD-Struktur

Das CAD-Modell wurde in Autodesk Fusion 360 erstellt und klar in Baugruppen strukturiert:
