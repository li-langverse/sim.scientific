# sim.scientific

Official Li package mirror for the **scientific and engineering simulation** vertical (**PH-SCI**): molecular dynamics (LJ) smokes, 2D heat/PDE field setup, rigid-body integration hooks, and `run_algo` / `run_simulation` dispatch aligned with [`sim`](https://github.com/li-langverse/sim).

| | |
|---|---|
| **Import** | `import sim.scientific` |
| **Package id** | `PKG-li-sim-scientific` (`li-sim-scientific` in `li.toml`) |
| **Base sim API** | [li-langverse/sim](https://github.com/li-langverse/sim) â€” `SimRunResult`, vertical/algo ids |
| **Vision / RFC** | [world-studio-vision Â§ PH-SCI](https://github.com/li-langverse/lic/blob/main/docs/game-dev/world-studio-vision.md) (monorepo copy) |

## Build smoke

CI and local mirror checks use **`lic check`** on the library entry (same as [`.github/workflows/ci.yml`](.github/workflows/ci.yml)):

```bash
# Build lic first: https://github.com/li-langverse/lic â€” then:
/path/to/lic/build/compiler/lic/lic check src/lib.li
```

From a full **lic** monorepo checkout with sibling packages (`li-sim`, `li-physics-particles`, `li-physics-rigid`), path deps in `li.toml` resolve; this repo is the **standalone mirror** for org publishing and package CI.

## License

GPL-3.0-or-later OR MIT â€” see `li.toml`.
