# 3D-Drucker

```admonish info title="Wer kennt sich hier aus?"
Danilo, Nici, Raphi N
```

Seit Anfang 2015 haben wir einen 3D Drucker, den Ultimaker 2+. Hier eine
kurze Anleitung, wie man diesen verwendet.

Inhalt:

<!-- toc -->

## 3D-Modelle

### Herunterladen

Falls du ein fixfertiges 3D-Modell herunterladen möchtest, bieten
folgende Websites eine riesige Auswahl

- <https://www.thingiverse.com/>
- <https://grabcad.com/library>
- <https://cults3d.com/>

Auf https://www.hongkiat.com/blog/download-free-stl-3d-models/ findest
du eine Liste mit weiteren 3D-Modell-Websites.

### Selber machen

Du kannst dir auch mit einer CAD-Software ein eigenes Modell erstellen.
Für Anfänger ist dabei vor allem <https://www.tinkercad.com/>
empfehlenswert. Ansonsten hier eine Liste mit weiteren kostenlosen
3D-CAD-Tools:

- <https://www.tinkercad.com/> (Webbasiert, Englisch)
- <https://www.onshape.com/> (Webbasiert, sehr mächtiges CAD, die Grundfunktionen sind gratis)
- <https://www.blender.org/> (Windows / Mac / Linux, Mehrsprachig, sehr mächtig aber steile Lernkurve)
- <https://www.openscad.org/> (Windows / Mac / Linux, Modelle werden mit Code generiert)

m diese Programme zu lernen, gibt es auf Youtube häufig sehr gute
Tutorials und Lernvideos.

Hier noch eine ausgezeichnete Ressource mit Tipps zum Designen für den
3D-Druck:
<https://support.3dverkstan.se/article/38-designing-for-3d-printing>

## Materialien

Für die Art von 3D-Drucker wie der Ultimaker einer ist, werden primär
drei Materialien verwendet: PLA, ABS und PET.

**PLA** besteht aus biologischen Materialien wie Maisstärke, Zuckerrohr
oder Tapioka-Wurzeln. Es ist in industriellen Anlagen kompostierbar.
Gegenüber ABS bietet es tiefere Schmelztemperaturen sowie weniger
Warping (Verkrümmung). Es ist allerdings ein wenig spröder als ABS und
kann sich bei hohen Temparaturen (zB hinter der Windschutzscheibe im
Auto im Hochsommer) leicht verformen. Im Coredump verwenden wir
bevorzugt PLA.

**ABS** wird auf Öl-Basis hergestellt. ES ist das selbe Material, wie
für Lego verwendet wird. Es ist etwas stärker als PLA und weniger
spröde. Es weist aber auch etwas mehr Warping auf. Dem kann man mit der
Beheizten Plattform des Ultimakers etwas entgegenwirken.

**PET** kennt ihr von den Flaschen. Es weist eine hohe Schlagfestigkeit
auf. Für einfacheren 3D-Druck ist es häufig gemischt mit anderen
Stoffen, z.B. [PETG (mit
Glykol)](https://filamentworld.de/3d-druck-wissen/was-ist-petg/).

Und hier ein ausführlicherer Material-Vergleich:
<https://support.3dverkstan.se/article/28-material-guide>

Auf Google findet man noch viele weitere Ressourcen.

## Slicen

Wenn man ein 3D-Modell hat, muss man dieses zuerst für den Druck
aufbereiten. Es wird dabei in Schichten aufgeteilt (das sogenannte
Slicing). Zudem kann man in diesem Schritt die Druck-Parameter wie
Temperatur, Schichtdicke, Geschwindigkeit etc. festlegen.

Das Slicing kann mit Cura durchgeführt werden. Du kannst es hier für
Windows, Linux und macOS herunterladen:
<https://software.ultimaker.com/> Cura unterstützt diverse
Import-Formate, die am meisten verbreiteten sind STL und OBJ.

Bei den Einstellungen gilt, ausprobieren bis man weiss was gut
funktioniert. Bei der Schichtdicke ergibt 0.2 mm gute Resultate in
Entwurfsqualität, bei 0.1mm kann man bereits kaum mehr die einzelnen
Schichten erkennen.

## Drucken

Mit Cura kannst du eine `.gcode`-Datei exportieren. Diese kopierst du
einfach auf die SD-Karte des Ultimakers. Du findest die SD-Karte links
neben dem Display.

Bitte erstelle im Hauptverzeichnis einen Ordner mit deinem Namen, damit
kein Chaos entsteht.

Dann kannst du im Print-Menu dein File auswählen und den Druck starten.

Abfälle und Ausschuss, welcher beim Druck entsteht, kannst du in der
Plastikbox neben dem Drucker hinterlegen.

## Abrechnen

Die Preisliste findest du neben dem 3D-Drucker an der Wand. Abgerechnet
wird pro Gewicht des resultierenden Drucks (inkl. Support), die
Druckzeit ist darin inbegriffen.

In der Materialkiste findest du eine Küchenwaage. Wäge bitte damit dein
ausgedrucktes Objekt und lege das Geld in die Kasse. Das Gewicht sollte
jeweils auf die nächsten 5 Gramm aufgerundet werden.

## Material wechseln

Um das Material zu wechseln, drücke im Menu auf dem LCD auf "Material"
und dann auf "Change". Befolge die Anweisungen auf dem Display.

## Troubleshooting / Tipps

Falls du Probleme mit der Druckqualität hast, ist der
[Visual Troubleshooting Guide](https://support.3dverkstan.se/article/23-a-visual-ultimaker-troubleshooting-guide),
der [Print Quality Troubleshooting Guide](https://www.simplify3d.com/support/print-quality-troubleshooting/),
der [All3DP Troubleshooting Guide](https://all3dp.com/common-3d-printing-problems-3d-printer-troubleshooting-guide/)
oder der [Getting Better Prints](https://support.3dverkstan.se/article/30-getting-better-prints)-Post
eine hervorragende Resource.
Auch die [Knowlede Base](https://ultimaker.com/en/support/knowledge) von
Ultimaker ist super.

Wenn der Druckkopf verstopft ist, solltest du (mit entsprechender
Vorsicht) die [Atomic
Method](https://support.3dverkstan.se/article/10-the) durchführen.
