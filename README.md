# Quake Overhaul PNG Pack

PNG converted textures contained in .wad files from the [WDU's Quake WAD Overhaul Project](https://valvedev.info/tools/quake-wad-overhaul-project/).

## What's included?

- quake_base folder-contains png textures from the base.wad
- quake_desert folder—contains png textures from the desert.wad
- quake_impel folder—contains png textures from the impel.wad
- quake_medieval folder—contains png textures from the medieval.wad
- quake_misc folder-contains png textures from the misc.wad
- quake_runic folder-contains png textures from the runic.wad

## About WDU's Quake WAD Overhaul Project

The pack features every texture featured in the original build of Quake, Mission Pack 1: Scourge of Armagon, Mission Pack 2: Dissolution of Eternity, Mission Pack 3: Abyss of Pandemonium, and many id-sourced textures that were never used in the original maps, lifted from the [original texture sources](https://valvedev.info/tools/quake-wad-overhaul-project/city5_source.png). Duplicates were weeded out, and every texture has been renamed and re-sorted into WADs of each one of the game's texture themes.

![A sample of the desert WAD](https://github.com/user-attachments/assets/ce1b2e57-408a-47d9-8306-6b4d3ad0c6e8)

### What was wrong with the original WADs?

The original WADs that new mappers are often told to use did not come from id themselves. These WADs are messy, sorted badly, and come with many textures that are unusable as textures themselves (notably, the item textures and a colormap, which no editor I know of has ever needed). Even internally, id did not keep their texture usage straight.

- Textures ripped from the original game often have very sporadic name and numbering schemes.
- Duplicate textures are common. (All of the "wizmet" textures, for example, are duplicates of existing runic textures.)
- Cases where textures have shared names have also cropped up, causing them to overwrite one another when added to the same WAD.
- id did not use all assets created for Quake. Many textures that fit perfectly within the game's themes were not used in the original maps at all, meaning they've been mostly off-limits to mappers. These are usually referred to as "beta" textures. (The mission packs did make use of these textures on occasion; the green "hipnotic" sky was originally used in DM7, an unreleased id map.)
- Despite the mission packs sharing the same texture themes, these are rarely integrated and new mappers are likely to miss them, meaning much less variety in textures used in new maps.

What we've done is re-sort all textures into different WADs based on theme, with the mission pack and "beta" textures mixed in for variety. This is by far the most complete selection of textures you'll find in one set of WADs. We've also fixed the numbering scheme in the hopes that it'll make finding the right texture easier.

![A sample of the medieval WAD](https://github.com/user-attachments/assets/c2239c91-15b6-4e2e-a779-d433003f75b3)

## Texture themes
- idbase—The military base theme, as seen at the start of each id1 (Quake) episode and as the first episode of hipnotic (Scourge of Armagon). Stripes, strips of rivets, technology, and the occasional bit of grime.
- Desert—a composite of the unreleased Aztec textures and textures that were later used in rogue (Dissolution of Eternity). Sandy bricks, red clay, grey stonework, and ornate detailing often featuring skulls, suns, daggers, pharaohs, and wings.
- Impel—not a true theme, but features the textures seen in impel (Abyss of Pandemonium). We've elected to not mix them with the rest of the themes, as impel textures tend to be redrawn versions of existing textures. They're named the same as their id1 counterparts, however, so if you were to load impel.wad into your editor of choice, the impel textures would replace the originals in the map.
- Medieval—a composite of general medieval textures, the elder world textures, commonly seen in Episode 4 of id1, and the wizard textures most notably used in E1M3. Textures found in hipnotic's second and third episodes are also commonly found here. Brown and green brickwork, bronze doors, rotting woodwork, and mangled, disemboweled torture victims. (While Wizard and Elder both have their distinctive looks, we're keeping this simple, and they fit mostly into the general Medieval theme regardless.)
- Runic—The metallic theme, commonly seen in Episode 3 of id1 and throughout the rest of the game. Copper and metallic tones, decorative light fixtures, demon faces, runes, skulls, and spilt blood throughout.
