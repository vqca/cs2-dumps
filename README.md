# CS2 Offsets & Patterns

Automatisch generiert von **cs2-dumper** auf jedem lokalen Dump.

- **Build:** 14188
- **Dump-Zeitpunkt:** 2026-10-01T13:35:43.277471700+00:00
- Erzeugt am: 01.10.2026 15:35

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
