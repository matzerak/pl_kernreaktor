# Kernreaktor · Interaktives Physiklabor

**Wie lässt sich die Kettenreaktion in einem Kernreaktor kontrollieren?**

Eine interaktive, experimentelle Lernumgebung für den Physikunterricht der Klasse 10. Die Schülerinnen und Schüler untersuchen an einem schematischen Druckwasserreaktor, wie die Stellung der Steuerstäbe die Kettenreaktion beeinflusst und warum ein Reaktor auch nach dem Abschalten weiter gekühlt werden muss.

Die App verrät die zentralen Zusammenhänge nicht. Regler und Knöpfe sind neutral beschriftet, die Einleitung stellt nur die Leitfrage, und Erklärungen stehen eingeklappt im letzten Bereich. Die Schülerinnen und Schüler sollen durch Beobachten und Messen selbst die Wirkungskette erschließen.

Lernprodukt kann eine Betriebsanleitung für einen sicheren Reaktorbetrieb sein. Dazu werden Arbeitsblätter vorgeschlagen.

---

## Auf einen Blick

| | |
|---|---|
| Zielgruppe | Physik, Klasse 10 (Kernphysik / Energieversorgung) |
| Zeitbedarf | ca. 2 Unterrichtsstunden mit Arbeitsblatt, je nach Vertiefung mehr |
| Sozialform | Einzel- oder Partnerarbeit am iPad, Tablet, Smartphone oder Laptop |
| Technik | eine einzige Datei `index.html`, läuft offline im Browser |
| Sprache | Deutsch |

---

## Starten

1. Die Datei `index.html` auf das Gerät kopieren (z. B. per AirDrop, Lernplattform, USB-Stick oder Schulserver).
2. Die Datei im Browser öffnen. Eine Installation, ein Konto oder eine Internetverbindung sind nicht nötig.
3. Die App lädt keine externen Schriften, Bibliotheken oder Analysedienste und speichert keine Daten. Festgehaltene Messwerte gehen beim Neuladen verloren; sie lassen sich über „Messwerte drucken“ ausgeben oder abschreiben.

Für die Arbeit am Smartphone empfiehlt sich das Querformat. Auf schmalen Bildschirmen lässt sich die Anlagenzeichnung seitlich verschieben, und die Lupenansicht zeigt den Reaktorkern bildschirmfüllend.

---

## Was die Schülerinnen und Schüler sehen

**Die Reaktoranlage als Querschnitt:** Die Darstellung des Druckwasserreaktors lässt klassisch zwei Kreisläufe betrachten. Im Primärkreislauf: Reaktordruckbehälter mit Reaktorkern, Brennelementen und beweglichen Steuerstäben, Druckhalter, Dampferzeuger und Hauptkühlmittelpumpe. Im Sekundärkreislauf folgen Turbine, Generator, Kondensator, Speisewasserpumpe und Kühlturm. Primär-, Sekundär- und Kühlkreislauf sind farblich und durch die Strichart unterschieden. Das Wasser strömt sichtbar, die Turbine dreht sich, die Farbe des Primärkreislaufs folgt der Temperatur. Im Reaktordruckbehälter siedet das Wasser im Normalbetrieb nicht; Dampfblasen gibt es nur auf der Sekundärseite des Dampferzeugers.

**Die Teilchenebene im Kern:** Gleichzeitig ist im Reaktorkern eine stark vereinfachte Teilchenebene zu sehen. Schnelle Neutronen (dunkles orange) werden im Wasser zwischen den Brennstäben abgebremst und sind danach langsam (blau). Ein langsames Neutron kann einen U-235-Kern spalten; dabei entstehen zwei Spaltprodukte und zwei oder drei neue schnelle Neutronen. Andere Neutronen werden in einem Steuerstab absorbiert oder gehen verloren. Über „Ein Neutron markieren“ lässt sich ein einzelnes Neutron auf seinem Weg verfolgen; ein Statustext sagt, was mit ihm geschieht.

Beide Ebenen hängen am selben Modellzustand: Mehr Spaltungen im Kern führen gleichzeitig zu höherer Temperatur, stärkerem Dampfstrom, schnellerer Turbine und höherer Generatorleistung.

Die Anwendung ist ein **vereinfachtes physikalisches Modell** und keine technische Reaktorsimulation. Alle angezeigten Zahlen sind modellhafte Werte, was auch in der App selbst deutlich gekennzeichnet ist.

---

## Die vier Bereiche

### 01 Lernmodus – Beobachten

