# gzgscanner 🛒

**gzgscanner** (Geld-Zurück-Garantie Scanner) ist ein spezialisierter Barcode-Scanner, der dir sofort zeigt, ob du für ein Produkt dein Geld zurückerhalten kannst. 

Einfach den Barcode scannen und direkt sehen, ob eine aktuelle **Geld-Zurück-Aktion (GZA)** vorliegt.

## Features

* **Schnell-Check:** Sofortige Überprüfung von Barcodes während des Einkaufs.
* **Visuelles Feedback:**
    * 🟢 **Grün:** Aktion gefunden! Das Produkt ist für eine Geld-Zurück-Garantie berechtigt.
    * 🔴 **Rot:** Kein Treffer. Der Barcode wurde nicht in der Datenbank der aktuellen Aktionen gefunden.
* **Einfache Handhabung:** Kamera draufhalten, Ergebnis ablesen, sparen.

## Die Datenbank (`data.json`)

Das Herzstück des Scanners ist die Datei `data.json`. Hier sind alle aktuell bekannten Barcodes und die dazugehörigen Aktionen hinterlegt.

**Du möchtest helfen?** Die Community lebt von aktuellen Daten! Wenn du eine neue Aktion kennst oder einen Fehler in den Daten findest:
* Bearbeite die `data.json` direkt in deinem Fork.
* Sende uns deine Änderungen einfach per **Pull Request**. Nach einer kurzen Prüfung wird die neue Aktion für alle Nutzer freigeschaltet.

## Funktionsweise

Der Scanner gleicht die gescannten EAN/UPC-Nummern in Echtzeit mit den Einträgen in der `data.json` ab.

1. App starten.
2. Barcode des Produkts fokussieren.
3. Die App färbt den unteren Teil des Bildschirmes, je Verfügbarkeit, ein..

---

## 🤖 Disclaimer (KI-Hinweis)

Bitte beachte: Diese Android-App wurde mithilfe von **Künstlicher Intelligenz (AI)** erstellt. Obwohl wir versuchen, die Funktionalität und die Daten so aktuell wie möglich zu halten, können Fehler auftreten. Die Nutzung erfolgt auf eigene Gefahr. Prüfe im Zweifelsfall immer die offiziellen Teilnahmebedingungen der jeweiligen Hersteller-Aktion.
