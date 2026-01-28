# 🎮 Hytale German Translation

Eine deutsche Übersetzung für Hytale.

## ✨ Features

- 📝 Übersetzung von Client und Server
- 👤 Avatar-Anpassungen komplett übersetzt
- 🔄 Regelmäßige Updates bei neuen Spielversionen
- ⚡ Einfache Ein-Klick-Installation

## 📥 Installation

### Automatische Installation (empfohlen)

Öffne die Windows **PowerShell** und füge folgenden Befehl ein:

```powershell
# Dieser Befehl installiert die deutsche Übersetzung automatisch
$zip = "$env:TEMP\gt.zip"; $dir = "$env:TEMP\gt"; `
    Invoke-WebRequest "https://github.com/CelduinX/hytale-german-translation/raw/refs/heads/main/latest.zip" -OutFile $zip; `
    Expand-Archive $zip $dir -Force; `
    Copy-Item "$dir\install\*" "$env:APPDATA\Hytale\install" -Recurse -Force; `
    Remove-Item $zip, $dir -Recurse -Force; `
    Write-Host "Installation erfolgreich abgeschlossen!" -ForegroundColor Green
```

**Was macht das Script?**
1. 📦 Lädt die ZIP-Datei von GitHub herunter
2. 📂 Entpackt sie in einen temporären Ordner
3. 📋 Kopiert die Übersetzungsdateien nach `%appdata%\Hytale\install`
4. 🧹 Räumt die temporären Dateien auf
5. ✅ Zeigt eine Erfolgsmeldung an

### Manuelle Installation

1. Lade die neueste Version herunter: https://github.com/CelduinX/hytale-german-translation/raw/refs/heads/main/latest.zip
2. Entpacke die ZIP-Datei
3. Kopiere den `install`-Ordner nach `%appdata%\Hytale\`

## 📁 Enthaltene Dateien

| Datei | Beschreibung |
|-------|--------------|
| `client.lang` | Client-Übersetzungen (UI, Menüs, etc.) |
| `server.lang` | Server-Übersetzungen (Items, NPCs, etc.) |
| `avatarCustomization/*.lang` | Avatar-Anpassungen |

---

⭐ Wenn dir die Übersetzung gefällt, lass gerne einen Stern da!
