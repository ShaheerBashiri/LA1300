# Projekt-Dokumentation
 
Erstellt von Mohammad Shahir Bashiri

| Datum | Version | Zusammenfassung |
| --- | --- | --- |
| 6.09.2023 | 0.0.1 | Erstellung von Programm |
| 6.09.2023 | 0.0.2 | Dokumentation und Portfolio fertig |



## 1 Informieren

### 1.1 Ihr Projekt

Ein interaktives Konsolen-Zahlenratenspiel, bei dem der Spieler gegen den Computer antritt.

Dieses Projekt zielt darauf ab, ein unterhaltsames und intuitives Spiel zu erstellen, bei dem der Benutzer eine vom Computer generierte Zufallszahl erraten muss. Das Spiel bietet dem Benutzer Feedback in Form von Farben und Soundeffekten und ermöglicht es ihm, seine Fähigkeiten durch wiederholtes Spielen zu verbessern. 

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ | Beschreibung |
| --- | --- | --- | --- |
| 1 | Muss | Funktional | Als Spieler möchte ich gegen den Computer antreten, um eine Geheimzahl zu erraten. |
| 2 | Muss | Funktional | Als Spieler möchte ich Feedback erhalten, ob meine geratene Zahl zu hoch, zu niedrig oder korrekt ist. |
| 3 | Kann | Funktional | Als Spieler möchte ich sehen, wie viele Versuche ich benötigt habe, sobald ich die Zahl errate. |
| 4 | Kann | Qualität | Als Spieler möchte ich eine intuitive GUI haben, um das Spiel leicht navigieren zu können. |
| 5 | Kann | Funktional | Als Spieler möchte ich meine Punktzahl in einer Highscoreliste sehen. |
| 6 | Kann | Funktional | Als Spieler möchte ich Soundeffekte hören, wenn ich eine Zahl eingebe, sie richtig errate oder verliere. |

| TC-№ | Ausgangslage                     | Eingabe           | Erwartete Ausgabe                                                            |
|------|----------------------------------|-------------------|------------------------------------------------------------------------------|
| 1.1  | Start des Spiels, Zufallszahl = 50 | 25               | "Die gesuchte Zahl ist größer!"                                             |
| 1.2  | Zufallszahl = 50                 | 75               | "Die gesuchte Zahl ist kleiner!"                                              |
| 1.3  | Zufallszahl = 50                 | 50               | "Gratulation! Sie haben die Zahl erraten!" + Anzahl der Versuche              |
| 1.4  | Zufallszahl = 50                 | ABC              | Fehlermeldung + Aufforderung, eine gültige Zahl zwischen 1 und 100 einzugeben |
| 1.5  | Zahl wurde erraten               | "Nochmal spielen?"| Startet das Spiel erneut oder beendet es, je nach Auswahl                    |
| 1.6  | Spiel wird gestartet             | 101              | Fehlermeldung + Aufforderung, eine gültige Zahl zwischen 1 und 100 einzugeben |
| 1.7  | Spiel wird gestartet             | -5               | Fehlermeldung + Aufforderung, eine gültige Zahl zwischen 1 und 100 einzugeben |

### 1.4 Diagramme

![image](https://github.com/ShaheerBashiri/LA1300/assets/111045708/ecfd7051-b40f-4876-92a4-ef4e76cf50d4)


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| --- | --- | --- | --- | --- |
| 1.A | 6.09 | Mohammad | Implementierung des Basis-Spiels | 45' |
| 2.B | 6.09 | Mohammad | Hinzufügung von Soundeffekten und Farbanpassungen | 45' |

Total: 90'

## 3 Entscheiden

Wir haben uns entschieden, die Spiellogik zuerst zu implementieren und anschließend User-Feedback-Features wie Soundeffekte und Farben hinzuzufügen. Da es sich um ein Konsolenspiel handelt, haben wir auf eine GUI verzichtet, können dies aber in zukünftigen Versionen hinzufügen.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| --- | --- | --- | --- | --- |
| 1.A | 13.09.2023 | Mohammad | 45' | 40' |
| 2.B | 14.09.2023 | Mohammad | 45' | 50' |

## Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum   | Resultat        | Tester |
|------|---------|-----------------|--------|
| 1.1  | 13.09.23| Erfolgreich     | ich    |
| 1.2  | 13.09.23| Erfolgreich     | ich    |
| 1.3  | 13.09.23| Erfolgreich     | ich    |
| 1.4  | 13.09.23| Fehler erkannt  | ich    |
| 1.5  | 13.09.23| Erfolgreich     | ich    |
| 1.6  | 13.09.23| Fehler erkannt  | ich    |
| 1.7  | 13.09.23| Fehler erkannt  | ich    |





