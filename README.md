# PACT STIX Data

Auto-generated [STIX 2.1](https://oasis-open.github.io/cti-documentation/stix/intro) bundle for the **PACT** (Physical Access & Control Taxonomy) matrix. Use it with [MITRE ATT&CK Navigator](https://mitre-attack.github.io/attack-navigator/) or any STIX 2.x tooling.

- **Website:** [pact.slashsec.at](https://pact.slashsec.at)
- **Source dataset (JSON):** [pact-data-json](https://github.com/slashsec-Red-Teaming-GmbH/pact-data-json)

## ATT&CK Navigator Usage

1. Open [ATT&CK Navigator](https://mitre-attack.github.io/attack-navigator/).
2. **Create New Layer → More Options**.
3. **Collection or STIX bundle URL:** `https://raw.githubusercontent.com/slashsec-Red-Teaming-GmbH/pact-data-stix/main/pact-attack.json`
4. Set **Bundle version number** to `4`.
5. Set **Bundle domain** to `pact-attack`.

## Do not edit this repository directly

Files here are produced by the website CI pipeline from the JSON dataset. To change tactics, techniques, mitigations, or detections, open a pull request against [pact-data-json](https://github.com/slashsec-Red-Teaming-GmbH/pact-data-json). After the website builds successfully, updated STIX files are committed here automatically.

## Files

| File | Purpose |
|------|---------|
| `pact-attack.json` | STIX 2.1 bundle (tactics, techniques, sub-techniques, mitigations, relationships) |
| `index.json` | Collection index for Navigator (`collection_index_url`) |

### Raw URLs

| Resource | URL |
|----------|-----|
| STIX bundle | `https://raw.githubusercontent.com/slashsec-Red-Teaming-GmbH/pact-data-stix/main/pact-attack.json` |
| Collection index | `https://raw.githubusercontent.com/slashsec-Red-Teaming-GmbH/pact-data-stix/main/index.json` |

Technique and tactic pages in the bundle link to [pact.slashsec.at](https://pact.slashsec.at).

## Reporting issues

- **Content errors** (wrong technique text, missing links, bad IDs): [pact-data-json issues](https://github.com/slashsec-Red-Teaming-GmbH/pact-data-json/issues)
- **STIX export / Navigator compatibility:** [pact-data-json issues](https://github.com/slashsec-Red-Teaming-GmbH/pact-data-stix/issues) or via email to [pact@slashsec.at](mailto:pact@slashsec.at)

## License

Licensed under the [Apache License 2.0](LICENSE).
