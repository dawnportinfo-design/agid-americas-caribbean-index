# AGID Caribbean Index

AGID Caribbean index for Americas country and territory repository coordination.

## Status

- Owner: `dawnportinfo-design`
- Repository: `agid-americas-caribbean-index`
- Stage: `wave-0-index`
- Index readiness: `index-ready`
- Country data readiness: `plan-only`
- Privacy: no raw personal address, recipient, precise private coordinate, witness, or private-key material.

## Scope

The Caribbean index tracks sovereign states, overseas territories, special municipalities, island chains, and staged postal-weak or no-postal-code country packs.

This repository is an AGID coordination index. It stores repository pointers,
safe source policy, postal status, quality gates, conformance status, and
special-region display policy for Americas address infrastructure.

It does not store private delivery addresses, recipient records, precise private
coordinates, witness material, private keys, large GIS extracts, map tiles,
search indexes, or carrier operational datasets.

## Related Repositories

- `agid-country-cu` - Cuba (CU)
- `agid-country-ht` - Haiti (HT)
- `agid-country-do` - Dominican Republic (DO)
- `agid-country-pr` - Puerto Rico (US) (PR)
- `agid-country-jm` - Jamaica (JM)
- `agid-country-bs` - Bahamas (BS)
- `agid-country-tt` - Trinidad and Tobago (TT)
- `agid-country-vi` - US Virgin Islands (US) (VI)
- `agid-country-vg` - British Virgin Islands (VG)
- `agid-country-ky` - Cayman Islands (KY)
- `agid-country-tc` - Turks and Caicos (TC)
- `agid-country-gp` - Guadeloupe (GP)
- `agid-country-mq` - Martinique (MQ)
- `agid-country-bb` - Barbados (BB)
- `agid-country-lc` - Saint Lucia (LC)
- `agid-country-vc` - St. Vincent & Grenadines (VC)
- `agid-country-gd` - Grenada (GD)
- `agid-country-dm` - Dominica (DM)
- `agid-country-kn` - Saint Kitts and Nevis (KN)
- `agid-country-ag` - Antigua and Barbuda (AG)
- `agid-country-aw` - Aruba (AW)
- `agid-country-cw` - Curacao (CW)
- `agid-country-sx` - Sint Maarten (SX)
- `agid-country-mf` - Saint Martin (MF)
- `agid-country-bl` - St. Barthelemy (BL)
- `agid-country-ai` - Anguilla (AI)
- `agid-country-ms` - Montserrat (MS)
- `agid-country-bq` - Caribbean Netherlands (BQ)

## Data Boundary

GitHub may contain synthetic fixtures, rules, manifests, source notes, postal
status, repository placement, and quality gate metadata. Large geography,
building polygons, hydrographic datasets, OSM/Overture extracts, routing
networks, and generated caches must stay in external content-addressed packs.

## Country And Territory Creation Policy

Physical country repositories are created only when they have enough content to
be useful: README, manifest, postal status, source policy, quality gates,
synthetic tests, no-raw-address guardrails, and a maintainer path. Planned child
repositories stay in this index until data volume, ownership, or pull-request
pressure justifies a split.

## Postal-Weak And Island Policy

Caribbean and Latin American packs can include postal-code, postal-weak,
no-postal-code, island, ferry, border, disaster, and informal-settlement modes.
Those modes must be represented as technical address infrastructure and never
as publication of personal addresses.

## Special Region Policy

AGID repository placement is a technical address-data organization rule. It does
not imply sovereignty, recognition, or territorial ownership. Disputed,
overseas, de facto, maritime, island, or special regions must carry explicit
source, license, canonical region, and display policy before data publication.

## Validation

The repository includes JSON manifests and a lightweight GitHub Actions workflow
that validates JSON files. Public release content must pass AGID no-raw-address
review before data publication.
