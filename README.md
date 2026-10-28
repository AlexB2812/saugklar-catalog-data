# SaugKlar-Katalog (veröffentlicht)

Automatisch erzeugte, signierte Katalogdateien der App SaugKlar. **Nicht von Hand ändern** – jeder Stand wird vom
Workflow `publish.yml` des (privaten) Quell-Repos geschrieben.

- `v1/catalog.json` – Katalog (Schema 1)
- `v1/catalog.json.sig` – Ed25519-Signatur, von der App gegen ihren eingebauten Public Key geprüft
- `v1/catalog-meta.json` – Version, Anzahl, SHA-256 (die App prüft diese Datei höchstens einmal am Tag)
