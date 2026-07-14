# Wolfswald 🐺

Ein kleines Fluchtspiel für den Browser (optimiert für iOS/Safari):
Du rennst durch einen Wald in der Dämmerung – immer wieder taucht ein Wolf auf,
jagt dich und verschwindet nach einigen Sekunden wieder. Überlebst du 5 Minuten, hast du gewonnen.

## Spielen

Einfach `index.html` im Browser öffnen – fertig. Keine Installation,
kein Build-Schritt, keine Abhängigkeiten.

## Steuerung

- **Touch (iOS):** Finger irgendwo auf den Bildschirm setzen und ziehen – der
  virtuelle Joystick erscheint dort, wo du den Finger aufsetzt.
- **Tastatur (Desktop):** WASD oder Pfeiltasten.

## Technik & Sicherheit

- Eine einzige HTML-Datei mit Vanilla JavaScript und Canvas 2D.
- **Keine Drittanbieter-Pakete, keine CDNs, keine ausgehenden Verbindungen** –
  alle Grafiken werden zur Laufzeit gezeichnet, alle Sounds per Web Audio API
  synthetisiert.
- Der Rekord wird nur lokal im Browser gespeichert (`localStorage`).
