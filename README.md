# AION — Cosmos Holographic Membrane

AION is a browser-only 3D research visualization of a 512-channel OES-32
latching simulation. Open `index.html` directly or visit the published Pages
site:

<https://sparkainlp-x.github.io/Cosmos-Holographic-Membrane-Simulation/>

## Scope

This is research visualization only. It is not medical advice, certified
hardware, a diagnostic tool, or a performance benchmark. The app makes no
claim based on the 94.92% QECC table, which is intentionally not included.

The documented model definitions are:

- `W = 512`
- `R = max|x − xref|`
- `τ = 0.08`
- `μ(i) = (i + 256) mod 512`
- `FOLD8 = 64 × 8`
- `SAFE = A ∧ C0 ∧ C1 ∧ C_fold`

These definitions are not a certification or a measured result.

## Development

No build step or dependency is required. Serve the repository with any static
HTTP server for local testing, or open `index.html` in a modern browser.

See [LICENSE](LICENSE), [NOTICE](NOTICE), and [SECURITY.md](SECURITY.md).