flowchart LR
  A[Web API] --> B[Format & AV Scan]
  B -->|OK| C[Pre‑Validation Rules]
  C -->|PASS| D[Perception]
  B -->|FAIL| Q[Quarantine]
  C -->|FAIL| Q
