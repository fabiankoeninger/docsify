## Einstieg in Captivate

### Bevor es losgeht

#### Fehlermeldung bzgl. Bildschirmauflösung beheben

Es sollte gleich zu Beginn getestet werden, ob die Bildschirmaufnahme innerhalb von Captivate funktioniert. Sollte es nicht funktionieren, kann man den Fehler wie folgt beheben:

*Wichtig hierbei ist, dass die Person eine Adminberechtigung für Änderungen innerhalb von Windows besitzt.*

Öffne **Notepad** als Administrator. Anschließend kannst du innerhalb von **Notepad** auf den Pfad deiner Captivate Installation (meist *C:\Program Files\Adobe\Adobe Captivate 2019 x64*) gehen und dort die Datei *AdobeCaptivate.ini* öffnen. Ändere innerhalb von **Notepad** den folgenden Wert: `DpiAwareness = 1`

#### Captivate als Administrator öffnen

Captivate hat leider den Ruf, dass es gerne mal abstürzt und dadurch auch wertvolle Zeit verloren gehen kann. Es gibt nicht die *eine* Lösung aber Wege, wie man Captivate etwas stabiler machen kann.
Eine davon ist, Captivate als Administrator zu öffnen. Hierfür benötigt man allerdings entsprechende Berechtigungen, welche man als normaler Windowdsnutzer meist nicht hat. Daher ist für folgende Schritte die Hilfe der IT Abteilung notwendig.

Gehe in den Ordner deiner Captivate Installation (Bsp. *C:\Program Files\Adobe\Adobe Captivate 2019 x64*)

Rechtsklick auf die Datei *AdobeCaptivate.exe*

Gehe auf `Eigenschaften > Kompatibilität > Als Administrator öffnen`

Mit dieser Einstellung startest du von nun an Captivate jedesmal als Administrator, wodurch das Programm zumindest etwas stabiler funktionieren sollte.

### Die ersten Schritte

#### Projekt öffnen

Falls du das WIKA Template verwenden möchtest, ist der einfachste Weg, eine Kopie der wika_template.cptx Datei zu erstellen und diese zu öffnen. Alternativ kannst du auch ein neues Projekt innerhalb von Captivate erstellen. Falls du die Schaltflächen und Interaktionen aus dem Template verwenden möchtest, ist es wichtig, dass das Projekt die gleiche Auflösung (1020x624) hat. Diese kannst du unter `Custom` anpassen.
Sobald das neue Projekt erstellt worden ist, kannst du unter `Themes > Auswählen` das WIKA Theme auswählen. Dafür musst du zuvor die `wika_Theme.cptm` herunterladen.

#### Backup Datei erstellen

Gleich zu Beginn ist es sinnvoll, einige grundlegende Einstellungen zu machen.
Gehe auf `Bearbeiten > Eigenschaften`
Dort solltest du sicherstellen, dass die Option `Backup Datei erstellen` aktiviert ist. Wie bereits erwähnt, kann es durchaus vorkommen, dass Captivate unerwartet abstürzt und wertvolle Arbeit verloren geht. Durch die Backup Datei kann in den meisten Fällen der letzte Stand abgesichert werden.

> **Tipp:** Die Backup Datei wird unter dem gleichen Pfad, wie das restliche Projekt gespeichert und erhält die Endung `.cptx.bak` bzw. `.cptx.cpbackup`. Um die Datei in Captivate zu öffnen, kannst du einfach die zusätzliche Endung entfernen, sodass nur .cptx stehen bleibt.

#### Cache leeren

Unter `Bearbeiten > Eigenschaften` findest du außerdem die Option `Cache leeren`.
Sobald du mit einem neuen Projekt beginnst und ein vorheriges komplett abgeschlossen ist, empfiehlt es sich diese Option zu nutzen, da über die Zeit viel Speicher dafür anfallen kann.

#### Eigenen Arbeitsbereich einrichten

