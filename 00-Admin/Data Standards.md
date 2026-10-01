# Data Standards

## Identifiers

- Observations: `OBS-NNN`
- Samples: `K26-NNN`
- Photos: `P26-YYYYMMDD-NNN`

## Required metadata

Every field record should include the date, location, observer, coordinates and
links to related notes. Use ISO dates (`YYYY-MM-DD`) and decimal latitude /
longitude in WGS84 unless another datum is explicitly recorded.

## Evidence and interpretation

Use separate sections for what was observed, what was measured, and what is
inferred. Label interpretations with a confidence of `low`, `medium` or `high`
and cite external claims in `06-References/`.

## Measurements

Record units with every value. Use strike/dip conventions consistently and
include the instrument or method where practical.
