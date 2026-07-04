# holographic-wormhole-codec

**The unified DBBH → DBWH throat — one tested loop.** Pure Rust, zero deps, `json=0`, no JSON/Node.

The map found the black mouth, white mouth, N-cylinder slice roof, residual selector, and watcher gate
*spread* across `dbbh-coms-quant-prism`, `Q-PRISM/host8`, and `path2-two-shadow-recovery` PR #1. This
crate ports them into **one object, one loop**:

```
BLACK MOUTH  black_hole_compress: object -> N-cylinder shadows + AGT address + IX-737 capsule
THROAT       crosses = capsule + tiny residual selector, NOT the object
WHITE MOUTH  white_hole_emit: consent-gated reconstruct (inverse Radon / CRT), AGT round-trip check
WATCHER      N-directional gate: black<->white AGT round-trip + N-cylinder cross-checks + watcher rows
RECEIPT      HBP hot-path rows, json=0
             -> VerifiedClone | Held{InsufficientRoof, NoConsent, Collapsed, WatcherDisagreement, AddressMismatch}
```

## Honest boundary
- `MEASURED` (`cargo test`): the single-machine loop — verified byte-identical clone; consent gating
  (no-consent / collapse Held); insufficient-roof Held; tampered-shadow caught by the AGT round-trip.
- `UNVERIFIED`: the **live acer↔liris two-fabric traversal over Hilbra** — this crate is the throat;
  the live crossing (two physical mouths) is the next rung. Also no `SYSTEM_AFFIRMED` seal yet (council fallback).
- `BOUNDARY`: **"clone" = classical representation copy** (no-cloning respected — not a physical quantum
  clone). Shannon caps the roof: `Held` when the shadows don't jointly carry `H(object)`. No physical
  wormhole, no FTL, no quantum-transport claim.

## The arc it closes
papers → capstone (recovery) → Path-1 (recall) → Path-2 (no store) → 3D Q-PRISM (any *where*) →
slice-time (any *when*) → **the throat (both mouths + N-directional watcher, one loop)**.

## License
MIT OR Apache-2.0.