Die Abläufe sind bewusst verlangsamt. Einzige Einstellgröße ist die **Eintauchtiefe der Steuerstäbe** (0 % = ganz herausgezogen, 100 % = ganz eingefahren). Angezeigt werden Reaktorleistung, relative Zahl freier Neutronen, Spaltungen je 10 s im gezeigten Kernausschnitt und die Temperatur des Primärkreislaufs. Ein Zeitdiagramm zeigt den Leistungsverlauf mit markiertem Betriebsbereich von 90–110 %.

Über „Messwert festhalten“ legen die Schülerinnen und Schüler eine Messwerttabelle an, die sie für das Arbeitsblatt nutzen können. Die Beobachtungsaufträge A–C führen vom einzelnen Neutron über eine Messreihe zur ganzen Anlage.

### 02 Schnellmodus – Unter Kontrolle halten

Die Modellzeit läuft dreimal so schnell, und die Zahl der Neutronen schwankt von selbst. Ziel ist, die Leistung während eines **40-sekündigen Durchgangs** möglichst im Betriebsbereich zu halten. Die Leistung folgt einer Änderung der Steuerstäbe mit wenigen Sekunden Verzögerung, sodass vorausschauend geregelt werden muss.

Am Ende steht eine sachliche Bilanz: Zeitanteil im Betriebsbereich, höchste und niedrigste Leistung, die im Durchgang erzeugte Wärmeenergie in MWh und ob der Reaktorschutz eingreifen musste (über 150 % Leistung). Die Schwankungen sind bei allen Durchgängen gleich, damit Ergebnisse vergleichbar sind. Ranglisten oder Punkte gibt es zunächst bewusst nicht. (Kann aber den Wert der erzeugten Wärmeenergie hergestellt werden – falls interessant.)

### 03 Störfall – Störung der Kühlung

Ein didaktisches Szenario, das zu einem Druckwasserreaktor passt und kein reales Ereignis nachbildet: Die Hauptkühlmittelpumpe fällt aus. Den Schülerinnen und Schülern stehen zwei getrennte Eingriffe zur Verfügung: **Reaktorschnellabschaltung** und **Notkühlung**.

Zusätzlich angezeigt werden die Wärme aus Kernspaltung und die **Nachzerfallswärme** getrennt, der Wasserstand im Kern, der Kühlmittelstrom und ein zweites Diagramm mit der Kerntemperatur. Eine Statusleiste zeigt die Warnstufen *Normalbetrieb → Warnung → Kritischer Zustand → Kernschädigung*, ein Ereignisprotokoll hält alle Schritte fest. Als Endstufe eines völlig misslungenen Durchgangs wird eine Kernschmelze schematisch dargestellt: Brennstoff sammelt sich am Boden des Druckbehälters, freigesetzte Stoffe bleiben im Containment. Es gibt keine Explosion.

### 04 Quellen und Modell

Quellen, ausdrücklich benannte Modellgrenzen und die fachlichen Kernaussagen zum Vergleichen. Die Kernaussagen sind eingeklappt und als „erst nach dem Experimentieren öffnen“ gekennzeichnet.

---

## Didaktisches Konzept

Die App verrät die zentralen Zusammenhänge nicht. Regler und Knöpfe sind neutral beschriftet, die Einleitung stellt nur die Leitfrage, und Erklärungen stehen eingeklappt im letzten Bereich. Die Schülerinnen und Schüler sollen durch Beobachten und Messen selbst die Wirkungskette erschließen:

> Steuerstabstellung → Zahl verfügbarer Neutronen → Zahl der Kernspaltungen → Wärmeentwicklung → Reaktorleistung

Im Störfall ist die angestrebte Erkenntnis:

> Auch nach dem Beenden der Kettenreaktion muss der Reaktorkern weiter gekühlt werden.

Die App ist deshalb als Werkzeug für ein Arbeitsblatt und ein anschließendes Lernprodukt gedacht, nicht als selbsterklärendes Lernmodul.

### Möglicher Unterrichtsablauf

