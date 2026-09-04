# wacha Minecraft — packwiz modpack

This repo hosts the **generated** packwiz client-distribution pack for the wacha
Minecraft server. Do not hand-edit anything here — it's overwritten on every sync.

Source of truth: `mods.yaml` in the private `wacha-minecraft/mc-config` repo. See
that repo's `pack/README.md` for how mods are declared and how the pack is
regenerated, and `pack/tools/generate-pack.js` for the generation logic.

## For players

```
java -jar packwiz-installer-bootstrap.jar https://raw.githubusercontent.com/wacha-minecraft/mc-config-pack/main/pack.toml
```

See the private repo's `pack/README.md` for full instructions (Prism Launcher, etc).
