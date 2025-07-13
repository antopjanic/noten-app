# 📚 Notenverwaltung

Eine moderne Web-App zur Verwaltung von Studiennoten mit mehreren Noten pro Modul und gewichteter Durchschnittsberechnung im Apple-ähnlichen Design.

## ✨ Features

- **Vollständige Modulverwaltung** für 6 Semester
- **Mehrere Noten pro Modul** mit automatischer Durchschnittsberechnung
- **Gewichtete Durchschnittsberechnung** pro Semester und gesamt
- **LocalStorage-Persistierung** - Ihre Noten bleiben gespeichert
- **Minimalistisches Apple-Design** mit TailwindCSS
- **Responsive Design** für alle Geräte
- **Datenexport** als JSON-Datei

## 🚀 Lokale Verwendung

1. **App öffnen**:
   - Doppelklicken Sie auf `index.html`
   - Oder öffnen Sie die Datei in Ihrem Browser

2. **App verwenden**:
   - Noten in die Eingabefelder eingeben (1.0 - 6.0)
   - "+" Button klicken oder Enter drücken
   - Gewichtete Durchschnitte werden automatisch berechnet
   - Alle Daten werden im Browser gespeichert

## 🌐 Online veröffentlichen (Kostenlos)

### Option 1: GitHub Pages (Empfohlen)

1. **GitHub Account erstellen** (falls noch nicht vorhanden):
   - Besuchen Sie [github.com](https://github.com)
   - Erstellen Sie ein kostenloses Konto

2. **Repository erstellen**:
   - Klicken Sie auf "New repository"
   - Name: `notenverwaltung`
   - Wählen Sie "Public"
   - Klicken Sie auf "Create repository"

3. **Dateien hochladen**:
   - Laden Sie alle Dateien aus diesem Ordner hoch
   - Oder verwenden Sie GitHub Desktop

4. **GitHub Pages aktivieren**:
   - Gehen Sie zu "Settings" → "Pages"
   - Source: "Deploy from a branch"
   - Branch: "main" oder "master"
   - Klicken Sie auf "Save"

5. **Webseite ist online**:
   - Ihre App ist unter `https://ihr-username.github.io/notenverwaltung` verfügbar
   - Kostenlos und automatisch gehostet

### Option 2: Netlify (Alternative)

1. **Netlify Account erstellen**:
   - Besuchen Sie [netlify.com](https://netlify.com)
   - Erstellen Sie ein kostenloses Konto

2. **App deployen**:
   - Ziehen Sie den Ordner auf die Netlify-Oberfläche
   - Oder verbinden Sie mit GitHub

3. **Webseite ist online**:
   - Automatische URL wird generiert
   - Kostenlos und schnell

### Option 3: Vercel (Alternative)

1. **Vercel Account erstellen**:
   - Besuchen Sie [vercel.com](https://vercel.com)
   - Erstellen Sie ein kostenloses Konto

2. **App deployen**:
   - Verbinden Sie mit GitHub
   - Automatisches Deployment

## 📁 Projektstruktur

```
notenverwaltung/
├── index.html              # Hauptdatei (eigenständig)
├── README.md               # Diese Datei
└── [andere Dateien]        # Für React-Version (optional)
```

## 🎯 Verwendung

1. **Noten eingeben**: 
   - Geben Sie eine Note (1.0 - 6.0) ein
   - Klicken Sie auf "+" oder drücken Sie Enter
   - Mehrere Noten pro Modul möglich

2. **Noten verwalten**:
   - Klicken Sie auf Note-Tags zum Löschen
   - "Löschen" Button für alle Noten eines Moduls
   - "Alle Noten löschen" für kompletten Reset

3. **Durchschnitte verfolgen**:
   - Modul-Durchschnitt aus allen Noten
   - Semester-Durchschnitt gewichtet nach Modul-Gewichtung
   - Gesamtdurchschnitt aller gewichteten Modul-Durchschnitte

4. **Daten sichern**:
   - Automatische Speicherung im Browser
   - "Daten exportieren" für Backup als JSON

## 🎨 Design

- **Apple-ähnliches Design** mit sanften Schatten und abgerundeten Ecken
- **Farbkodierung**: 
  - 🟢 Grün: Noten ≥ 5.5
  - 🟡 Gelb: Noten 4.5 - 5.4
  - 🔴 Rot: Noten < 4.5
- **Responsive Layout** für Desktop, Tablet und Mobile

## 📊 Modulübersicht

Die App enthält alle Module aus 6 Semestern mit entsprechenden Gewichtungen:

- **Semester 1**: 8 Module (Gewichtung 1-4)
- **Semester 2**: 6 Module (Gewichtung 2-4)
- **Semester 3**: 6 Module (Gewichtung 2-4)
- **Semester 4**: 3 Module (Gewichtung 2-4)
- **Semester 5**: 6 Module (Gewichtung 2-4)
- **Semester 6**: 5 Module (Gewichtung 1-6)

## 🔧 Gewichtungsberechnung

**Wichtig**: Die Gewichtung wird nur auf den **Modul-Durchschnitt** angewendet, nicht auf jede einzelne Note.

**Beispiel**:
- Modul "Mathematik" (Gewichtung: 4)
- Noten: [5.0, 5.5, 4.5]
- Modul-Durchschnitt: (5.0 + 5.5 + 4.5) ÷ 3 = 5.0
- Gewichtet für Semester-Durchschnitt: 5.0 × 4 = 20.0

## 📝 Lizenz

Dieses Projekt ist für den persönlichen Gebrauch erstellt.

## 🆘 Support

Bei Fragen oder Problemen:
1. Überprüfen Sie die Browser-Konsole (F12)
2. Stellen Sie sicher, dass JavaScript aktiviert ist
3. Versuchen Sie einen anderen Browser 