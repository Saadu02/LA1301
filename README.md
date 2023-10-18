# Projekt-Dokumentation

Gruppe Schach: Sathana, Nicola, Carina, Ava

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|       | 0.0.1   | ✍️ Jedes Mal, wenn Sie an dem Projekt arbeiten, fügen Sie hier eine neue Zeile ein und beschreiben in *einem* Satz, was Sie erreicht haben. |
|       | ...     |                                                              |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

Schach spiel in unity und Visual Studio Code.

Wir möchten Untiy näher kennenlernen und in Kontakt kommen mit Game-Design. Wir haben uns gedacht, dass Schach ein gutes Beispiel ist für Game-Design, weil man da viele Möglichkeiten hat es zu gestalten.
### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    | Ich kann mit meinen Freunden spielen. | Funktion | Als ein Spieler möchte ich die Möglichkeit haben, gegen meine Freunde zu spielen. |
| 2  | kann gutes Design geniessen | Qualität | Als Spieler möchte ich ein gutes Design geniessen.|
| 3  | kann gute Gestalltung haben | Qualität | Als ein Spieler möchte ich, dass das Programm eine gute Darstellung hat, damit es nicht Langweilig aussieht.|
| 4  | Alle Figuren können sich Bewegung | Funktion | Als ein Spieler möchte ich, das man die figuren bewegen kann schieben kann, damit ich beim spielen schieben kann.|
| 5  | Alle Figuren müssen verschiedene Farben haben | Funktion | Als Spieler möchte ich, das es zwei verschiedene Figuren also Zwei Farben hat, damit ich unterscheiden kann, welche Figur zu wem gehört.|
| 6  | Der Aufbau muss normal sein | Funktion | Es sollte ein normalen Aufbau eines Schachspieles haben.|
| 7  | Die Eigenschaften müssen normal sein | Funktion | Jede Schachfigur hat die Eigenschaften wie beim normalen Schach.|
|8| Figuren nehmen| Funktion| Als Spieler möchte ich, dass die Figuren, wenn sie gefahren sind und eine andere Figur geschlagen haben, dass diese Figur vom Brett verschwindet und in meinen Count geht. |
|9| Count| Qualität| Als User möchte ich, dass jedes Mal wenn ich eine Figur geschlagen habe, diese in meinen Count gelangt, damit ich sehen kann wieviele Figuren vom Gegner ich schon geschlagen habe.|


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Spiel startet | klickt auf eine Figur | Figur wird ausgewählt |
| 2.1  | Figur wurde ausgewählt | User klickt auf ein beliebigs Feld | Figur wird dorthin bewegt |
| 3.1  | Figur wurde ausgewählt | User klickt auf ein Feld auf das die Figur sich nicht bewegen kann | Figur wird nicht bewegt |
| 4.1  | Figur wird auf ein Feld gezogen | Spieler 1 setzt Spieler 2 in Schach | Schach wird angezeigt |
| 5.1  | Der König kann sich nicht mehr auf ein Feld bewegen wo er nicht im Schach ist | | Schachmatt wird angezeigt |

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme

✍️Fügen Sie hier ein Use Case-Diagramm mit mindestens 10 Anwendungsfällen ein; und einen PAP.

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  | 13.09.2023 | Carina | Design | 2x 45min |
| ...  |       |           |              |               |
| ...  |       |           |              |               |
| ...  |       |           |              |               |
| ...  |       |           |              |               |
| ...  |       |           |              |               |
| ...  |       |           |              |               |
| ...  |       |           |              |               |

Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
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
