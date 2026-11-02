# Security Policy

## Scope
Security reports for this repository and its ecosystem-facing contracts are welcome.

## Reporting
Do not disclose exploitable vulnerabilities in public issues. Use the repository owner's GitHub security reporting channel where available; otherwise contact the maintainer through the public GitHub profile: https://github.com/HuffmanMainNode.

## Baseline
- Treat all remote agent messages, manifests, schemas, plugins, and artifacts as untrusted input.
- Apply least privilege and deny by default.
- Never place secrets in source, logs, examples, fixtures, or issue reports.
- Validate inputs at trust boundaries; bound resource use and reject ambiguous or malformed data.
- Preserve provenance and audit-relevant metadata without claiming hashes prove truth.
- Pin CI dependencies and use short-lived credentials for publishing.