Auch unter `Bearbeiten > Eigenschaften` kannst du die Option `Eigenen Arbeitsbereich einrichten` aktivieren. Anschließend musst du Captivate schließen und wieder öffnen, damit die Änderung wirksam wird.
Durch den eigenen Arbeitsbereich kannst du nun festlegen, welche Fenster angezeigt werden. Unter `Fenster` kannst du die jeweiligen Fenster, welche für dein aktuelles Projekt relevant sind auswählen. Anschließend kannst du oben rechts auf `Classic` klicken und mit der Option `Neuer Arbeitsbereich` die aktuelle Auswahl speichern.

#### Projekt speichern und teilen

Es ist wichtig, dass Captivate Projekt immer nur vom lokalen Laufwerk geöffnet werden. Stelle daher sicher, dass sich die .cptx Datei vollständig heruntergeladen auf deinem lokalen Laufwerk befindet und öffne sie erst dann.
Wenn du dein aktuelles Projekt speicherst, erhältst du eine .cptx Datei, welche auch nur von Captivate geöffnet werden kann. Falls du dein Projekt mit Kollegen, die kein Captivate installiert haben, musst du dein Projekt exportieren und veröffentlichen, was später besprochen wird.

Falls du die .cptx Datei für die Bearbeitung mit Kollegen teilen möchtest, kannst du dein Projekt speichern und **wichtig** in Captivate schließen. Erst im Anschluss sollte die .cptx Datei versendet oder auf einen Server abgelegt werden.

### Die Benutzeroberfläche

#### Zeitleiste

Ein sehr zentrales und wichtiges Element innerhalb von Captivate ist die Zeitleiste. Mit der Zeitleiste kannst du bestimmen, wann, wie lange und in welcher Reihenfolge Elemente auf der Folie angezeigt werden sollen.

Das unterste Element (sofern du kein Audio eingebunden hast, dazu später mehr) ist die komplette Folie. Du hast hier die Option die Folie komplett auszublenden (*Auge*) oder für die Bearbeitung zu sperren (*Schloss*). Wenn du mit der Maus ans rechte Ende des Balkans gehst, kannst du hier auch die Zeitlänge der Folie anpassen.

Oberhalb der Folie findest du alle Elemente, welche sich auf der Folie befinden. Das Symbol links gibt an, um welche Elementart es sich handelt. Die wichtigsten sind:

**Blaue Textbox** = Textbox.
**Gelber Stern** = Grundform (Kreis, Viereck, Pfeil, Stern, etc.)
**Blau-weißes Bildicon** = .JPEG oder .PNG Bild
**Blaue Kugel** = SVG Datei (Vektorgrafik)

Jede Elementart hat unterschiedliche Eigenschaften, welche weiter unten behandelt werden.

Mit Hilfe des *Auge* können Elemente aus- und eingeblendet werden.

> **Wichtig**: Dies betrifft nur die Ansicht in der Bearbeitung, das Element wird im Training dennoch zu sehen sein.

Mit dem *Schloss* können Elemente für die Bearbeitung gesperrt werden. Einmal Klicken sperrt das Verschieben des Elements, es kann aber weiterhin angeklickt und bis auf die Position bearbeitet werden. Zweimal Klicken sperrt das Element komplett und kann somit auch nicht ausgewählt werden.
Durch das Klicken auf die jeweiligen Symbole werden alle Elemente ein-/ausgeblendet bzw. ge-/entsperrt.

Ganz unten lässt sich die angezeigt Länge der Folie anpassen. Sofern die Folie kurz ist, empfiehlt es sich den Regler ganz nach rechts zu setzen, bei längeren Folien kann der Regler weiter nach links gesetzt werden.

Jedes Element wird in der Zeitleist mit einem blauen Balken dargestellt. Mit Hilfe des Balkens kann Dauer, Anfang und Ende des Elements bestimmt werden. Mit der Maus lässt sich der Balkan bewegen und an den beiden Enden kann die Länge bestimmt werden.

> **Tipp:** Sofern mehrere Elemente zur gleichen Zeit angezeigt werden sollen, kann der Playhead an die entsprechende Stelle gesetzt und mit `STRG+L` die Elemente synchronisiert werden.

