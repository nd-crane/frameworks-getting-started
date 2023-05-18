# SBOM Generation Testing Results

## `github-generated.json`

Generated using Github's SBOM generation tool (Insights > Dependency graph > Export SBOM)

SPDX Version: 2.3

- packages: 200
  - SPDXID
  - name
  - version
  - licsenseconcluded (sometimes)
  - externalRefs
    - referenceCategory
    - referenceLocator
    - referenceType
- files: 0
- relationships: 0

## `tool-generated.json`

Generated using (microsoft/sbom-tool)[https://github.com/microsoft/sbom-tool].

SPDX Version: 2.2

- packages: 207
  - name
  - SPDXID
  - version
  - supplier
  - externalRefs
    - referenceCategory
    - referenceLocator
    - referenceType
- files: 22981
- relationships: 207
  - package to root relationship only
