# SBOM Generation Testing Results

## `github-generated.json`

Generated using Github's SBOM generation tool (Insights > Dependency graph > Export SBOM)

SPDX Version: 2.3

- packages: 200
  - SPDXID
  - name
  - version
  - licsense concluded (sometimes)
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

looks like its getting the SPDXID's wrong

Example Package: aiohttp

**Github Generated:** `SPDXID:SPDXRef-pip-aiohttp-3.8.4`

**Tool Generated:** `SPDXID:SPDXRef-File--.venv-lib-python3.11-site-packages-aiohttp-retry-2.8.3.dist-info-top-level.txt-AB5E1DC6CC3ACE9E1BEE2C852488D7C5F253484A`