Erste Stunde (45'):

1. **Einstieg:** Leitfrage entwickeln, Vorwissen zu Kernspaltung und Kettenreaktion aktivieren, Vermutungen sammeln.
2. **Lernmodus (ca. 20–25 min):** Neutronen verfolgen, Messreihe zu mindestens vier Eintauchtiefen aufnehmen, Weg der Energie durch die Anlage beschreiben.
3. **Schnellmodus (ca. 10–15 min):** mehrere Durchgänge, eigene Regelstrategie beschreiben, über die Verzögerung nachdenken.
4. **Sicherung:** Wirkungskette formulieren, mit den eingeklappten Kernaussagen vergleichen, Modellgrenzen besprechen.

Zweite Stunde (45'):

1. **Einstieg:** Leitfrage weiterentwickeln/konkretisieren, Vermutungen sammeln. Ggf. erklärende Videos anschauen. 
2. **Störfall (ca. 20 min):** erst ohne Eingriff beobachten, dann mit Schnellabschaltung, dann systematisch den Zeitpunkt der Notkühlung variieren.
3. **Sicherung:** Wirkungskette formulieren, mit den eingeklappten Kernaussagen vergleichen, Modellgrenzen besprechen, Lernprodukt (Entwicklung einer Betriebsanleitung) erstellen.

Mögliche dritte Stunde (45'):

* Die SuS diskutieren zu "Pro und Contra" (Anregung dazu z.B. https://youtu.be/5aRcXyhDiuQ und https://youtu.be/m7HCKIkid2c von Breaking Lab)



### Arbeitsblattvorschlag

Im Anhang findet sich ein Vorschlag für Arbeitsblätter. 

* Die erste Seite hat sich für die erst Stunde als sinnvoll erwiesen. Damit werden die Beobachtungen strukturiert und es finden sich darauf eine Wertetabelle.
* Die zweite Seite dann für die zweite Stunde. Die Entwicklung des Lernprodukts hat bei meinen Schülerinnen und Schülern etwa 15 Minuten gedauert.



---

## Hinweise für die Lehrkraft: Was im Modell zu beobachten ist

*Dieser Abschnitt ist für die Vorbereitung gedacht und nimmt die Ergebnisse vorweg.*

**Lernmodus – Gleichgewichtswerte nach dem Einschwingen (modellhaft):**

| Eintauchtiefe | Freie Neutronen | Reaktorleistung | Temperatur Kernaustritt |
|---:|---:|---:|---:|
| 0 % | ca. 220 % | ca. 220 % | ca. 377 °C |
| 25 % | ca. 160 % | ca. 160 % | ca. 347 °C |
| 40 % | ca. 125 % | ca. 125 % | ca. 329 °C |
| 50 % | 100 % | 100 % | 316 °C |
| 60 % | ca. 75 % | ca. 75 % | ca. 303 °C |
| 75 % | ca. 19 % | ca. 19 % | ca. 275 °C |
| 100 % | 0 % | 0 % | 265 °C |

Der Zusammenhang ist gleichsinnig, aber nicht linear; nach einer Verstellung dauert es einige Sekunden, bis sich ein neues Gleichgewicht einstellt. Die angezeigten Spaltungen je 10 s sind proportional zur Neutronenzahl. Die Teilchenanimation zeigt nur wenige Teilchen stellvertretend und schwankt daher stärker als die Messanzeigen.

**Störfall – typische Verläufe** (Zeiten im Ereignisprotokoll in Modellzeit; der Störfall läuft im Modell doppelt so schnell wie die Echtzeit):

- *Kein Eingriff:* Warnung nach etwa 5 s, der Reaktorschutz schaltet bei 340 °C von selbst ab. Weil die Kühlung fehlt, verdampft dennoch das Wasser im Druckbehälter, der Kern liegt nach etwa 40 s trocken, Kernschädigung nach etwa 2 min, Kernschmelze nach etwa 4 min.
- *Nur Schnellabschaltung:* Die Spaltungswärme fällt sofort fast auf null, die Nachzerfallswärme bleibt sichtbar. Die Temperatur steigt langsamer, aber weiter; ohne Kühlung folgen dieselben Stufen später.
- *Schnellabschaltung und Notkühlung:* Wird die Notkühlung innerhalb von etwa 2½ min Modellzeit eingeschaltet, bleibt der Kern unbeschädigt, auch wenn er zwischenzeitlich trocken lag. Später eingeschaltet, sinkt die Temperatur zwar, aber die Kernschäden bleiben bestehen.

Gerade der Vergleich von „nur Schnellabschaltung“ und „Schnellabschaltung mit Notkühlung“ eignet sich, um die zentrale Erkenntnis zur Nachzerfallswärme herauszuarbeiten.

---

## Modellannahmen und Grenzen

- Alle Zahlen sind **modellhafte Werte**. 100 % steht für den Normalbetrieb des Modellreaktors.
- Der Betriebsbereich 90–110 % ist ein Zielbereich für die Aufgaben, keine reale Sicherheitsgrenze.
- Im Kern sind nur wenige U-235-Kerne und Neutronen stellvertretend gezeichnet; Bewegungen sind stark verlangsamt, die Anlage ist nicht maßstäblich.
- Modellzeit: Lernmodus 1-fach, Schnellmodus 3-fach, Störfall 2-fach gerafft. Ein realer Störfall verläuft über deutlich längere Zeiträume.
- Die Leistungsschwankungen im Schnellmodus sind vorgegeben, damit geregelt werden muss. In realen Druckwasserreaktoren wird die Leistung zusätzlich über Borsäure im Kühlwasser eingestellt.
- Die Energieangabe im Schnellmodus setzt 100 % mit 3950 MW Wärmeleistung gleich (Orientierungswert aus LEIFIphysik) und rechnet mit der Modellzeit.
- Der Reaktorschutz greift im Störfall erst spät von selbst ein, damit eigene Eingriffe möglich bleiben. Reale Anlagen schalten früher automatisch ab und besitzen mehrere voneinander unabhängige Notkühlsysteme.
- Die Temperaturschwellen der Warnstufen (330 °C Warnung, 346 °C Sieden bei ausgefallener Kühlung, 1200 °C Kernschädigung, 2200 °C Kernschmelze) sind für das Modell gewählt.
- Die Nachzerfallswärme beginnt im Modell bei etwa 5 % der Leistung und klingt danach ab (vgl. GRS-Glossar).

Die Besprechung dieser Grenzen kann selbst Teil der Sicherung sein: Was zeigt das Modell gut, was zeigt es verzerrt oder gar nicht?

---

## Quellen und fachliche Grundlage

- YouTube Videos von https://www.youtube.com/@swissnuclear8245  - dort finden sich kurze Videos zum Druckwasserreaktor und zu einzelnen Bestandteilen/Prozessen
- "Pro und Contra" – Anregung dazu z.B. https://youtu.be/5aRcXyhDiuQ und https://youtu.be/m7HCKIkid2c von Breaking Lab
- LEIFIphysik: [Druckwasserreaktor](https://www.leifiphysik.de/kern-teilchenphysik/kernspaltung-und-kernfusion/ausblick/druckwasserreaktor)
- LEIFIphysik: [Kettenreaktion](https://www.leifiphysik.de/kern-teilchenphysik/kernspaltung-und-kernfusion/grundwissen/kettenreaktion)
- LEIFIphysik: [Funktionsweise eines Kernkraftwerks](https://www.leifiphysik.de/kern-teilchenphysik/kernspaltung-und-kernfusion/aufgabe/funktionsweise-eines-kernkraftwerks)
- Gesellschaft für Anlagen- und Reaktorsicherheit (GRS), Glossar: [Reaktorschnellabschaltung (RESA)](https://www.grs.de/index.php/de/glossar/reaktorschnellabschaltung-resa)
- GRS, Glossar: [Nachzerfallswärmeleistung](https://www.grs.de/de/glossar/nachzerfallswaermeleistung)
- GRS, Glossar: [Notkühlung](https://www.grs.de/de/glossar/notkuehlung)
- Informationsportal von Bund und Ländern „Sicherheit in der Kerntechnik“: [Gestaffeltes Sicherheitskonzept](https://www.nuklearesicherheit.de/genehmigungs-und-aufsichtssystem/sicherheitskonzept/gestaffeltes-sicherheitskonzept/)

---

## Technische Hinweise

- Eine einzige HTML-Datei mit eingebettetem CSS, JavaScript und SVG, ohne externe Abhängigkeiten.
- Bedienbar mit Touch, Maus und Tastatur (Tabs mit Pfeiltasten, Regler mit Pfeiltasten oder den Knöpfen − und +).
- „Pause“ friert Animation und Messwerte ein, „Zurücksetzen“ stellt den Ausgangszustand des aktuellen Bereichs her.
- Bei eingestellter reduzierter Bewegung im Betriebssystem startet die App pausiert.

## Entwicklung und Lizenz

Den Quellcode habe ich mithilfe von ChatGPT erstellen lassen. Ausgehend von meiner didaktischen Idee habe ich die Anwendung in einem iterativen Prozess durch zahlreiche Anpassungen und Tests weiterentwickelt.

Mit der Veröffentlichung möchte ich zugleich den Quellcode zugänglich machen und zur Auseinandersetzung mit der Anwendung einladen. Die Entstehung mithilfe von KI ist für sich genommen keine Aussage über die Fehlerfreiheit oder Lizenzierung des Codes. Eine konkrete Lizenz wird in dieser Beschreibung nicht festgelegt; die Bedingungen für die Nutzung und Weiterentwicklung des Quellcodes sind gesondert im Repository anzugeben.

## Ausprobieren und Mitentwickeln

Ich freue mich über Erfahrungsberichte aus dem Unterricht, Hinweise auf Fehler und Vorschläge zur Weiterentwicklung.



---

Teil der Reihe **Physiklabor** – Entdecken. Verändern. Verstehen.
Matthias Krebs
