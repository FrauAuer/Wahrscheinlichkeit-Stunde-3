# 🎲 Zufallsexperiment – Farben ziehen (Firebase Web-App)

Diese Web-App ermöglicht es Schülergruppen, ihre Ergebnisse aus einem Zufallsexperiment (Farben ziehen) einzugeben und zentral auszuwerten.
Die Daten werden in einer Firebase Realtime Database gespeichert und live im Dashboard visualisiert.

---

## 📌 Funktionen

### 📝 Eingabeseite (index.html)
- Eingabe von Passwort, Gruppennummer und Ziehungen
- Nur Zahlen bei Gruppennummer erlaubt
- 0 verschwindet beim Anklicken automatisch
- Leere Felder werden wieder zu 0 gesetzt
- Speicherung in Firebase

### 📊 Dashboard (dashboard.html)
- Anzeige aller Gruppen-Ergebnisse
- Automatische Live-Aktualisierung
- Tabelle + Säulendiagramme
- Numerische Sortierung der Gruppen

### 🔥 Firebase
- Realtime Database
- Zentrale Datenspeicherung
- Live-Synchronisation

---

## 🗂️ Projektstruktur

projektordner/
│── index.html
│── dashboard.html
│── firebase-config.js

---

## ⚙️ Einrichtung

1. Firebase-Projekt erstellen
2. Realtime Database aktivieren
3. firebase-config.js mit eigenen Daten füllen

---

## ▶️ Nutzung

### Schüler:
1. index.html öffnen
2. Passwort eingeben
3. Gruppennummer eintragen
4. Ergebnisse eingeben
5. senden

### Lehrkraft:
1. dashboard.html öffnen
2. Passwort eingeben
3. Ergebnisse live sehen

---

## ⚠️ Hinweise

- Gruppennummer nur Zahlen
- Gruppen überschreiben eigene Daten
- Internet notwendig

---

## 🚀 Erweiterung

- Weitere Farben
- CSV Export
- Weitere Stunden (z.B. Stunde4)

---

## 👩‍🏫 Einsatz

Grundschule – Mathematik – Wahrscheinlichkeit
