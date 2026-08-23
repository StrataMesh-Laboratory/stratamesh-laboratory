# Laboratory ladder

**Evidence before promotion.** No stage is skipped by marketing.  
Full public text: [ROADMAP-PUBLIC-v0.3](https://github.com/StrataMesh-Laboratory/stratamesh-core/blob/main/docs/ROADMAP-PUBLIC-v0.3.md) in `stratamesh-core`.

| Stage | Gate |
|-------|------|
| **LAB** (current) | Reference node · wire + threat drafts · single-process benchmark · honest non-claims |
| **Adversarial lab** | Multi-host gossip + chaos · I1–I6 in CI · resource-proof MVP · receipt path |
| **Public testnet** | Frozen wire subset · published adversarial evidence · external join · still not mainnet |
| **Mainnet** | Explicit decision after sustained evidence — **not scheduled here** |

## Ordered backlog (urgency)

1. Multi-host gossip (real peers)  
2. Economic invariants I1–I6 in CI  
3. Resource-proof MVP (one capacity class)  
4. Service receipt minimal object  
5. Wire freeze + join doc aligned to running peers  
6. Public testnet metrics  
7. Application depth only after green gates  

## Centres of gravity

DAG · identity · resource proofs · service receipts · settlement (`#mint` / `#0`)

## Workstream labels (inside a stage only)

- **A-like (mesh):** multi-host, chaos, peer/sync metrics  
- **B-like (depth):** emission enforcement, proofs, invariants — not full Agora/ACB/PQ as promotion gates  

Detail: `stratamesh-core` · `docs/WIRE-PROTOCOL-v1.md` · `docs/THREAT-MODEL-v1.md` · `src/protocol_benchmark.py`
