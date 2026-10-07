# Sabines Gassirunde

Ein kleines Browser-Minispiel: Sabine geht mit ihrem Hund Bello im Park spazieren
und muss den anderen Hunden ausweichen.

## Spielen

`index.html` im Browser öffnen – keine Installation nötig.

- **Steuerung:** Handy: Finger irgendwo auflegen und ziehen (wie ein Trackpad); Tastatur: Pfeiltasten / WASD
- **Pause:** P oder Tippen auf das Pause-Symbol oben rechts
- 🦴 Leckerli = +50 Punkte, ❤️ = ein Leben zurück
- Wird Sabine oder Bello angerempelt, geht ein Leben verloren (3 Leben)
- Je länger der Spaziergang, desto schneller und frecher werden die anderen Hunde

## Endgegner: Die Nachbarn mit den 3 Zäunen

Nach 100 m (danach alle 450 m) stehen die beleidigten Nachbarn hinter ihren drei Zäunen
(Zaun 1 Lattenzaun, Zaun 2 Jägerzaun, Zaun 3 Maschendrahtzaun) und behaupten, Bello würde
in ihren Garten machen.

- Grüne **Kotbeutel** einsammeln: Sabine wirft jeden als Beweis, dass sie immer aufräumt,
  gegen den vordersten Zaun.
- Jeder Zaun hat **3 Zaun-Punkte** (bei jedem weiteren Besuch +1). Ein Treffer kostet 1 Punkt.
- Fallen alle drei Zäune, geben die Nachbarn auf: +1000 Punkte und alle Leben werden aufgefüllt.
- Die Nachbarn werfen **Beschwerdebriefe**, ab Zaun 2 auch **Gartenzwerge**, und spritzen später
  mit dem **Gartenschlauch** (die blinkende blaue Spalte warnt vorher).

---

# Rollbrett Underground 3D (`skate/index.html`)

Ein 3D-Skate-Spiel im Stil der alten Street-Skate-Spiele (Three.js, eine einzige HTML-Datei).
Zwei Minuten Session in einem Hafen-Skatepark mit Quarterpipes, Funbox, Treppe mit Handläufen,
Kickern, Ledges, Rails und einem Mega-Kicker.

- **Tricks:** Ollie, Flip-Tricks (Kickflip, Heelflip, Pop Shove-It, Varial Kickflip, 360 Flip),
  Grabs (Indy, Nosegrab, Tailgrab, Melon, Method), Grinds (50-50, Nosegrind, 5-0, Boardslide, Crooked),
  Manual und Nose Manual, Drehungen in der Luft (Frontside/Backside 180, 360, 540 …).
- **Quarterpipes:** schnell reinfahren für Vert-Airs; Sprung an der Kante gibt extra Höhe.
- **Combos:** Punkte aller Tricks × Anzahl der Tricks. Mit Manual landen hält die Combo am Leben,
  wiederholte Tricks bringen weniger Punkte. Quer landen oder Flip nicht fertig = Bail.
- **Spezial-Leiste:** füllt sich mit Tricks; wenn sie leuchtet, gehen Spezial-Tricks
  (Ghetto Bird, Darkslide, Casper) und die Balance ist leichter.
- **Freak Out:** nach einem Bail Sprung hämmern für Trostpunkte.
- **Ziele:** 10.000 / 30.000 Punkte, S-K-A-T-E, 5er-Combo, 3 s Grind, 360er-Drehung, Treppen-Gap, geheimes Video-Tape.
- **Steuerung:** Tastatur (Pfeile, Leertaste, J, L, I, O, P) oder am Handy (quer) virtueller Stick + Trick-Buttons.
- Braucht beim Start Internet (Three.js und Schriften kommen vom CDN).
