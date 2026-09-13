# HH3 Ported Additions - Release-ready repository

For the most reliable BattleScribe installation, create a GitHub Release after uploading this repository.
The included `publish-catpkg.yml` workflow will generate the official `.bsi`, `.bsr`, `.catz`, and `.gstz` release assets.

Use this URL in BattleScribe after the first release finishes publishing:

`https://github.com/kobychapmans-ship-it/Hh3.0-conversion2/releases/latest/download/Hh3.0-conversion2.latest.bsi`

The raw `main/index.bsi` file is retained as a fallback, but the release asset URL is the recommended installation path.

---

# HH3 Ported Additions - Unbound Force (BattleScribe Complete v1.1)

This repository is an add-on catalogue for the original Horus Heresy 1.0 BattleScribe game system.

## BattleScribe URL

`https://raw.githubusercontent.com/kobychapmans-ship-it/Hh3.0-conversion2/main/index.bsi`

## Important fix in v1.1

The repository index now includes the **original HH1 game-system package** as well as the add-on catalogue.
This makes the repository self-contained from BattleScribe's perspective and avoids the catalogue being skipped when the parent game system is not already resolved from another repository.

Required files at repository root:

- `index.bsi`
- `index.xml`
- `The.Horus.Heresy.gstz`
- `HH3.Ported.Additions.Unbound.Force.catz`

The add-on catalogue revision is now **2** so BattleScribe will detect it as newer than the previous attempt.

## Force

Create a force named:

**Unbound Force - HH3 Ported Additions**

Then choose exactly one **Force Source** filter. There are no standard Force Organisation restrictions.

## Offline fallback

`HH3.Ported.Additions.Unbound.Force.bsr` is included. It can be imported directly using BattleScribe's **Import Data From File** option if needed.
