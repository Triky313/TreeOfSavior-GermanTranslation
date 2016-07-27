#Tree of Savior Übersetzungsprojekt
Hier wird an einer deutschen Übersetzung für Tree of Savior gearbeitet.
<br><br>
## Wie hinzufügen?
Das hinzufügen geht ganz einfach, ihr müsst in den Installations-Ordner von ToS gehen..
<br><br>
<b>Beispiel</b>:<br>
<i>SteamLibrary\steamapps\common\TreeOfSavior\release\languageData</i>
<br><br>
<img src="http://images.akamai.steamusercontent.com/ugc/287477208212554149/E5FF5D7FFD99F8E035A5A6336B698A54DCA40F46/" alt="Bild des TreeOfSavior-Verzeichnisses">
<br>
Dort hinein die Zip/Rar-Datei entpacken, so dass ein neuer Order Deutsch neben Englisch und kr entsteht.
<br><br>
Im Spiel selbst könnt ihr dann unter Settings ganz unten die Sprache auswählen.
<img src="http://images.akamai.steamusercontent.com/ugc/287477208212568392/5D8063ADB970C2468368B384F51EF82A1A92FD5E/" alt="Bild des Einstellungs-Fensters in Tree of Savior">
<br><br>

## Warum wird nicht alles übersetzt?
Im Grunde versuche ich alles zu übersetzen. Natürlich gibt es aber Dinge, die man vielleicht nicht übersetzen sollte um nicht alles zu verkomplizieren.
<br><br>
Unter anderem habe ich mich erst einmal dazu entschlossen die Skill-Namen auf Englisch zu lassen.
<br><br>
Zum einen ist es nicht so einfach den passenden Namen zu finden. Der andere Grund ist, es gibt einige Guides im Internet welche soweit ich gesehen habe immer die englischen Namen benutzen, egal ob die Seite nun auf Deutsch ist oder nicht.
<br>
Somit muss keiner philosophieren was für einen Skill ich denn nun meine (Auch wenn das Bild des Skills noch zu sehen ist).
<br><br>
Eine andere Sache ist, die Länge eines Wortes oder Satzes. Oft ist es so, dass die deutsche Übersetzung dann +10 Zeichen mehr hat und ingame dann einfach nicht mehr gut aussieht, so dass sie z.B. über Ränder stehen.
<br><br>
Trotzdem diskutiere ich hier gerne über eine bessere Lösung. Ich bin nicht perfekt und wir werden sicherlich eine gute Lösung für alles finden.
<br><br>

## Du willst helfen?
Unterstützung und Verbesserung sind gern gesehen!
Du kannst hier gern "Pull Requests" einleiten oder Fehler melden.<br><br>
Sollte jemand keine Erfahrung mit GitHub haben und trotzdem helfen wollen, kann er/sie mir Daten per Email an triky@web.de zukommen lassen.
<br><br>
Sollte jemanden etwas nicht gefallen, der Satzbau schlecht formuliert sein, Wörter zu lang sein oder einfach irgendetwas nicht in Ordnung sein.. teilt es mir mit!
<br><br>
Ich bin gern bereit etwas zu ändern oder anzupassen. Auch ich übersehe mal etwas oder wähle nicht immer die richtigen Worte. 
<br><br>
<strong>Also, keine Scheu!</strong>
<br>
####Was wird übersetzt?####
Im Grunde versuchen wir alles zu übersetzen. Natürlich müssen wir aber auch auf die Benutzerfreundlichkeit achten.
Da ist es z.B. so, dass wir einige Sachen erst einmal gar nicht übersetzen oder nur teilweise. Folgende Regeln werden hier aufgelistet:
* Skills werden erst einmal nicht übersetzt. (Nur die Beschreibungen)
* Orte werden erst einmal nicht übersetzt.
* Gegenstände (Items) werden teilweise übersetzt. (Beispiel: Panto Sword zu Panto Schwert) Eigennamen bleiben also bestehen.

####Regeln in den .tsv-Dateien####
* Wenn ihr was übersetzt, müsst ihr darauf achten, dass zwischen der ID und des Literals der TAB-Platz bleibt, so dass alle gleichauf sein. ETC_20150317_008234**[HIER TAB]**Rezept – Moplah
* Es ist möglich Texte in mehreren Sprachen in einer Datei unter zu bringen. Diese werden dann mit einem TAB-Platz unterteilt. Dabei wird das, was im Spiel angezeigt werden soll als erstes geschrieben. Am besten wäre es, wenn man das englische dahinter belässt um weitere Korrekturen einfacher zu machen.<br>Beispiel: ETC_20150317_008234**[HIER TAB]**Preis**[HIER TAB]**Price
* Wenn texte mit Geschwungenen Klammern kommen z.B. {nl} dann müssen die immer auch wieder geschlossen werden. Achtet darauf, dass ihr nicht aus Versehen eine Klammer entfernt.
* __{nl}__ steht übrigens für NewLine also Neue Zeile. Sollte mal etwas nicht ganz in eine Zeile passen, kann man dies damit anpassen.
<br><br>

## So einfach kannst du Änderungen vornehmen!
Wenn du im Spiel selbst Literale (Zeichenketten/Text) siehst, welcher geändert werden soll, kannst du das ganz einfach tun. Dazu musst du nur eine kleine Datei in den Ordner “languageData“ hinzufügen. Das ist der Ordner, welcher auch alle Sprachordner enthält. (Englisch und kr z.B.).

Die Datei heißt <strong>editor.ini</strong> und liegt hier im Ordner TreeOfSavior-GermanTranslation mit drin. Das heißt für dich, diese Datei einfach aus dem Ordner nehmen und ein Ordner zurück wieder einfügen.

Innerhalb dieser Datei gibt es drei wichtige Zeilen.<br><br>
Zeile 1: Kann den inGame-Editor An/Ausschalten<br>
Zeile 2: Gibt die Sprache an, welche im Original angezeigt werden soll<br>
Zeile 3: Das muss den Datei-Pfad zu eurem Text-Bearbeitungsprogramm beinhalten, sonst funktioniert es nicht. In meinem Fall ist das Notepad++
<pre>Use=YES
ReferLanguage=English
CommandOption=C:\\Program Files (x86)\\Notepad++\\notepad++.exe "[Path]" -n[Line]</pre>

Ist das getan, kannst du das Spiel starten und im Spiel selbst nun bei fast jedem Text <strong>STRG+SHIFT+Linksklick</strong> machen und der Texteditor eurer Wahl wird mit der Text-Zeile die ihr ändert wollt geöffnet.

Viel Spaß.
<br><br>

## Intellectual Property Rights Ownership
Please be aware that the Intellectual Property Rights of the following, including, but not limited to, belong to IMC Games Co., Ltd: The names of any characters, NPCs, places, scenes, things, events, short phrases, short sayings and the likes that are set forth in Tree of Savior, as well as any translations or contributions from our contributors.

                                  ⓒ IMCGAMES CO., LTD. All Rights Reserved.
