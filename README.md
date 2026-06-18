# PSYCHRONIC_BattleEngineMZ

**RPG Maker MZ Plugin**

Psychronic Battle Engine (Event-Driven Fixed with Projectiles and Actor Positioning)

## What It Does

Psychronic Battle Engine (Event-Driven Fixed with Projectiles and Actor Positioning).

## Plugin File

- `PSYCHRONIC_BattleEngineMZ.js`
- Target: RPG Maker MZ
- Author: Psychronic
- URL: https://psychronic.itch.io

## Parameter Summary

- actorBattlerSettings
- enemyBattlerSettings
- battleOrientation
- actorPositions
- enableCustomPositions: Enable custom actor positioning. If false, uses default MZ positioning.
- stateOverlaySpeed: Animation speed multiplier for state overlays (poison, etc.). Lower = faster.
- enableActorEscape: Add an Escape command to the actor command window during battle.
- escapeCommandText: The text to display for the escape command.
- enemyStateDisplay
- enemyStateIconOffsetX: X position offset for enemy state icons.
- enemyStateIconOffsetY: Y position offset for enemy state icons.
- enemyStateAnimOffsetX: X position offset for enemy state animations/overlays.
- enemyStateAnimOffsetY: Y position offset for enemy state animations/overlays.
- damageFontSize: Font size for damage popups.
- damageDigitWidth: Width multiplier for each digit (1.0 = auto, higher = more spacing).
- damageOutlineWidth: Outline width for damage numbers (0 = no outline).
- damagePopupDuration: How long damage popups stay visible (in frames).
- hpDamageColor: Color for HP damage (hex code, e.g., #ffffff for white).
- hpHealColor: Color for HP recovery (hex code, e.g., #80ff80 for green).
- mpDamageColor: Color for MP damage (hex code, e.g., #ffffff for white).
- mpHealColor: Color for MP recovery (hex code, e.g., #80b0ff for blue).
- damagePopupOffsetX: X position offset for damage popups (relative to battler).
- damagePopupOffsetY: Y position offset for damage popups (relative to battler, negative = above).
- type
- charsetSpeed: Frame speed for charset battlers. Only applies if Type is Charset.
- Additional parameters are documented in the plugin header/help text.

## Installation

1. Download `PSYCHRONIC_BattleEngineMZ.js`.
2. Place it in your RPG Maker MZ project's `js/plugins/` folder.
3. Enable it from the RPG Maker Plugin Manager.
4. Configure any plugin parameters or commands listed below.

## Source

This standalone repository is generated from the latest PSYCHRONIC plugin source in the RPG Reactor Complex template.

## License

MIT. See `LICENSE`.
