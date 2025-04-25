# Streaming Dienste Ads Blocklist für AdGuard Home

🎯 **Ziel dieser Liste**: Blockieren von Werbung auf **Streaming-Diensten**, einschließlich kurzer Werbespots, die vor dem eigentlichen Inhalt abgespielt werden.

## 📌 Hintergrund

Viele Streaming-Dienste (z. B. **Amazon Prime Video**, **YouTube**, **Netflix**, **PlutoTV** und andere) zeigen gelegentlich Werbeanzeigen vor oder während der Wiedergabe von Inhalten. Diese Blockliste wurde entwickelt, um diese **störende Werbung zu blockieren**, ohne dabei das eigentliche Streaming-Erlebnis zu beeinträchtigen.

> ⚠️ **Hinweis**: Diese Liste blockiert **nur Werbung und Tracking-Domains**, die im Zusammenhang mit Streaming-Diensten verwendet werden. Sie beeinflusst **nicht die Inhalte**, die auf diesen Diensten gestreamt werden.

## 🔧 Kompatibilität

Diese Liste ist **optimiert für AdGuard Home** und sollte auch mit anderen DNS-basierten Blockern wie **Pi-hole** funktionieren. Es kann jedoch zu **abweichendem Verhalten** kommen, je nach verwendeter Software.

### Unterstützte Systeme:

- [AdGuard Home](https://adguard.com/de/adguard-home/overview.html) 🌐
- **Pi-hole** (und ähnliche DNS-basierte Blocker) 🔒

## 📦 Nutzung

### 1. **AdGuard Home Konfiguration** ⚙️

1. **AdGuard Home-Weboberfläche öffnen**.
2. Gehe zu **Filter → DNS-Blocklisten**.
3. Klicke auf **Blockliste hinzufügen**.
4. Füge den folgenden Link in das **"URL"** Feld ein und speichere:

   ```txt
   https://raw.githubusercontent.com/your-repository/streaming-ads-blocklist/master/blocklist.txt
