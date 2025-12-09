---
layout: page
title: BSG Command Net Frequency Allocation Process
description: null
image: null
author: null
show_tile: false
---

This document formalizes the approved procedure for establishing, protecting, and utilizing the Command Net long-range (LR) radio frequency during BSG operations.

## 1. Purpose

This process ensures:

* The Command Net remains restricted to authorized personnel.
* Frequencies are not compromised through in-game voice or text communication.
* A consistent, non-verbalised method is used to determine the LR command frequency each mission.
* Radio discipline and operational security are maintained across all campaigns.

## 2. Authorized Roles

Only the following roles may access or transmit on the Command Net:

* Team Lead
* RTO
* JTAC
* Game Master

All other personnel must remain on their designated short-range squad radios unless explicitly instructed otherwise.

## 3. Seed Frequency Governance

### 3.1 Definition

A **seed frequency** is an internally agreed LR frequency baseline used for calculating the Command Net frequency.

### 3.2 Protection

The seed frequency must **never** be spoken aloud or typed during missions.

### 3.3 Update Cycle

The seed frequency must be updated:

* Every six months, or
* After each campaign, or
* Immediately upon compromise (e.g., an officer states the frequency in mission).

### 3.4 Documentation

The updated seed must be recorded in the appropriate restricted channel or document accessible only to authorized officers.

## 4. Modifier System

### 4.1 Definition

A **modifier** is a numerical multiplier applied to the seed frequency to produce the mission’s Command Net frequency.

### 4.2 Agreement

The Team Lead, RTO, JTAC, and Game Master must agree on the modifier before mission start or immediately before radio checks.

### 4.3 Verbal Use

Modifiers may be spoken aloud, as they do not reveal the actual frequency.

### 4.4 Standard Modifier Terminology

The following phrases are approved for operational use:

* “Single Net” = ×1
* “Double Net” = ×2
* “Triple Net” = ×3
* “Quad Net” = ×4
* “Five Net” = ×5

**Note:** This calculation method is intentionally simple but may produce resulting frequencies outside the usable LR radio range in Arma 3. Future refinements to the calculation (such as modular arithmetic, clamping, or offset systems) may be implemented to improve practical usability without compromising security.

### 4.5 Calculation

Command Net Frequency = **Seed Frequency × Modifier**

## 5. In-Mission Procedure

1. The RTO announces the agreed modifier phrase via voice or text (e.g., “Command Net will be on the triple net”).
2. Authorized personnel compute the resulting frequency using the current seed.
3. The actual frequency must never be spoken aloud or typed during the mission.
4. Authorized roles tune into the Command Net.
5. All other players remain on their designated short-range squad radios unless specifically instructed otherwise.

## 6. Compliance

All personnel in authorized roles are responsible for enforcing this procedure.
Any breach—intentional or accidental—must be reported to the Game Master team so that the seed frequency can be rotated if necessary.

## 7. Review

This process will be reviewed during each seed update cycle to ensure continued effectiveness and alignment with BSG operational standards.
