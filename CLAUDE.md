# CLAUDE.md – Projektanweisung

## Projektname
<!-- Name des Projekts -->

## Stack
- Backend: <!-- Technologie eintragen -->
- Frontend: <!-- Technologie eintragen -->
- Datenbank: <!-- Technologie eintragen -->
- Weitere: <!-- Technologie eintragen -->

## Wichtige Befehle
```bash
# Start
# npm run dev / uvicorn main:app ...

# Tests
# npm test / pytest ...

# Build
# npm run build ...
```

## Dokumentationsstruktur
Alle Projektdokumente liegen unter `.claude/`:

| Ordner | Verwendung |
|--------|------------|
| `00-development-tools/completion-reports/` | Abschlussberichte fertiggestellter Features |
| `00-development-tools/feature-tracking/` | Status & Fortschritt einzelner Features |
| `00-development-tools/phase-tracking/` | Phasenpläne und Phasenabschlüsse |
| `00-development-tools/week-tracking/` | Wöchentliche Planungen und Zusammenfassungen |
| `01-debugging/` | Debugging-Guides und Fix-Dokumentation |
| `02-quick-start/` | Einstieg, Installation, Deployment, Integration |
| `03-system-diagnosis/` | Performance-Analysen und Systemreports |
| `04-api-documentation/` | API-Endpunkte, Referenz, Beispiele |
| `05-api-expansion/` | Planung von API-Erweiterungen |
| `06-memory-storage/` | Memory- und Storage-Guides |
| `07-phase-documentation/` | Implementierungsdokumentation je Phase |
| `08-general-documentation/` | Architektur, Guides, Prompts, Skills, Summaries |
| `agents/` | Agent-Definitionen für Claude |
| `archive/` | Archivierte Planungen und alte Reports |

## Arbeitsregeln
- Neue Features in `00-development-tools/feature-tracking/` dokumentieren
- Abgeschlossene Features als Report nach `00-development-tools/completion-reports/`
- Phasenabschlüsse in `07-phase-documentation/` ablegen
- Debugging-Lösungen in `01-debugging/` festhalten
- API-Änderungen sofort in `04-api-documentation/` aktualisieren

## Architektur
<!-- Kurze Beschreibung der Systemarchitektur -->

## Wichtige Dateien
<!-- z.B. src/main.py, app/page.tsx, ... -->

## Umgebungsvariablen
<!-- Welche .env Variablen werden benötigt -->
