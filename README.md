# 🎯 Breakfast Club – Darts Scoring

Zähl-Tool für Live-Darts (301/501, Single/Double Out, First to 3/5/7/9) direkt im Browser.

**▶ Öffnen:** https://demuhb.github.io/breakfast-club-darts/

## Bedienung
- Wurf = Klick aufs Board, Klick in den dunklen Außenring = Miss
- `Strg` + `Z` oder Button = letzten Wurf rückgängig (auch nach Überwurf oder Leg-Ende)
- Ein laufendes Spiel wird automatisch zwischengespeichert und kann nach einem Neuladen fortgesetzt werden

## Statistiken auf einen anderen PC übertragen
Die Historie liegt im Browser (localStorage) des jeweiligen PCs.
1. Alter PC: **Historie → Export (JSON)**
2. Neuer PC: **Historie → Import** → Datei wählen

Der Import führt zusammen: bereits vorhandene Spiele werden übersprungen, nichts wird überschrieben.
Exporte älterer Versionen (1.0 – 2.1) werden weiterhin gelesen.
