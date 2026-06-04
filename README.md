# Endfield Randomizer

Randomizer UI for:
- selecting and filtering characters
- selecting and filtering weapons with per-weapon count limits
- selecting stage or CC mode (one mode at a time)

## Behavior

- Defaults to selecting all characters, weapons, stages, and CC entries.
- Randomization output includes:
  - 4 unique characters
  - 1 weapon per character (respecting weapon type compatibility and count limits)
  - either 1 stage (with level) or 1 CC

## Notes

- Stage and CC cannot both be used in one roll.
- Character and weapon search bars are shown above filters.
- Character/weapon filter sections (and each filter group) are collapsible and collapsed by default.
- Character and weapon filters are multi-select chips (class, element, faction, weapon type, category).
- Characters, weapons, and stages are shown as compact image-only selectable cards with name tooltips.
- Character and weapon image cards use rarity-colored `img-bg-X` backgrounds.
- Selected cards use a bright "priority-2" style outline.
- Stage/CC radio mode hides the inactive section and clears its selection.
- CC tag randomization is not implemented yet.
- Placeholder images were added for missing character/weapon/stage images.

