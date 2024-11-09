# Erstes LaTeX Dokument

Hier lernst du, wie

- ein LaTeX Projekt aufgebaut ist
- man ein LaTeX Projekt in Kapitel und Unterkapitel unterteilt
- man in LaTeX ein Inhaltsverzeichnis erstellt
- man in LaTeX Bilder einfügt
- man in LaTeX die Textgröße und Textfarbe ändert

## Aufbau eines LaTeX Projekt

LaTeX Projekte sind grob aufgeteilt in "Präambel" und Hauptteil. 

### Präambel

In der Präambel kann man grundlegende Eigenschaften des Projekts definieren (Papiergröße, Art des Projekts, Breite der Ränder, Schriftart) und Pakete einbinden. Das Einbinden von Paketen ermöglicht es einem z.B. Bilder einzufügen oder Mathesymbole zu verwenden. Wenn sich ein LaTeX Projekt nicht so verhält wie man erwartet, kann es daran liegen, dass man das benötigte Paket nicht in der Präambel eingebunden hat.

Das Gute ist, dass Overleaf sich automatisch darum kümmert, dass das Dokument in der Präambel schon definiert wird und essentielle Pakete bereits eingebunden sind. Dadurch kann man sich direkt auf den Hauptteil und eigentlichen Inhalt des Projekts fokussieren.

### Hauptteil

Im Hauptteil fügt man alles hinzu, was man auch letzlich im PDF Dokument sieht. Also den ganzen Text, Bilder, Quellcodebeispiele usw. Da LaTeX im Gegensatz zu Word kein interaktiven Editor hat, muss man alles, was z.B. aussehen soll wie eine Überschrift, als solche definieren. Befehle beginnen in LaTeX mit `\` (backslash) und werden in Overleaf durch Farbe gekennzeichnet. Es gibt also Befehle für Überschriften, Bilder einfügen oder das Inhaltsverzeichnis. Nach dem Befehlnamen steht der Text, der die durch den Befehl definierte Eigenschaft hat, in geschweiften Klammern `{...}`.

Am Anfang muss man fast alle Befehle im Internet nachschauen (in diesem Repository sind in den Ordnern auch einige zusammengetragen). Wenn man sich mit der zeit an LaTeX gewöhnt, wird der eigene Workflow deutlich schneller und die Befehle kommen einem immer öfter als intuitiv vor.



## Aufgabe

Erstelle ein LaTeX Projekt mit 3 Kapiteln, wobei das erste Kapitel ein Unterkapital hat, welches widerum ein Unterkapitel hat. Füge anschließend nach dem Titel des Dokuemnts ein Inhaltsverzeichnis hinzu.

Füge im dritten Kapitel jeweils ein kursives, unterstrichenes und fettgedrucktes Wort hinzu, sowie eins, das sowohl fett als auch unterstrichen ist. Ändere außerdem die Farbe und Schriftgröße eines Wortes in diesem Kapitel. _Hinweis: Wenn du das Paket ```blindtext``` mit ```\usepackage{blindtext}``` einbindest, kannst du mit dem Befehl ```\blindtext``` dummy Text einfügen._

## Tipp

Hier sind einige der Befehle, die man in der Aufgabe braucht. Probier doch einfach mal aus, welche Effekte sie in LaTeX haben: `\section{}`, ` \subsection{}`, `\textbf{}`, `\textit{}`, `\tableofcontents`
