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

Core-XY-Schema ansehen Core-XY-Schema

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

---

###meine Gedanken und Entscheidungen

-Ursprünglich habe ich zwischen einem Aluminiumprofil und einem gedruckten Rahmen gewählt, da die Profile bei Amazon zu teuer waren (20-40 Euro für 2 Profile 2020 400 mm). Aber ich habe 12 Profile für 20 Euro gefunden, also war die Wahl offensichtlich.

-Die Befestigungen für ihre Verbindung waren ebenfalls teuer, und die gedruckten [Teile] bogen sich stark durch und waren zu zerbrechlich. Ich bin einen anderen Weg gegangen. Ich habe Löcher im Profil gebohrt. Zuerst 6 Millimeter bis zur Mitte und 3,2 mm durchgehend und die Profile mit M3-Schrauben verbunden. Die Verbindung war ziemlich stabil und das hat mich zufrieden gestellt.

-Ich habe die MGN12H Linearführungsschienen in unterschiedlichen Längen bestellt, weil ich bei der Bestellung zunächst falsche Maße angegeben habe. Eigentlich hätte ich 3 Stück mit jeweils 350 mm bestellen sollen, stattdessen habe ich zuerst 300 mm genommen.

Als ich gemerkt habe, dass diese Länge nicht ausreicht, habe ich mich bewusst entschieden, sie nicht zurückzugeben. Danach habe ich 2 Stück mit 350 mm bestellt, aber der Verkäufer hatte nur noch eine auf Lager. Er bot mir stattdessen eine 400-mm-Schiene zum gleichen Preis (zzgl. Versandkosten) an, was ich akzeptiert habe.

An sich ist das kein großes Problem, allerdings musste ich meine Konstruktion bereits während des Zusammenbaus anpassen, da ich beim Entwurf ursprünglich von zwei identischen Führungen ausgegangen war.
