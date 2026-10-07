# Changelog

## 2.0.3

- Map Key Results' Objective reference from the Objectives matrix Short Description to its generated Id.
- Skip the first two preamble rows only on the Objectives origin sheet.
- Add fixed DEV, STAGING, and PROD deployment profiles; PROD remains blocked until its spreadsheet URLs are configured.

## 2.0.2

- Fixed Work Streams to Key Results relationship generation by matching Roadmap-Workstreams columns I/J against KRs column E.
- Relation rows now reference the generated Work Stream and Key Result IDs from their respective matrices.
- Ensured relation cells use the shared matrix format so the UI and import process preserve their values.
- Added diagnostics for matched relationship counts and unmatched Key Result examples.
