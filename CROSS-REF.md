# CROSS-REF — mycelium-std-swap

Mycelium-internal dependencies only (steer handoff §6.1; external crates stay in Cargo
metadata). Pinned revs are the fixed (buildable) tips recorded by the Phase-B wave;
content hash = git tree hash of the pinned rev.

| Interface consumed | Repo | Pinned rev | Content hash | Notes |
|---|---|---|---|---|
| mycelium-cert | https://github.com/tzervas/mycelium-runtime | `ab9cee665b620ed80ab74ea61ea639817dc49077` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-cert` (see monorepo `docs/api-index/INDEX.md#mycelium-cert`) |
| mycelium-core | https://github.com/tzervas/mycelium-core | `781d3fcceba82acfe6b0eb46650513bd78a2416b` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-core` (see monorepo `docs/api-index/INDEX.md#mycelium-core`) |
| mycelium-numerics | https://github.com/tzervas/mycelium-value | `fce92daed05e9f10202c202648ec43fb0a6991d7` | tree `(tree hash: fetch dep rev locally to resolve)` | Rust API of `mycelium-numerics` (see monorepo `docs/api-index/INDEX.md#mycelium-numerics`) |

**Owning docs:** `docs/spec/stdlib/swap.md` (slice in this repo) · RFC-0016.
**Source provenance:** extracted from `tzervas/mycelium` archive `aad96b7a…`; fixed by
the course-correction Phase B (workspace root, git pins, toolchain + supply-chain
replicas, CI v2). Full program record: monorepo
`docs/planning/course-correction-2026-07-18/PROGRAM.md`.
