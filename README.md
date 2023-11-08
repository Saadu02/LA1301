# Projekt-Dokumentation

Gruppe Schach: Sathana, Nicola, Carina, Ava

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|       | 0.0.1   | ✍️ Jedes Mal, wenn Sie an dem Projekt arbeiten, fügen Sie hier eine neue Zeile ein und beschreiben in *einem* Satz, was Sie erreicht haben. |
|       | ...     |                                                              |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

Schachspiel in Unity und Visual Studio.

Wir möchten Untiy näher kennenlernen und in Kontakt kommen mit Game-Design. Wir haben uns gedacht, dass Schach ein gutes Beispiel ist für Game-Design, weil man da viele Möglichkeiten hat es zu gestalten. Doch später haben wir entschieden mit Winforms zu programmieren, da es sehr schwierig war und Zeitlich für uns nicht reichte. 

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    | muss | Funktion | Als ein Spieler möchte ich die Möglichkeit haben, gegen meine Freunde zu spielen, damit ich schauen kann wer gewinnt. |
| 2  | muss | Qualität | Als Spieler möchte ich, dass das Spiel ein gutes Darstellung hat, damit es nicht langweilig aussieht.|
| 3  | muss | Funktion | Als ein Spieler möchte ich, das die figuren bewegen wenn ich sie bewege, damit das Spiel auch funktioniert.|
| 4  | muss | Funktion | Als Spieler möchte ich, das die Hälfte der Figuren seperat sind, damit ich sehe, welche Figuren mir gehören und die ander hälfte den Gegner gehören.|
| 5  | muss | Funktion | Als Spieler möchte ich, dass das Spiel an das Schachregel orientiert, damit es wirklich nach SchachSpiel ist.|
| 6  | muss | Funktion | Als Spieler möchte ich, dass die Figuren unterschiedliche Eigenschaften/Bewegung haben, damit das spiel interessanter wirkt.|
| 7 | muss| Funktion| Als Spieler möchte ich, wenn ich den Gegners Figur geschlagen habe, dass Figur auch verschwindet, weil am sonsten weiss man nicht wer gewonnen hat.|
| 8 | muss | funktion| Als Spieler möchte ich, dass die Felder grün angezeigt werden, wenn ich ein Figur klicke, damit ich weiss in welche richtig mein Figur bewegen kann.|

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.



### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Spiel startet | klickt auf eine Figur | Figur wird ausgewählt |
| 2.1  | Figur wurde ausgewählt | User klickt auf ein beliebiges Feld | Figur wird dorthin bewegt |
| 3.1  | Figur wurde ausgewählt | User klickt auf ein Feld auf das die Figur sich nicht bewegen kann | Figur wird nicht bewegt |
| 4.1  | Figur wird auf ein Feld gezogen | Spieler 1 setzt Spieler 2 in Schach | Schach wird angezeigt |
| 5.1  | Der König kann sich nicht mehr auf ein Feld bewegen wo er nicht im Schach ist | | Schachmatt wird angezeigt |

### 1.4 Diagramme

✍️Fügen Sie hier ein Use Case-Diagramm mit mindestens 10 Anwendungsfällen ein; und einen PAP.

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A | 13.09.2023 | Nicola | für Zwei Spieler erstellen | 45min |
| 2.A | 13.09.2023 | Carina | Darstellung/ Dessigne | 2 x 45min |
| 3.A | 18.10.2023 | Ava & Nicola | Figuren Bewegung | 50 min|             |
| 4.A | 18.10.2023 | Ava & Nicola | Zwei unterschiedlichkeit des Figurs | 20 min | |
| 5.A | 18.10.2023 | Sathana | Schachregel | 60 min|
| 6.A | 01.11.2023 | Sathana | Figuren Eigenschaften | 70 min |
| 7.A | 01.11.2023 | Nicola | Figuren verschwindet, nach dem sie geschlagen wurde.| 90min |
| 8.A | 01.11.2023 | Sathana| man klickt ein Figur und es werden die richtungen in grün angezeigt. | 45 min|

Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  | 1.11.2023 | Carina Sutter | 2x 45min |12x 45min |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
