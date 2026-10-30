# 🐉 DM Toolkit

A single-file web app for running a D&D 5e session as the Dungeon Master: party stat sheet, combat tracker, dice roller and SRD reference. No install, no account, no server.

## Launch it

- **Online:** open https://infinitelyeducated-bot.github.io/dm-toolkit/
- **Offline:** download `index.html` and double-click it. It opens in any modern browser.

Your data is stored in your own browser (local storage). Nothing is uploaded. Use **Export** for backups.

## What it does

- **Party & Combat sheet:** name, class, level, AC, HP (with − / + damage and healing), speed, Init, passive perception, six ability scores with modifiers, temp HP, death saves, conditions, resources and notes. Scroll the mouse wheel over any number field to adjust it (Shift = ±10).
- **Turn order:** *Roll for Player Order* rolls d20 + Init for everyone and re-rolls ties; reorder by hand with ▲ / ▼. *End Turn ▶* moves to the next combatant and counts rounds. The current player has a yellow outline, monsters and NPCs an orange one.
- **Monsters & NPCs:** add custom NPCs or search the SRD (needs internet) and add them to the order.
- **Dice roller:** 1–20 dice, each its own d4 / d6 / d8 / d10 / d12 / d20 / d%; modifier, advantage and disadvantage, ability and skill checks, per-player saved dice setups and named roll presets. History shows every roll with the player's name.
- **Campaigns & safety:** named campaigns, session notes and loot log, undo, auto-save, export/import, optional timed auto-backup, print view, light theme and larger text. *Reset App* wipes everything after a warning.
- **DM Guide tab:** browse SRD monsters (full stat blocks), spells, classes, races, rules, equipment and more from [dnd5eapi.co](https://www.dnd5eapi.co). Links to the official PHB, DMG and Monster Manual are included. The app has a built-in **❓ How to Use** guide.

## Notes

- The SRD content is © Wizards of the Coast under the OGL / CC-BY and is fetched live; the full rulebooks are not included.
- Browser storage is per browser and per device. Clearing site data erases it, so export regularly.

## License

MIT for the app code. See `LICENSE`.
