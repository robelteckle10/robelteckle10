# PhenoAge Calculator

[← Back to portfolio](../README.md)

**Status:** Done
**Stack:** Single-file HTML + JavaScript

## In plain English

Enter nine common blood-test values plus your age, and it estimates your "biological age" using the published Levine et al. (2018) PhenoAge formula. Everything runs in the browser; no data is sent anywhere.

## How it works

```mermaid
flowchart LR
    I[Age + 9 lab markers] --> X[Linear score<br/>weighted sum]
    X --> M[Mortality score]
    M --> P[PhenoAge]
```

Inputs: albumin, creatinine, glucose, C-reactive protein, lymphocyte %, mean cell volume, red cell distribution width, alkaline phosphatase, white blood cell count.

> Educational tool, not medical advice.
