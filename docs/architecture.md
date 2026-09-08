# Lab Architecture

The Detection Engineering Lab follows this lifecycle:

Attack behaviour
    ↓
Telemetry generation
    ↓
Data ingestion
    ↓
Detection logic
    ↓
Alert
    ↓
Enrichment
    ↓
Investigation
    ↓
Response
    ↓
Detection tuning

Every detection added to the repository should eventually identify:

- threat behaviour
- ATT&CK technique
- telemetry source
- required fields
- detection logic
- false positives
- validation method
- investigation procedure
- response guidance

## Design Principle

Detections should be treated as versioned and testable engineering artifacts.
