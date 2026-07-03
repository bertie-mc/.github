# bertie-mc

Custom **NeoForge 1.21.1** mods built for the *bertie* modpack. Public repos are MIT-licensed; each has CI that builds on every push and publishes a **GitHub Release** with the JAR on version tags (`v*`).

## 🧩 Content mods

| Mod | What it does | Build |
|-----|--------------|-------|
| [carving](https://github.com/bertie-mc/carving) | Carve tool heads & armor from material slates | ![Build](https://github.com/bertie-mc/carving/actions/workflows/build.yml/badge.svg) |
| [berlords-food-system](https://github.com/bertie-mc/berlords-food-system) | Valheim-style stomach-slot food & buff system | ![Build](https://github.com/bertie-mc/berlords-food-system/actions/workflows/build.yml/badge.svg) |
| [berlords-emi](https://github.com/bertie-mc/berlords-emi) | Native EMI recipe plugins for JEI-only mods | ![Build](https://github.com/bertie-mc/berlords-emi/actions/workflows/build.yml/badge.svg) |
| [explode-to-mine](https://github.com/bertie-mc/explode-to-mine) | Ores must be exploded before they can be mined | ![Build](https://github.com/bertie-mc/explode-to-mine/actions/workflows/build.yml/badge.svg) |
| [ender-eyes](https://github.com/bertie-mc/ender-eyes) | Helmet enchant: Endermen ignore your gaze | ![Build](https://github.com/bertie-mc/ender-eyes/actions/workflows/build.yml/badge.svg) |
| [withered-hearts](https://github.com/bertie-mc/withered-hearts) | Trims the withered heart bar to what the Wither drains | ![Build](https://github.com/bertie-mc/withered-hearts/actions/workflows/build.yml/badge.svg) |
| [bertie-filters](https://github.com/bertie-mc/bertie-filters) | FTB filter for Slag 'n' Embers wooden modular parts | ![Build](https://github.com/bertie-mc/bertie-filters/actions/workflows/build.yml/badge.svg) |

## 🔧 Compatibility & fixes

| Mod | Patches | Build |
|-----|---------|-------|
| [bush-tweaks](https://github.com/bertie-mc/bush-tweaks) | Berries & Cherries bushes → vanilla sweet-berry behavior | ![Build](https://github.com/bertie-mc/bush-tweaks/actions/workflows/build.yml/badge.svg) |
| [rustic-engineer-fix](https://github.com/bertie-mc/rustic-engineer-fix) | Rustic Engineer airship/dragonfly flight | ![Build](https://github.com/bertie-mc/rustic-engineer-fix/actions/workflows/build.yml/badge.svg) |
| [short-circuit-fix](https://github.com/bertie-mc/short-circuit-fix) | Short Circuit translucent render layer | ![Build](https://github.com/bertie-mc/short-circuit-fix/actions/workflows/build.yml/badge.svg) |
| [fd-shader-fix](https://github.com/bertie-mc/fd-shader-fix) | fdlib shader-load boot crash | ![Build](https://github.com/bertie-mc/fd-shader-fix/actions/workflows/build.yml/badge.svg) |
| [frozen-reg-fix](https://github.com/bertie-mc/frozen-reg-fix) | Immersive Armors "registry is already frozen" crash | ![Build](https://github.com/bertie-mc/frozen-reg-fix/actions/workflows/build.yml/badge.svg) |

## 🔒 Ports (private — pending upstream license review)

- **neko-neoforge** — NeoForge port of *Neko's Enchanted Books* (Infernal Studios)
- **explosive-enhancement** — NeoForge reimplementation of *Explosive Enhancement* (Superkat32)

---

<sub>All mods target NeoForge 1.21.1 (Java 21). To cut a release: tag a repo <code>vX.Y.Z</code> and push the tag — CI builds and attaches the JAR to a GitHub Release.</sub>
