# Filament-Swatches (holudi)

Musterkarten zum Herzeigen von Filamenten und Druckplatten, 2 mm dick, mit Vertiefung für Thermo-Etiketten und Loch für Schnur/Ring (Fächer).

- `filament_swatch.py` – erzeugt alle Karten in FreeCAD (Makro oder Python-Konsole) und exportiert `.FCStd` + `.3mf` neben das Skript; Maße oben als Parameter
- `swatch-A-eckloch` – 45 × 43 mm, Etikett 40×20, Treppe 0,2–1,8 mm (9 Stufen), Dreiecksloch in der Ecke
- `swatch-A-holo` – 45 × 43 mm, Etikett 40×30 (Filament + Plattentyp), flache Unterseite für Holo-/Struktur-Platten
- `swatch-B-kompakt` – 78 × 36 mm, Etikett 40×20, 3×3-Raster 0,2–1,8 mm, Rampe 0,2–2,0 mm mit Skala, Rundloch Ø 8

## Details
- Etikettfläche: Etikett + 0,5 mm Spiel je Seite, Eckradius 2,5 mm; Tiefe 0,2 mm (A) bzw. 0,4 mm (B)
- Lochkanten oben und unten 0,4 mm Fase (45°, überhangfrei)
- Skala B: Rille je 0,2 mm Dicke = 3,5 mm Rampenlänge, lange Rillen bei 1,0 und 2,0 mm; Rillen sitzen auf der Mitte der gedruckten Stufen

## Druck
- Unterseite aufs Bett, alle Vertiefungen oben, ohne Stützmaterial
- 0,2 mm Schichthöhe (High Quality), Oberseite Monotonic Line, kein Ironing
- Holo-Platten: am besten mit schwarzem PLA Basic zeigen, zusätzlich eine helle Karte zum Vergleich