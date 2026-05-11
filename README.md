# redline-cbis
Redline Congressional Boundary Intelligence System

--
Built to track and legtitimize voting rights, gerrymandering, and the consititution.


Redline is a civic intelligence platform that quantifies the relationship between votes cast and legislative power under modern U.S. redistricting regimes.

Following the Louisiana v. Callais decision (2026), multiple states began rapid redistricting cycles that materially altered representation outcomes. This system tracks those changes in real time and models their counterfactual fairness under proportional electoral assumptions.

## Core Capabilities

- Representation Gap Analysis (seat-to-vote distortion modeling)
- Counterfactual Map Simulation (fair-district projection)
- Majority-Minority District (MMD) erosion tracking
- State-level redistricting risk classification
- Precinct-level vote efficiency modeling (Virginia module)

## Key Insight

Modern gerrymandering is no longer static. It is a cascading system response triggered by judicial decisions, legislative signaling, and interstate coordination effects.

Redline treats this as a dynamic system rather than isolated state maps.

## Data Model

All outputs are derived from versioned datasets and reproducible metrics defined in `/core/metrics`.

## Methodology

See `/docs/methodology.md` for formal definitions of:
- Representation Gap
- Efficiency Gap
- Counterfactual Seat Allocation Model

## Architecture

The system is composed of:
- A core analytical engine
- A state-level data normalization layer
- A visualization and simulation frontend

## Status

Early-stage research prototype. Designed for policy analysis, academic use, and civic transparency tooling.
