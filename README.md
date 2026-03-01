# demo-order-service

> **BOSS Demo Microservice — Tier 2 (Important)**
>
> Simulates the Order / Inventory Management Service in the BOSS  application ecosystem.

---

## Overview

This repository is part of the **BOSS Versioning System** demo. It represents a **Tier 2 Important** microservice — changes here have a medium impact on the BOSS application version.

## Branch Structure

| Branch | Environment | Version Impact |
|--------|-------------|----------------|
| `develop` | DEV | Right-most digit bumps (e.g. `2.0.0 → 2.0.1`) |
| `release/qa` | QA | No version bump — testing only |
| `uat` | UAT (Pre-Production) | **Middle digit bumps** (e.g. `2.0.3 → 2.1.0`) — triggers BOSS aggregator |

## PR Labels

| Label | Meaning | BOSS Impact (Tier 2) |
|-------|---------|----------------------|
| `breaking-change` | API/data model breaking change | **MINOR bump** |
| `feature` | New functionality | **MINOR bump** |
| `enhancement` | Improvement to existing feature | **MINOR bump** |
| `bugfix` | Bug fix | **PATCH bump** |

## BOSS Tier Assignment

- **Tier**: 2 — Important
- **Simulates**: Order / Inventory Service
- **Priority**: Medium — changes affect business features
