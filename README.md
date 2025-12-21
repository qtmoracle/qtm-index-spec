# QTM Index Specification

**Title:** QTM Index  
**Description:** A standards-based coordination primitive for deterministic discovery, eligibility evaluation, and clearing  

## Version
- **Current version:** v0.01
- **Canonical document:** QTM_Index_v0.01.pdf
- **Date (UTC):** 2025-12-17

## Release

Published release v0.01 is located in `release_v0.01/` and is intended to remain immutable.

## Overview
QTM Index is a neutral coordination primitive that indexes standards-based claims about entities and offerings to enable deterministic discovery, eligibility evaluation, and clearing across decentralized applications. The specification minimizes on-chain state, remains compatible with public standards and verifiable credential models, and does not assert truth, authority, or exclusivity.

## Scope
This repository contains the informational specification for QTM Index v0.01. It defines the conceptual and architectural foundation of the primitive and is intended for review, discussion, and interoperability exploration.

## Non-Goals
- Identity verification
- Reputation scoring
- Economic enforcement
- Consensus on truth
- Application-level policy or governance

## Repository Contents
- `QTM_Index_v0.01.pdf` — Canonical specification document
- `HASH.txt` — SHA-256 hash of the canonical PDF
- `README.md` — Repository overview and metadata

## Integrity
To verify the integrity of the specification:

```bash
shasum -a 256 QTM_Index_v0.01.pdf

Compare the output to the value in HASH.txt.

Status

QTM Index v0.01 is an initial conceptual specification. No production guarantees are implied.
