<p align="center">
    <img src="./img/ATX_Defense_Logo_Horizontal.png" alt="ATX Defense Logo"/>
</p>

# CMMC Space FedRAMP Marketplace

This repository holds the FedRAMP certification package overview data for the CMMC Space FedRAMP Marketplace listing.

## Files

- `fedramp-certification-package-overview.json` — the unmodified template published by the FedRAMP PMO. Use it as the reference for structure and field names; do not fill it out.
- `cmmc-space-fedramp-certification-package.json` — the template filled out with the information for our FedRAMP Marketplace listing. This is the file we maintain.

## Validation

Any change to `cmmc-space-fedramp-certification-package.json` must pass the [FedRAMP JSON Schema Validator](https://www.fedramp.gov/schemas/validator/?schema=fedramp-certification-package-overview-schema-2026-06-24.json) before it can be approved or merged. Paste the updated file into the validator, confirm it validates cleanly, and note that in the pull request.
