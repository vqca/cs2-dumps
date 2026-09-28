# CS2 Offsets & Patterns

Automatisch generiert von **cs2-dumper** auf jedem lokalen Dump.

- **Build:** 14185
- **Dump-Zeitpunkt:** 2026-09-28T22:36:00.610755900+00:00
- Erzeugt am: 29.09.2026 00:36

## Was ist drin?

| Datei | Inhalt |
|---|---|
| `offsets.*` | Globale Adress-/Struktur-Offsets (JSON, C#, C++, Rust, Zig) |
| `patterns.*` | Funktions-Pattern-Scans (add_entity / remove_entity) |
| `client_dll.*`, `server_dll.*`, ... | Schema-Dumps aller Module |
| `interfaces.*`  | Interface-Adressen |
| `buttons.*`     | Button-Offsets |

## Nutzung

Einfach das Repo klonen oder einzelne Dateien laden:

`
git clone https://github.com/vqca/cs2-dumps.git
`

Das Repo wird bei jedem Dump automatisch aktualisiert. Die `offsets.json`
ist die maschinenlesbare Variante (dezimal).