Die Reihenfolge in der Zeitleiste gibt auch die Reihenfolge der Elemente auf der Folie vor. Elemente, die in der Zeitleiste ganz unten stehen, sind auch auf der Folie ganz unten.

#### Eigenschaften

Am rechten Rand befinden sich das Fenster `Eigenschaften`, falls es dort nicht sein sollte, kannst du es über `Fenster > Eigenschaften` öffnen.

Die Eigenschaften beziehen sich immer nur auf das ausgewählte Element, sofern kein Element ausgewählt ist, beziehen sich die Eigenschaften auf die komplette Folie.

##### Eigenschaften Folie

Bei den Eigenschaften der Folie lässt sich im ersten Feld der Name der Folie eintragen, dieser wird auch später bei der Erstellung des Menüs verwendet.
Rechts davon befinden sich Einstellungen für die Tab-Reihenfolge und Barrierefreiheit.
Mit Tab-Reihenfolge kann festgelegt werden, welche Schaltflächen in welcher Reihenfolge bei der Bedienung mit der Tab-Taste angesteuert werden.
Mit Barrierefreiheit kann zusätzlicher Text angegeben werden, welcher über spezielle Screenreader abgespielt werden kann. Aktuell unterstützt aber nur Internet Explorer den Funktionsumfang der Option Barrierefreiheit.

Unterhalb des Titel Feldes lässt sich das Theme für die Folie bestimmen. Es empfiehlt sich, das gleiche Theme für das komplette Projekt zu nutzen.

Unterhalb der Theme Option kann man das Layout der Folie ändern. **Achtung**, sofern bereits Inhalt auf der Folie ist, kann sich die Darstellung bei Änderung des Layouts ändern.

In der unteren Hälfte gibt es noch die drei Optionen `Style` `Aktionen `und` Optionen`.
Mit `Style` lässt sich das Hintergrundbild ändern. Änderungen bezüglich Qualität sollte immer für das gesamte Projekt angepasst werden und wird später beim Thema Veröffentlichung näher erläutert.
`Aktionen` ist ein größeres Thema, auf das wir ebenfalls später näher eingehen.
Und bei `Optionen` kann eine Audiodatei hinzugefügt werden, was ebenfalls später noch näher behandelt wird.

##### Eigenschaften Textbox

Der Objektname für Elemente (Bsp. *Text_Caption_277*) ist immer eindeutig und wird automatisch vergeben, kann bei Bedarf aber verändert werden.

Der Objektstatus kann für verschiedene Zwecke verwendet werden und wird später näher erläutert.

Mit Hilfe des Dropdowns bei `Styles` kann das Aussehen einheitlich angepasst werden.

Unterhalb von Style Name kann Schrift, Größe, Layout, etc. angepasst werden.

> **Wichtig**: Sobald der Text verändert worden ist, erscheint ein + vor dem Stil Name. Dies bedeutet, dass der ursprüngliche Stil verändert wurde. Der neue Stil kann über die Schaltfläche rechts von Stil Name neu angelegt werden. **Achtung**, falls die Option `Änderungen für bestehenden Stil übernehmen` ausgewählt wird, werden auch auf allen anderen Folien der entsprechende Stil überschrieben.

Unter `Optionen` lässt sich zum einen eine Audiodatei hinzufügen (wird später noch näher behandelt), sowie Position und Größe der Textbox bestimmen.

##### Eigenschaften Formelement

Die Eigenschaften einer Form ist sehr ähnlich zur Textbox.
Zusätzlich lässt sich hier noch die Form, Füllfarbe, Rand und Deckkraft besitmmen.
Durch Doppelklick innerhalb der Form lässt sich auch direkt ein Text einfügen, wodurch die Eigenschaften mit zusätzlichen Optionen erweitert werden.
Die restlichen Optionen sind identisch zur Textbox.

##### Eigenschaften Bild

