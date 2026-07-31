Garbanzo Mindustry mod (content-pack)

What I added

- mod.hjson — the mod manifest (content-pack, no Java main). Declares a dependency on OP-Mod.
- content/items.hjson — example items (garbanzo, raw-epidonite, epidonite)
- content/blocks.hjson — example blocks (garbanzo_farm, ore-epidonite1..3)
- content/units.hjson — empty placeholder
- content/liquids.hjson — liquid-epidonite
- sprites/ (placeholder + your provided sprites)

Dependency note

This mod declares a dependency on "OP-Mod" (case-sensitive). You must install the OP-Mod mod (for example: https://github.com/Delourians/OP-mod) alongside this mod for everything to work, since some research/ids reference content provided by OP-Mod.

How to install locally on Android

1. I can publish a ready-to-download ZIP with mod.hjson at the archive root so Mindustry accepts it.
2. Download the ZIP on your Android device.
3. Move the ZIP to /sdcard/Android/data/io.anuke.mindustry/files/mods/ or open Mindustry → Mods → Import and select the ZIP.
4. In Mindustry → Mods, enable both "OP-Mod" and "Garbanzo" (order doesn't strictly matter), and then start a game.

Notes

- If OP-Mod has the mod id spelled differently, adjust mod.hjson `dependencies` accordingly. I tried to find the upstream repo and a likely match is https://github.com/Delourians/OP-mod — if that is the one you meant, the id may be "OP-Mod" (case-sensitive) as you said. If you want me to verify the exact id inside that repo's mod.hjson, reply “confirm id” and I will fetch it and update.
- If you prefer the mod to be standalone (no external dependency), I can duplicate the OP-Mod assets (ruby, rl-turret tech, surge-alloy, etc.) in this mod, but that may cause conflicts if OP-Mod is also installed.

Next steps I can take

- Publish a ZIP you can download on Android now (reply “publish”).
- Verify OP-Mod's exact mod id in the upstream repo and update `dependencies` if needed (reply “confirm id”).
- Make the mod standalone by adding stubs for missing OP-Mod content (reply “stub it”).

