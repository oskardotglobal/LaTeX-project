# Erstes LaTeX Dokument

Hier lernst du, wie

- ein LaTeX Projekt aufgebaut ist
- man ein LaTeX Projekt in Kapitel und Unterkapitel unterteilt
- man in LaTeX ein Inhaltsverzeichnis erstellt
- man in LaTeX Bilder einfügt
- man in LaTeX die Textgröße und Textfarbe ändert

## Aufbau eines LaTeX Projekt

LaTeX Projekte sind grob aufgeteilt in "Präambel" und Hauptteil. In der Präambel kann man grundlegende Eigenschaften des Projekts definieren (Papiergröße, Art des Projekts, Breite der Ränder, Schriftart) und Pakete einbinden. Das Einbinden von Paketen ermöglicht es einem z.B. Bilder einzufügen oder Mathesymbole zu verwenden. Wenn sich ein LaTeX Projekt nicht so verhält wie man erwartet, kann es daran liegen, dass man das benötigte Paket nicht in der Präambel eingebunden hat.

Das Gute ist, dass Overleaf sich automatisch darum kümmert, dass das Dokument in der Präambel schon definiert wird und essentielle Pakete bereits eingebunden sind.

## Aufgabe

Erstelle ein LaTeX Projekt mit 3 Kapiteln, wobei das erste Kapitel ein Unterkapital hat, welches widerum ein Unterkapitel hat. Füge anschließend nach dem Titel des Dokuemnts ein Inhaltsverzeichnis hinzu. _Hinweis: Hierfür ist nur ein Befehl nötig._

Füge im zweiten Kapitel ein Bild hinzu, welches du z.B. auf https://unsplash.com/ gefunden hast.

Füge im dritten Kapitel jeweils ein kursives, unterstrichenes und fettgedrucktes Wort hinzu, sowie eins, das sowohl fett als auch unterstrichen ist. Ändere außerdem die Farbe und Schriftgröße eines Wortes in diesem Kapitel. _Hinweis: Wenn du das Paket ```blindtext``` mit ```\usepackage{blindtext}``` einbindest, kannst du mit dem Befehl ```\blindtext``` dummy Text einfügen._
