# Laboratory charter

## Purpose

Build a **verifiable resource-coordination protocol** around Fog/Edge infrastructure, with STRATA as settlement unit.

The valuable centre is not branding or surface applications. It is:

> **DAG + identity + resource proofs + service receipts + settlement**

Everything else (portal, Bancada CGU, metaverse OS vocabulary, DAO surfaces) is an **application layer** that must not outrun protocol evidence.

## In scope

- Fog/Edge hierarchy and node treasury model (`NODE_WALLET`)
- DAG ledger, gossip, tip selection, lab finality
- Proof of Contribution → emission from `#mint`
- Burn to `#0` on resource use
- Resource proofs and service receipts
- Threat model and adversarial test harnesses
- Reference node operation (`FOG-NODE-PT-CM-001`)

## Out of scope (until evidence)

- Mainnet claims or production custody guarantees
- Real post-quantum cryptography (placeholders only on lab roadmap)
- aBFT finality guarantees
- Treating the Fog Node as a user/SCA account
- Expanding DAO / metaverse / KYC product surface while core invariants remain experimental

## Operator

**AMCM ENI** (André Manuel Calhegas Morais) operates the reference Fog Node in Lisboa and maintains this laboratory organisation.

## Governance of claims

If implementation behaviour and normative docs diverge, **docs win until a deliberate revision**. Silent drift is a defect.
