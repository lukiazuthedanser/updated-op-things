Garbanzo Mindustry mod (content-pack)

What I added

- mod.hjson — the mod manifest (content-pack, no Java main)
- content/items.hjson — a single example item (id: garbanzo)
- content/blocks.hjson — empty array (placeholder for your blocks)
- content/units.hjson — empty array (placeholder for your units)

How to install locally

1. Zip the repository contents so that mod.hjson sits at the top level in the zip (or copy the entire repo directory).
2. Put the zip (or folder) into your Mindustry/mods/ directory.
3. Start Mindustry and enable the "Garbanzo" mod in the Mods menu.

How to expand the mod

- Add sprites/images in a `sprites/` directory and reference them in your content files using the matching filename (without extension).
- Edit content/*.hjson to add items, blocks, units, and other content. Mindustry uses HJSON for content files — they are human-friendly JSON. Keep the files as arrays of objects.
- If you need custom logic (new behaviors, UI, or hooks) you'll need to switch to a Java/Kotlin mod with a `main` entry in mod.hjson and a compiled jar.

Notes

- This is a minimal content-pack scaffold so you can start adding content assets and HJSON definitions. If you want, I can:
  - add example blocks/units with valid properties,
  - create a sprites placeholder and a sample icon,
  - or convert this to a Java/Kotlin mod skeleton with Gradle and a main class.

Next steps I can take now

- Populate the content files with concrete example blocks/units (I can add a simple block and unit that work on recent Mindustry versions).
- Create a sample sprite and include it.
- Convert this scaffold into a Java/Kotlin mod if you prefer custom code.

