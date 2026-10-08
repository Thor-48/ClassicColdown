# ClassicColdown

ClassicColdown is a lightweight Minecraft plugin that adds configurable per-item cooldowns for weapons, armor, food, shields and more, in the style of classic PvP combat.

## Features

- **Custom Item Cooldowns**: Set a cooldown for almost any item with a single command.
- **Weapon Cooldowns**: Swords, axes, spears and maces start their cooldown when you hit something.
- **Food & Potion Cooldowns**: Cooldown starts when the item is consumed.
- **Projectile Cooldowns**: Bows, crossbows, tridents and throwables start their cooldown when launched.
- **Shield Cooldowns**: Shields go on cooldown when an axe disables them.
- **Armor Enchantment Cooldowns**: Protection, Fire/Blast/Projectile Protection, Unbreaking and Mending go on cooldown after a piece absorbs a hit. Thorns is not affected.
- **Boss Bar Display**: Armor cooldowns are shown with a boss bar. Pieces that expire at the same time share one bar.
- **Spear Support**: The charge attack has its own time window, and Lunge is removed from the spear until the cooldown is over.
- **Persistent Cooldowns**: Cooldowns are saved and survive restarts and relogs.
- **Tab Completion**: Commands automatically suggest subcommands and items.
- **Permission Support**: All commands are protected by the `classiccooldown.admin` permission.

## Commands

### `/cooldown add hand <seconds>`

Sets a cooldown for the item in your main hand.

**Permission:** `classiccooldown.admin`  
**Default:** OP

### `/cooldown add item <material> <seconds>`

Sets a cooldown for a specific item.

**Permission:** `classiccooldown.admin`  
**Default:** OP

### `/cooldown reset hand`

Removes the cooldown of the item in your main hand and restores vanilla behavior.

**Permission:** `classiccooldown.admin`  
**Default:** OP

### `/cooldown reset item <material>`

Removes the cooldown of a specific item.

**Permission:** `classiccooldown.admin`  
**Default:** OP

### `/cooldown reset all`

Removes all configured cooldowns.

**Permission:** `classiccooldown.admin`  
**Default:** OP

### `/cooldown list`

Shows all configured cooldowns.

**Permission:** `classiccooldown.admin`  
**Default:** OP

### `/cooldown reload`

Reloads the config.

**Permission:** `classiccooldown.admin`  
**Default:** OP

## Permission

| Permission | Description | Default |
|---|---|---|
| `classiccooldown.admin` | Allows the use of all ClassicColdown commands. | OP |

## Configuration

| Option | Description | Default |
|---|---|---|
| `spear-charge-window-ms` | How long (in ms) hits count as part of a spear charge attack. | `3000` |

## Requirements

- Minecraft **1.21+** (spear features require a version that includes spears, 1.21.11+)
- Paper
- Permission `classiccooldown.admin`

## Support & Community

[**Website**](https://why-luca.bot-keep.xyz/)  
[**DC Server for Custom Plugins**](https://discord.com/invite/D8DtJF2Jye)

## License

ClassicColdown is licensed under the **ClassicColdown License**.

You may use, modify, and redistribute the plugin, including on commercial servers. However, the original plugin and modified versions may **not be sold**.

[**View the full ClassicColdown License**](https://github.com/Thor-48/ClassicColdown/blob/main/LICENSE.md)
