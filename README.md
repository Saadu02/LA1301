# Projekt-Dokumentation

Gruppe Schach: Sathana Suganthasri, Nicola Karrer, Carina Sutter, Ava Hassani

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 01.11.2023 | 0.0.1     | Projekt fertig erstellt.|
| 01.11.2023 | 0.0.2     | Dokumentation fertig erstellt.|


## 1 Informieren

### 1.1 Ihr Projekt

In unserem Projekt geht es um ein Schachspiel mit einer völlig anderen Figurendarstellung, die von Carina Sutter erstellt wurde. Die Spielregeln sind normal, wie bei anderen Schachspielen. Man kann hier mit zwei Personen spielen. Person Nummer 1 klickt auf eine Figur, und es werden die möglichen Züge angezeigt, wohin er seine Figur bewegen kann. Das Gleiche passiert auch bei seinem Gegner. Das Ziel ist es, den Gegner möglichst zu schlagen. Es gibt auch einen Neustart-Button, nachdem man das Spiel beendet hat.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1 | muss | Funktion | Als ein Spieler möchte ich die Möglichkeit haben, gegen meine Freunde zu spielen, damit ich schauen kann wer gewinnt. |
| 2  | muss | Qualität | Als Spieler möchte ich, dass das Spiel ein gutes Darstellung hat, damit es nicht langweilig aussieht.|
| 3  | muss | Funktion | Als ein Spieler möchte ich, das die Figuren bewegen wenn ich sie bewege, damit das Spiel auch funktioniert.|
| 4  | muss | Funktion | Als Spieler möchte ich, das die Hälfte der Figuren separat sind, damit ich sehe, welche Figuren mir gehören und die andere Hälfte den Gegner gehören.|
| 5  | muss | Funktion | Als Spieler möchte ich, dass das Spiel an das Schachregel orientiert, damit es wirklich nach Schachspiel ist.|
| 6  | muss | Funktion | Als Spieler möchte ich, dass die Figuren unterschiedliche Eigenschaften/Bewegung haben, damit das Spiel interessanter wirkt.|
| 7 | muss| Funktion| Als Spieler möchte ich, wenn ich den Gegners Figur geschlagen habe, dass Figur auch verschwindet, weil ansonsten weiss man nicht wer gewonnen hat.|
| 8 | muss | Funktion| Als Spieler möchte ich, dass die Felder grün angezeigt werden, wenn ich ein Figur klicke, damit ich weiss in welche richtig mein Figur bewegen kann.|
| 9 | muss | Funktion | Als Spieler möchte ich, nach dem ich das Spiel fertig gespielt habe, neu gestartet wird, damit ich das Spiel noch einmal spiele.|



### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Spiel startet | Person 1 klickt ein Figur und bewegt sie. | Gegner ist dran.|
| 3.1  | Spiel startet | Person 1 klickt ein Figur und wählt auf ein grünes Feld. | Figur bewegt sich.|
| 5.1  | Spiel startet | Person 1 klickt den Turm (Zombie mit violette Hose und Erwachsen aussieht).| Der Turm kann nur Horizontal und Vertikal bewegen. |
| 6.1  | Spiel startet | Person 1 klickt den Bauer (Zombie mit violette Hose und wie ein Kind aussieht.)| kann nur zwei Schritt vorwärts bewegen.|
| 7.1 | Spiel läuft | Person 1 klickt seine Figur auf den Gegner seine Figur. | Gegners Figur verschwindet.|
| 8.1 | Spiel startet | Person 1 klickt sein Figur. | Wege werden in grün angezeigt.|
| 9.1 | Spiel beendet | Person 1 klickt Restart. | Das Spiel wird neu gestartet.|
| 9.1  | Spiel beendet | Person 1 klickt Exit. | Das Spiel schliesst.|

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A | 13.09.2023 | Nicola | für Zwei Spieler erstellen | 45min |
| 2.A | 13.09.2023 | Carina | Darstellung/ Design | 2 x 45min |
| 3.A | 18.10.2023 | Ava & Nicola | Figuren Bewegung | 50 min|             |
| 4.A | 18.10.2023 | Ava & Sathana | Zwei Untersciedlichkeit der Figur | 20 min | |
| 5.A | 18.10.2023 | Sathana | Schachregel | 60 min|
| 6.A | 01.11.2023 | Sathana | Figuren Eigenschaften | 70 min |
| 7.A | 01.11.2023 | Nicola | Figuren verschwindet, nach dem sie geschlagen wurde.| 90min |
| 8.A | 01.11.2023 | Sathana | man klickt eien Figur und es werden die Richtungen  in grün angezeigt. | 45 min|
| 9.A | 01.11.2023 | Nicola | Restart button | 45 min |

Total: 9



## 3 Entscheiden

Schachspiel in Unity und Visual Studio.

Wir möchten Unity näher kennenlernen und uns mit Game-Design vertraut machen. Ursprünglich dachten wir, dass Schach ein gutes Beispiel für Game-Design ist, weil es viele Möglichkeiten bietet, es zu gestalten. Allerdings haben wir später beschlossen, mit Winforms in Visual Studio zu programmieren, da es für uns zeitlich schwierig wurde und nicht ausreichend Zeit zur Verfügung stand.


## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  | 20.09.2023 | Nicola | 45 min | 2x 45min |
| 2.A  | 01.11.2023 | Carina | 2x 45min |12x 45min |
| 3.A  | 18.10.2023 | Ava & Nicola | 50min | 3x 45min |
| 4.A  | 18.10.2023 | Ava & Nicola | 20min | 2x 45min|
| 5.A  | 18.10.2023 | Sathana | 60min | 2x 45min |
| 6.A  | 01.11.2023 | Sathana | 70min | 3x 45min |
| 7.A  | 01.11.2023 | Nicola | 90min | 2x 45min |
| 8.A  | 01.11.2023 | Sathana | 45min | 50min |
| 9.A  | 01.11.2023 | Nicola | 45min | 3x 45min |



## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 01.11.2023 | OK | Sathana |
| 3.1  | 01.11.2023 | OK | Sathana |
| 5.1  | 01.11.2023 | OK | Sathana |
| 6.1  | 01.11.2023 | OK | Sathana |
| 7.1  | 01.11.2023 | OK | Sathana |
| 8.1  | 01.11.2023 | OK | Sathana |
| 9.1  | 01.11.2023 | OK | Sathana |
| 9.1  | 01.11.2023 | OK | Sathana |


Das Spiel wurde im HP Windows 11 Pro sowie auch asus vivobook Windows 11 getesten und funktioniert fehlerfrei.

