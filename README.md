# Codex Pets

Custom Codex pet assets.

## SURGe Wombat

SURGe Wombat is a cute wombat Codex pet wearing a small Splunk SURGe shirt.

The installable package is:

```text
pets/surge-wombat/
```

Package files:

- `pet.json` - Codex pet manifest.
- `spritesheet.webp` - Codex-compatible 8x9 RGBA spritesheet.

QA files:

- `qa/surge-wombat/contact-sheet.png` - visual contact sheet for all animation rows.
- `qa/surge-wombat/validation.json` - hatch-pet validation output.

## Install

Copy the pet folder into your local Codex pets directory:

```bash
mkdir -p ~/.codex/pets/surge-wombat
cp pets/surge-wombat/pet.json ~/.codex/pets/surge-wombat/pet.json
cp pets/surge-wombat/spritesheet.webp ~/.codex/pets/surge-wombat/spritesheet.webp
```

Restart Codex so the app can load the new pet.

## Verify

The spritesheet passed hatch-pet validation:

```text
ok: true
errors: []
warnings: []
```

Use `qa/surge-wombat/contact-sheet.png` to visually inspect the idle, running, waving, jumping, failed, waiting, active running, and review animation rows.
