# CGSV1 — Continuous Governance State Vector

## Purpose
Represents system governance state as a vector of admissibility margins.

## Inputs
- System state
- Proposed action
- Context

## Outputs
- Authorized / Not Authorized

## Invariants
- Fail-closed semantics
- Weakest-margin dominance
- Revocation supersedes permission

## Role
Serves as a canonical admissibility evaluator.

## Non-Scope
- Optimization
- Execution
- Policy generation
