---
title: "Übung 1 - Import und Export von Daten in ArchivesSpace"
date: 2021-11-14
---

Milý deníčku,

ich bin etwas aufgeregt. Ich berichte Dir heute in einer neuen resp. anderen Form. Und zwar geht es darum, dass ich Dir nun nicht über die vergangene Lehreinheit erzähle,
sondern ich mache eine Übung und berichte darüber. Wie aufregend, findest Du nicht? <br>
Naja, ich bin etwas verunsichert, weil ich nicht genau weiss, wie ich das am besten mache, aber ich versuche es einfach mal. Ja?

Also, zuerst zur Aufgabe. Diese besteht aus zwei Teilen. Es geht um Import und Export von Daten. <br>
Ich habe Dir im letzten Beitrag kurz geschildert, dass wir **ArchivesSpace** installiert und angefangen haben, damit zu arbeiten. Diese Übung bezieht sich auf dieses System.

Ich beginne mit dem Import. <br>
Wie im ersten Schritt beschrieben, habe ich die Beispieldaten als *"a raw XML file"* heruntergeladen. Es gab nich wirklich irgendwo eine Funktion 'Datei herunterladen'.
Deshalb habe ich die Seite als *"Web Page, XML only"* gespeichert. <br>
Als ich sie dann versuchte zu importieren, funktionierte es nicht und ich verfiel in Panik. Zwei Mal importierte ich die Datei und beides Mal bekam ich die Rückmeldung *Job failed*. <br>
Ich versuchte mich zu beruhigen und las noch einmal den Vorgang, den ich zu tun hatte. Zum Glück fand meinen Fehler: Da es sich um eine XML Datei handelt, dachte ich, ich muss sie auch in MARCXML importieren. Ich bemerkte aber, dass das nicht stimmt, sondern ich EAD als Format auswählen sollte. Danach hat es glücklicherweise geklappt. <br>
So viel dazu. Was ich nun wirklich dokumentieren soll, ist: Ich soll die Ansicht, die sich mir danach in ArchivesSpace ergab mit der Ansicht der bei den Beispieldaten verlinkten HTML-Ansicht vergleichen. <br>
Also los gehts: Als Erstes kann ich sagen, dass ich die Übersicht auf der HTML-Seite deutlich besser finde. Der Inhalt selbst ist zum Teil ähnlich, zum Teil nicht: die Zeitdaten
stimmen nicht überein. Auf der HTML-Seite steht 1939-1969 und in ArchivesSpace 1939-1958. Das finde ich problematisch. Gerade Zeitangaben können sehr wichtig sein und die
Ungleichheit dieser lässt bei mir Verwirrung und Unsicherheit aufkommen. Die "Biographical History" ist in beiden Ansichten vorhanden. Die "Scope and Contents of the Collection" (was genau vorhanden ist), ist in der HTML-Ansicht detaillierter aufgeführt, auch mit Unterteilungen. In ArchivesSpace erfährt man dagegen nur ganz grob eine
Auflistung darüber, was es beinhaltet. Ich mache dazu ein Beispiel:

ArchivesSpace: 
![image](https://user-images.githubusercontent.com/90834630/141674675-cd5687df-f189-470b-aa30-2e30720c4df3.png)
Quelle: [localhost:8080/resources/101#tree::resource_101](localhost:8080/resources/101#tree::resource_101)


HTML-Seite: <br>
![image](https://user-images.githubusercontent.com/90834630/141674689-baa35eb1-69f5-4306-a19b-f2609c283882.png) <br>
Quelle: [https://library.syr.edu/digital/guides/a/aaie.htm](https://library.syr.edu/digital/guides/a/aaie.htm)

Die Aufgabe ist es, beide ganz grob zu vergleichen, weswegen ich nicht mehr Beispiele aufzähle. Ich kann aber allgemein festhalten, dass ich persönlich die Ansicht in HTML bevorzuge, weil sie mir unter anderem auch kompakter erscheint und ich besser den Inhalt sehe. In ArchivesSpace gibt es für mich zu viele Anmerkungen daneben und der eigentliche Inhalt resp. Text folgt erst untergeordnet in einem spearaten Feld (siehe obiges Bild).


Der zweite Teil der Übung ist ein Export. <br>
Die Datei zu exportieren funktionierte auf Anhieb. Ich musste nur beachten, dass ich das richtige Format MARCXML auswähle.
Die Aufgabe hier besteht darin, dass ich die exportierte MARCXML-Datei kurz mit den in ArchivesSpace vorhandenen Informationen vergleiche und versuche festzustellen, ob 
der Export in MARCXML verlustfrei ist. <br>
Wenn ich ganz ehrlich sein darf: Es fällt mir wirklich schwer diese beiden Ansichten zu vergleichen, weil sie so unterschiedlich sind. <br>
In der MARCXML-Datei gibt es bei jedem Feld die Zusätze *"ind1"*, *"ind2"* und *"tag"*. Ich verstehe nicht ganz, was für Informationen diese darstellen, denn in ArchivesSpace finde ich diese Angaben nicht eins zu eins wieder. Aber eigentlich soll ich sagen, ob die MARCXML-Datei verlustfrei ist. <br>
Was verloren gegangen ist, sind die "Creation Dates". In diesem Fall wäre das 1939-1958. Alle sonstigen, ich sage jetzt mal 'administrativen' Angaben über die American Association of Industrial Editors (AAIE) Records, sind meiner Meinung nach vorhanden. Auch die "Biographical History" wurde wortgetreu übernommen. <br>
Nach einem zweiten und dritten Blick auf beide Dateien komme ich zum Schluss, dass einzig die Zeitdaten fehlen. Ansonsten ist die MARCXML-Datei vollständig. <br>
Aber, um die Frage zu beantworten, nicht ganz verlustfrei.


Puh. Nun bin ich am Ende der Übung. Ich hoffe sehr, dass ich sie richtig gelöst habe resp. auch vorgegangen bin. Ich kann für mich sagen, dass ich die Übung absolvieren
konnte und auch zu Ergebnissen kam. Ob sie richtig sind, das ist eine andere Frage. <br>
Bist Du auch mitgekommen, liebes Tagebuch?


Odpočiň si a na příští setkání. <br>
tvoje Barča

