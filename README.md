# L1FE / AWAKEN 014: THE POSSIBILITY ENGINE

A working experimental platform for evolving **bounded numerical physics laws** across miniature simulated worlds and preserving a diversity of outcomes.

## Run

Requires Node 20+, no external dependencies.

```bash
npm test
npm run discover -- --generations 100 --seed 2026
npm run serve
```

Open **http://localhost:4173**. Press **Discover 24 Worlds** to search for different physics genomes, choose a niche to fork reality, and paint charge or structures into the field. **F** fullscreen, **H** hide UI, **Space** pause, **1–4** choose visualization.

## Architecture

- `src/engine.mjs`: deterministic field simulation, bounded physics mutation, counterfactual seeded tests, quality-diversity archive.
- `src/cli.mjs`: reproducible batch discovery and JSON export.
- `src/server.mjs`: local dependency-free HTTP server.
- `web/index.html`: interactive cinema viewer and world intervention.
- `tests/engine.test.mjs`: replay, boundedness, validation, effect-of-physics, search reproducibility.
- `.github/workflows/test.yml`: automated CI.

## What this does and does not demonstrate

This prototype evolves **seven numerical coefficients** controlling diffusion, conductivity, ignition, decay, regrowth, persistent memory, and coupling. It does not evolve arbitrary source code, implement organism-owned inner models, or establish open-ended evolution. There are coupled material fields, **not evolving autonomous agents yet**.

The repertoire follows a simplified MAP-Elites-inspired approach, preserving strong candidates in niches defined by charge activity and energy variance. It is not a dependency on pyribs, and no external research code is copied. Novel discoveries require held-out replication and mechanism tests.

## Next

1. Add autonomous constructor agents with typed, evolvable operator programs.
2. Test inherited miniature predictive models against held-out outer worlds.
3. Introduce event provenance, causal interventions, and stronger diversity measures.
4. Benchmark worker and GPU implementations before scaling.
5. Add a separate native-resolution renderer without coupling it to the physics time-step.
