# claude-spec-template

Eine wiederverwendbare `.claude/` Projektstruktur-Vorlage für Claude Code Projekte.

## Verwendung

1. Oben rechts auf **"Use this template"** klicken
2. Neues Repository benennen
3. `CLAUDE.md` im Root ausfüllen
4. `.claude/` Ordner nach Bedarf befüllen

## Struktur

```
.
├── CLAUDE.md                          ← Projektanweisung für Claude (ausfüllen!)
└── .claude/
    ├── 00-development-tools/
    │   ├── completion-reports/        ← Abschlussberichte fertiggestellter Features
    │   ├── feature-tracking/          ← Status & Fortschritt einzelner Features
    │   ├── phase-tracking/            ← Phasenpläne und Phasenabschlüsse
    │   └── week-tracking/             ← Wöchentliche Planungen
    ├── 01-debugging/                  ← Debugging-Guides und Fix-Dokumentation
    ├── 02-quick-start/
    │   ├── 01-getting-started/        ← Einstieg & Setup
    │   ├── 02-installation/           ← Installationsanleitungen
    │   ├── 03-deployment/             ← Deployment-Checklisten
    │   ├── 04-integration/            ← Integrations-Guides
    │   ├── 05-features/               ← Feature-Dokumentation
    │   ├── 06-references/             ← Schnellreferenzen
    │   └── 07-guides/                 ← Schritt-für-Schritt-Guides
    ├── 03-system-diagnosis/           ← Performance-Analysen & Systemreports
    ├── 04-api-documentation/          ← API-Endpunkte & Referenz
    ├── 05-api-expansion/              ← Planung von API-Erweiterungen
    ├── 06-memory-storage/             ← Memory- und Storage-Guides
    ├── 07-phase-documentation/        ← Implementierungsdokumentation je Phase
    ├── 08-general-documentation/
    │   ├── Architecture/              ← Systemarchitektur
    │   ├── Guides/                    ← Allgemeine Guides
    │   ├── Planning/                  ← Planungsdokumente
    │   ├── Prompts/                   ← Prompt-Vorlagen
    │   ├── Skills/                    ← Agent-Skills
    │   ├── Summaries/                 ← Zusammenfassungen
    │   └── Verification/              ← Verifikations-Prompts
    ├── agents/                        ← Agent-Definitionen
    └── archive/
        ├── old-planning/              ← Archivierte Planungen
        └── old-weeks/                 ← Archivierte Wochen-Reports
```

## Warum diese Struktur?

Claude Code arbeitet effektiver wenn Dokumentation konsistent strukturiert ist.
Dieses Template gibt jedem Projekt von Anfang an die richtige Grundlage –
Claude findet sofort wo was liegt und kann gezielter dokumentieren.
