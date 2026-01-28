# 🎮 Hytale German Translation

Eine deutsche Übersetzung für Hytale.

## ✨ Features

- 📝 Übersetzung von Client und Server
- 👤 Avatar-Anpassungen komplett übersetzt
- 🔄 Regelmäßige Updates bei neuen Spielversionen
- ⚡ Einfache Ein-Klick-Installation

## 📥 Installation

### Automatische Installation (empfohlen)

Öffne **PowerShell** und füge folgenden Befehl ein:

```powershell
# Dieser Befehl installiert die deutsche Übersetzung automatisch
$zip = "$env:TEMP\gt.zip"; $dir = "$env:TEMP\gt"; `
Invoke-WebRequest "https://github.com/USERNAME/REPO/releases/latest/download/German_Translation.zip" -OutFile $zip; `
Expand-Archive $zip $dir -Force; `
Copy-Item "$dir\install\*" "$env:APPDATA\Hytale\install" -Recurse -Force; `
Remove-Item $zip, $dir -Recurse -Force
```

### Manuelle Installation

1. Lade die neueste Version von den [Releases](https://github.com/USERNAME/REPO/releases) herunter
2. Entpacke die ZIP-Datei
3. Kopiere den `install`-Ordner nach `%appdata%\Hytale\`

## 📁 Enthaltene Dateien

| Datei | Beschreibung |
|-------|--------------|
| `client.lang` | Client-Übersetzungen (UI, Menüs, etc.) |
| `server.lang` | Server-Übersetzungen (Items, NPCs, etc.) |
| `avatarCustomization/*.lang` | Avatar-Anpassungen |

## 🤝 Mitwirken

Fehler gefunden oder Verbesserungsvorschläge? Erstelle gerne ein [Issue](https://github.com/USERNAME/REPO/issues)!

---

⭐ Wenn dir die Übersetzung gefällt, lass gerne einen Stern da!
