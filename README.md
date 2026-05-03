# Warner Music Group

Warner Music Group is one of the major record labels in the music industry, with recorded music and music publishing operations spanning a roster of artists, songwriters, and labels. WMG includes Warner Records, Atlantic Records, Elektra Records, and Warner Chappell Music. The company provides music licensing APIs and developer tools for integrating licensed music into applications.

- **Website:** [https://www.wmg.com/](https://www.wmg.com/)
- **Licensing Portal:** [https://www.wmgmusiclicensing.com/](https://www.wmgmusiclicensing.com/)
- **Warner Chappell Music:** [https://warnerchappell.com/](https://warnerchappell.com/)

## APIs

### Warner Music Group Licensing API

API for searching the WMG catalog and requesting sync, mechanical, digital, and performance licenses for recordings and compositions.

- **Base URL:** `https://api.wmg.com`
- **Authentication:** OAuth 2.0 Authorization Code
- **Licensing Contact:** [onlinelicensing@wmg.com](mailto:onlinelicensing@wmg.com)

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [warner-music-group-licensing-openapi.yml](openapi/warner-music-group-licensing-openapi.yml) | WMG Licensing API — catalog search, tracks, artists, licenses |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [warner-music-group-rules.yml](rules/warner-music-group-rules.yml) | Spectral ruleset for WMG API conventions |

### Naftiko Capabilities

#### Shared Per-API Definitions

| File | Description |
|------|-------------|
| [capabilities/shared/wmg-licensing.yaml](capabilities/shared/wmg-licensing.yaml) | WMG Licensing API definition |

#### Workflow Capabilities

| Workflow | Description | Tools |
|----------|-------------|-------|
| [music-licensing.yaml](capabilities/music-licensing.yaml) | Music catalog discovery and licensing workflow | 5 tools |

### JSON Schemas

| Schema | Description |
|--------|-------------|
| [warner-music-group-license-schema.json](json-schema/warner-music-group-license-schema.json) | Music license request schema |

### JSON Structures

| Structure | Description |
|-----------|-------------|
| [warner-music-group-license-structure.json](json-structure/warner-music-group-license-structure.json) | License data structure documentation |

### JSON-LD Contexts

| Context | Description |
|---------|-------------|
| [warner-music-group-context.jsonld](json-ld/warner-music-group-context.jsonld) | JSON-LD context (schema.org + Music Ontology aligned) |

### Examples

| Example | Description |
|---------|-------------|
| [warner-music-group-searchCatalog-example.json](examples/warner-music-group-searchCatalog-example.json) | Catalog search request/response example |

### Vocabulary

| File | Description |
|------|-------------|
| [warner-music-group-vocabulary.yml](vocabulary/warner-music-group-vocabulary.yml) | WMG music licensing vocabulary |

## Labels

- **Warner Records** — Pop, rock, country, and alternative
- **Atlantic Records** — Pop, hip-hop, R&B, and rock
- **Elektra Records** — Rock and alternative
- **Reprise Records** — Rock and alternative
- **Warner Chappell Music** — Global music publishing
- **Warner Chappell Production Music** — Production music library

## Maintainers

**Kin Lane** — [kin@apievangelist.com](mailto:kin@apievangelist.com)
