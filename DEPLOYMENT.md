# 🚀 Deployment-Anleitung: Notenverwaltung online veröffentlichen

## 📋 Voraussetzungen

- Ein kostenloser GitHub Account
- Die Dateien aus dem `notenverwaltung` Ordner

## 🎯 Schritt-für-Schritt Anleitung

### 1. GitHub Account erstellen

1. Besuchen Sie [github.com](https://github.com)
2. Klicken Sie auf "Sign up"
3. Folgen Sie den Anweisungen zur Account-Erstellung
4. Bestätigen Sie Ihre E-Mail-Adresse

### 2. Repository erstellen

1. Klicken Sie auf das "+" Symbol oben rechts
2. Wählen Sie "New repository"
3. Füllen Sie die Felder aus:
   - **Repository name**: `notenverwaltung`
   - **Description**: `Notenverwaltung für Studium mit gewichteten Durchschnitten`
   - **Visibility**: ✅ Public
   - **Initialize this repository with**: ❌ Keine Optionen aktivieren
4. Klicken Sie auf "Create repository"

### 3. Dateien hochladen

#### Option A: Über die GitHub-Oberfläche

1. Klicken Sie auf "uploading an existing file"
2. Ziehen Sie alle Dateien aus dem `notenverwaltung` Ordner in das Upload-Fenster
3. Wichtig: Laden Sie mindestens diese Dateien hoch:
   - `index.html`
   - `README.md`
4. Klicken Sie auf "Commit changes"

#### Option B: Mit GitHub Desktop (Einfacher)

1. Laden Sie [GitHub Desktop](https://desktop.github.com/) herunter
2. Installieren und öffnen Sie GitHub Desktop
3. Klicken Sie auf "Clone a repository from the Internet"
4. Wählen Sie Ihr `notenverwaltung` Repository
5. Wählen Sie einen lokalen Pfad
6. Klicken Sie auf "Clone"
7. Kopieren Sie alle Dateien aus dem `notenverwaltung` Ordner in den geklonten Ordner
8. Gehen Sie zurück zu GitHub Desktop
9. Sie sehen alle neuen Dateien
10. Geben Sie eine Commit-Nachricht ein (z.B. "Initial commit")
11. Klicken Sie auf "Commit to main"
12. Klicken Sie auf "Push origin"

### 4. GitHub Pages aktivieren

1. Gehen Sie zu Ihrem Repository auf GitHub
2. Klicken Sie auf "Settings" (Tab oben)
3. Scrollen Sie runter zu "Pages" (linke Seitenleiste)
4. Unter "Source":
   - Wählen Sie "Deploy from a branch"
   - Branch: `main` (oder `master`)
   - Folder: `/ (root)`
5. Klicken Sie auf "Save"

### 5. Webseite ist online! 🎉

- Ihre App ist jetzt unter `https://ihr-username.github.io/notenverwaltung` verfügbar
- Es kann 1-5 Minuten dauern, bis die Seite verfügbar ist
- Die URL wird in den Pages-Einstellungen angezeigt

## 🔧 Custom Domain (Optional)

Falls Sie eine eigene Domain haben:

1. Gehen Sie zu "Settings" → "Pages"
2. Unter "Custom domain":
   - Geben Sie Ihre Domain ein (z.B. `notenverwaltung.de`)
   - Klicken Sie auf "Save"
3. Konfigurieren Sie Ihre Domain-Einstellungen beim Provider

## 📱 Testen der Webseite

1. Öffnen Sie die URL in verschiedenen Browsern
2. Testen Sie auf Desktop, Tablet und Mobile
3. Überprüfen Sie alle Funktionen:
   - Noten eingeben
   - Durchschnitte berechnen
   - Daten exportieren
   - LocalStorage funktioniert

## 🆘 Häufige Probleme

### Problem: Seite lädt nicht
- **Lösung**: Warten Sie 5-10 Minuten nach dem ersten Upload
- **Lösung**: Überprüfen Sie, ob `index.html` im Root-Verzeichnis liegt

### Problem: JavaScript funktioniert nicht
- **Lösung**: Überprüfen Sie die Browser-Konsole (F12)
- **Lösung**: Stellen Sie sicher, dass JavaScript aktiviert ist

### Problem: LocalStorage funktioniert nicht
- **Lösung**: Verwenden Sie HTTPS (GitHub Pages ist automatisch HTTPS)
- **Lösung**: Überprüfen Sie die Browser-Einstellungen

## 🔄 Updates veröffentlichen

Bei Änderungen an der App:

1. Laden Sie die aktualisierten Dateien hoch
2. GitHub Pages aktualisiert automatisch
3. Die Änderungen sind nach 1-5 Minuten online

## 📊 Analytics hinzufügen (Optional)

Falls Sie Besucher-Statistiken möchten:

1. Erstellen Sie ein kostenloses Konto bei [Google Analytics](https://analytics.google.com/)
2. Fügen Sie den Tracking-Code in `index.html` ein
3. Verfolgen Sie Besucher und Nutzung

## 🎯 Nächste Schritte

Nach dem erfolgreichen Deployment können Sie:

1. **Freunde und Kommilitonen einladen** die App zu nutzen
2. **Feedback sammeln** und Verbesserungen implementieren
3. **Weitere Features hinzufügen** wie:
   - Benutzer-Accounts
   - Cloud-Speicherung
   - PDF-Export
   - Noten-Historie

---

**🎉 Glückwunsch!** Ihre Notenverwaltung ist jetzt online und für alle kostenlos verfügbar! 