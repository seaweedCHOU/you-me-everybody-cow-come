# You Me Everybody Cow Come

The original, full Codex skill for transforming source photographs into the established Cow Come visual style.

This repository contains the complete skill instructions, detailed style specification, Codex interface metadata, and the visual calibration assets used by the skill.

## Examples

![Cow Come skill cover](examples/01-cover.png)

![Cow Come character holding a sandwich](examples/02-sandwich.png)

![Cow Come character seated outdoors](examples/03-seated-outdoors.png)

![Cow Come interior scene](examples/04-interior.png)

![Cow Come character gesturing](examples/05-gesture.png)

![Cow Come character drinking](examples/06-drink.png)

![Cow Come character taking a selfie](examples/07-selfie.png)

## Install

Copy this repository into your Codex skills directory so that `SKILL.md` is located at:

```text
$CODEX_HOME/skills/you-me-everybody-cow-come/SKILL.md
```

Restart or reload Codex after installation, then invoke the skill as `$you-me-everybody-cow-come`.

## Contents

- `SKILL.md` — main workflow and generation rules
- `references/style-spec.md` — detailed visual construction specification
- `references/legacy-ocean-assets.md` — optional ocean-scene reference notes
- `agents/openai.yaml` — Codex interface metadata
- `assets/` — authoritative targets and supporting calibration boards

## Image assets

The repository includes generated Cow Come calibration targets and showcase images. Original source photographs are not included.