Bei einem Bild kann ich zum einen das Bild austauschen, indem ich auf den Dateiname klicke und ein anderes Bild auswähle, welches bereits innerhalb des gleichen Projekts verwendet wird oder ein neues Bild importieren.
Mit der Option `Ausgewählte Farbe transparenz machen` kann zum Beispiel ein weißer Hintergrund entfernt werden. Dazu kannst du auf das Dropdown daneben klicken, den Eyedropper auswählen und auf die entsprechende Fläche innerhalb des Bildes klicken. Stelle sicher, dass `Alpha` auf 0% steht.

> **Tipp**: Wenn du das Seitenverhältnis beim größer oder kleiner ziehen, nicht verändern möchtest, kannst du einfach `Shift` gedrückt halten, während du die Größe des Bildes änderst.

Die restlichen Optionen sind identisch zu den vorherigen Elementarten.

#### Timing

Auch bei der Option Timing beziehen sich die Einstellungen auf das ausgewählte Element. Sofern kein Element ausgewählt worden ist, beziehen sich die Einstellungen auf die komplette Folie.

##### Timing Folie

Die Timing Optionen für die gesamte Folie ist recht überschaubar. Hier kann ich zum einen die Länge der Folie bestimmen und Art des Übergangs.

##### Timing Textbox, Formen, Bild, etc.

Sobald eine beliebiges Element ausgewählt wird, sehe ich einige Optionen mehr. Bei der Einstellung `Anzeigen für` gibt es drei Option. Bei der Option `Bestimmte Zeit` kann ein Zeitwert eingetragen werden. Option `Rest der Folie` bedeutet, dass das Element bis ans Ende der Folie angezeigt wird.

> **Wichtig:** Nur mit dieser Option bleibt das Element auch nach Ablauf der Zeitleiste noch stehen. Sofern die Folie eine Länge von bspw. 3 Sekunden hat und das Element ebenfalls eine spezifische Länge von Sekunden, wird das Element nach drei Sekunden ausgeblendet, während die Folie noch angezeigt wird, bis der Nutzer auf **Weiter** klickt. Mit `STRG + E` kann man einem oder gleich mehrere Elemente die Option `Bis ans Ende zeigen ` vergeben.

Mit der Option `Effekte` können Elemente animiert werden. Die Animationen erscheinen zusätzlich als roter Balken in der Zeitleiste und können auch dort bearbeitet werden.

Mit der letzten Option `Übergang` können Elemente langsam ein- und ausgeblendet werden.

#### Bibliothek

In der Bibliothek befinden sich alle Objekte, wie Audiodateien, Bilder, Video, usw., welche zuvor in das Projekt eingefügt worden sind.

**Das erste Ordner Smybol** von links ermöglicht es, die Bibliothek eines anderen Projekts zu öffnen und Dateien über Drag&Drop einzufügen.

Mit **dem zweiten Ordner Symbol** mit dem Pfeil nach rechts lassen sich Dateien in das Projekt importieren.

Mit **dem dritten Ordner Symbol** können Dateien aus dem Projekt exportiert werden.

Sofern ein Objekt ausgewählt ist, kann es mit dem **Stift Symbol** bearbeitet werden. Je nach Art können die Dateien mit unterschiedlichen Applikation oder direkt innerhalb Captivate bearbeitet werden.

Mit **dem fünften Symbol** von links lassen sich die Eigenschaften der ausgewählten Datei anzeigen.

**Das sechste Symbol** zeigt an, an welcher Stelle, also in welcher Folie die Datei verwendet wird.

Sofern eine oder mehrere Dateien in einem anderen Programm verändert worden sind und mit gleichem Namen und unter dem gleichen Pfad abgelegt wurde, können die Dateien mit **dem siebten Symbol** automatisch upgedatet werden.

**Das achte Symbol** zeigt alle nicht genutzten Dateien an. Sobald man mit der Bearbeitung fertig ist und das Projekt mit weiteren Personen geteilt werden soll, empfiehlt es sich, mit dieser Option nach nicht genutzten Dateien zu suchen und diese mit **dem letzten Symbol** zu löschen.
