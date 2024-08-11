## Comparison with [1.14 Pre-Release 1](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.14 Pre-Release 1)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Translations](#translations)
- [File structure](#file-structure)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">1.14 Pre-Release 1</th><th>1.14 Pre-Release 2</th></tr><tr><td>World version</td><td><code>1947</code></td><td><code>1948</code></td></tr><tr><td>Protocol version</td><td><code>472</code></td><td><code>473</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
custom_stat.txt
</summary>

```diff
+ minecraft:bell_ring
+ minecraft:interact_with_cartography_table
+ minecraft:interact_with_loom
+ minecraft:interact_with_stonecutter
+ minecraft:raid_trigger
+ minecraft:raid_win
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
universal_tags/custom_stat.json
</summary>

```diff
+ minecraft:bell_ring
+ minecraft:interact_with_cartography_table
+ minecraft:interact_with_loom
+ minecraft:interact_with_stonecutter
+ minecraft:raid_trigger
+ minecraft:raid_win
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ advancements.adventure.hero_of_the_village.description: Successfully defend a village from a raid
+ advancements.adventure.hero_of_the_village.title: Hero of the Village
+ advancements.adventure.voluntary_exile.description: Kill a raid captain.
Maybe consider staying away from villages for the time being...
+ advancements.adventure.voluntary_exile.title: Voluntary Exile
- block.minecraft.illager_banner: Illager Banner
+ block.minecraft.ominous_banner: Ominous Banner
+ options.discrete_mouse_scroll: Discrete Scrolling
+ options.mouse_settings: Mouse Settings...
+ options.mouse_settings.title: Mouse Settings
+ options.mouseWheelSensitivity: Scroll Sensitivity
+ stat.minecraft.bell_ring: Bells Rung
+ stat.minecraft.interact_with_cartography_table: Interactions with Cartography Table
+ stat.minecraft.interact_with_loom: Interactions with Loom
+ stat.minecraft.interact_with_stonecutter: Interactions with Stonecutter
+ stat.minecraft.raid_trigger: Raids Triggered
+ stat.minecraft.raid_win: Raids Won
+ stat.minecraft.ring_bell: Bells Rung
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancements/adventure/hero_of_the_village.json
+ minecraft/advancements/adventure/voluntary_exile.json
```

</details>
</details>