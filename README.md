# TeXstudio de_DE.badWords

## Sinn und Zweck

Zum Schreiben meiner Masterarbeit verwendete ich LaTeX mit [TeXstudio](https://www.texstudio.org/) als Editor. TeXstudio bietet eine Funktion zur Markierung "schlechter Wörter", die standardmäßig nicht aktiviert ist. Da mir in meiner Arbeit viele "schlechte Wörter" aufgefallen sind, habe ich diese Funktion aktiviert und mit einem großen Schwung an Wörtern gefüttert. Mir *persönlich* gelang es dadurch die Qualität meines Textes stark zu steigern. Da die Liste auch meinen Kommilitonen beim Verfassen ihrer Abschlussarbeiten half, entschied ich mich diese Liste zu veröffentlichen.

Die Bad Word Liste besteht aus vielen **Füllwörtern**, die weggelassen werden können, ohne den Sinn eines Satzes zu verändern. Beispiele:

 - Hier lässt sich ~~einfach~~ erkennen...
 - ... dies kann ~~also~~ dazu verwendet werden...

Zudem sind auch viele **unbestimmte Mengenangaben** (Ironie?) enthalten, um einen Hinweis zur Nacharbeitung zu liefern. Beispiele:

 - Es kann ~~manchmal~~ dazu führen, dass...
 - Es kommt daher ~~meistens~~ zum Problem...

Die Liste hat generell **keinen Anspruch auf Vollständigkeit**, auch wenn sie bereits viele -- oft pingelige -- Wörter enthält. Jede Wortmarkierung sollte daher auch **nicht blind gestrichen** werden; eine manuelle Nachprüfung ist in jedem Fall erforderlich! Die Idee ist es, dem Autor einen Hinweis auf mögliche Satzfüller zu geben.

Es fehlen wichtige Wörter? Bitte erstelle einen Pull Request! Weitere gute Hinweise für Autoren zur Textverbesserung finden sich unter: <http://www.schreiblabor.com/>.

## Installation

Für die Installation unter **Microsoft Windows** muss die Datei `de_DE.badWords` in den Ordner `C:\Program Files (x86)\TeXstudio\dictionaries`. Für **Linux** und **macOS** sollte dies analog funktionieren.

Anschließend sind folgende Einstellungen in TeXstudio unter `Optionen` > `TeXstudio konfigurieren...` > `Sprache prüfen` > `Eingebaute Grammatikprüfung` vorzunehmen:

 - **Prüfe auf "schlechte" Worte** anhaken
 - **Wortlistenverzeichnis:** `C:\Program Files (x86)\TeXstudio\dictionaries`

Grundsätzlich sollte die Bad Word Liste auch für andere LaTeX Editoren benutzbar sein. Leider fehlt mir da die Expertise; erstelle gerne einen Pull Request!

## Quellen

Neben "eigenen" Wörtern wurde die Bad Word Liste mit Wörtern aus folgenden Quellen angereichert:

- https://juttas-schreibtipps.blogspot.de/2006/07/giftliste-i-fllwrter.html
- https://juttas-schreibtipps.blogspot.de/2011/09/giftliste-iv-noch-mehr-fullworter.html
- http://www.schreiblabor.com/
