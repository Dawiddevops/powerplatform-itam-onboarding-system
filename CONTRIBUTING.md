# Contributing

This repository is a sanitized portfolio case study. Changes should improve the clarity of the generic design without making the public materials identify an employer, application, person, or operating environment.

## Privacy rules

- Do not add company names, ERP products, personal information, internal application or system names, tenant details, URLs, domains, credentials, or connection references.
- Do not publish raw application exports, screenshots, formulas, data files, or operational records.
- Keep examples conceptual and remove exact operational quantities, internal field names, and unique workflow details.
- Label reconstructed visuals and examples clearly; do not imply they are production evidence.

## Validation

Validate the conceptual JSON model with:

```powershell
python -m json.tool schema\conceptual-data-model.json
```

Check that Markdown links resolve within the repository and that Mermaid diagrams render correctly.

## Change description

Describe the documentation problem addressed, the files changed, and the validation performed. Do not include private context to justify a public change.
