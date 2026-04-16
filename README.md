# 📊 Wie oft ziehst du welche Farbe?

Eine interaktive Webanwendung zur Erfassung und Auswertung von Zufallsexperimenten im Mathematikunterricht (Grundschule, Klasse 4).

---

## ✨ Funktionen

### 👩‍🎓 Schüleransicht (`index.html`)
- Eingabe von:
  - Passwort (Unterrichtscode)
  - Gruppennummer
  - Anzahl gezogener Farben (blau/gelb, zwei Beutel)
- Automatische Validierung der Eingaben
- Speicherung der Ergebnisse in Firebase
- Benutzerfreundliche Eingabe (z. B. automatische Entfernung der „0“)

---

### 👩‍🏫 Lehrkraftansicht (`dashboard.html`)
- Übersicht aller Gruppen
- Echtzeit-Aktualisierung
- Darstellung als:
  - Tabelle
  - Säulendiagramme
- Anzeige der Gesamtanzahl der Gruppen

---

### ☁️ Datenbank (Firebase)
- Nutzung der Firebase Realtime Database
- Datenstruktur:
  ```
  Stunde3/{lessonCode}/groups/{groupKey}
  ```

---

## 🧠 Didaktischer Einsatz

Die Anwendung unterstützt:
- handlungsorientiertes Lernen
- eigenständige Datenerhebung
- Vergleich von Wahrscheinlichkeiten
- Reflexion über Zufall und Häufigkeiten

---

## 🚀 Installation & Nutzung

### 1. Voraussetzungen
- Firebase-Projekt
- aktivierte Realtime Database
- Webhosting (z. B. Firebase Hosting)

---

### 2. Firebase konfigurieren
Trage deine Firebase-Daten in die Datei `firebase-config.js` ein.

---

### 3. Projekt starten
- `index.html` → für Schülerinnen und Schüler
- `dashboard.html` → für Lehrkraft

Optional mit URL-Parameter:
index.html?lesson=33
dashboard.html?lesson=33

---

## 🔒 Datenschutz

- Es werden keine personenbezogenen Daten gespeichert
- Gruppennamen sollten anonym gewählt werden

---

## ⚙️ Technik

- HTML, CSS, JavaScript (ES Modules)
- Firebase SDK
- Echtzeit-Daten mit `onValue()`

---

## 🛠️ Erweiterungen (optional)

- Weitere Farben
- Prozentuale Auswertung
- Exportfunktion (CSV / PDF)
- Erweiterte Diagramme

---

## 👩‍🏫 Kontext

Entwickelt für die Unterrichtseinheit:

**„Gewinnwahrscheinlichkeiten auf dem Jahrmarkt“**  
(Mathematik, Klasse 4)
