# testprojekt

📦 git init                # Neues lokales Repository starten
💾 git add <datei>        # Datei zur nächsten Speicherung vormerken
📝 git commit -m "..."    # Änderungen dauerhaft speichern
☁️ git remote add origin  # Verbindung zu GitHub herstellen
🚀 git push               # Änderungen zu GitHub hochladen
📥 git pull               # Änderungen von GitHub abrufen
🌿 git branch             # Branches anzeigen
🌱 git branch <name>      # Neuen Branch erstellen
🔀 git merge              # Branches zusammenführen

---

## 🧠 Git Notizen (Tag 1–3)

### 🔹 Grundprinzip
- Git ist eine **lokale Versionsverwaltung** für Projekte
- GitHub ist eine **Online-Plattform**, um Repos zu speichern & gemeinsam daran zu arbeiten
- Änderungen werden in sogenannten **Commits (Snapshots)** gespeichert

---

### 🔹 Häufige Git-Befehle

```bash
git status        # Aktuellen Stand ansehen (was wurde geändert?)
git add <datei>   # Änderungen zur Speicherung vormerken
git commit -m ""  # Änderungen mit Nachricht speichern
git log           # Änderungsverlauf anzeigen
git diff          # Unterschied zwischen Versionen anzeigen
git clone <url>   # Repo von GitHub lokal klonen
git fetch         # Neueste Daten abrufen, aber noch nicht mergen
git push          # Änderungen zu GitHub senden
git pull          # Änderungen von GitHub holen + mergen
git remote -v     # Zeigt die verbundenen GitHub-Repos an


git switch -c feature-login    # Neuer Branch: 'feature-login' + direkt hineinspringen
# Datei ändern...
git add README.md              # Änderung vorbereiten
git commit -m "Login-Feature begonnen"  # Speichern im Branch
git switch main                # Zurück zur Hauptversion
git merge feature-login        # Änderungen von feature-login übernehmen
git branch -d feature-login    # Branch löschen (aufgeräumt)
