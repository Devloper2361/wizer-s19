# API Contract

This document defines communication between modules.

Do not change API structures without team agreement.

## Incident

Example:

{
  "id": "INC-001",
  "type": "CROWD",
  "status": "UNDER_REVIEW",
  "risk": "HIGH",
  "confidence": 0.89,
  "zoneId": "ZONE-C"
}

## Crowd

Example:

{
  "zoneId": "ZONE-C",
  "currentLevel": 82,
  "predictedLevel": 94,
  "risk": "HIGH",
  "confidence": 0.87
}