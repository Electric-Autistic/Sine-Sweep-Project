# Sine-Sweep-Project

Collection of EQ APO files ear tuned using Sine Sweep technique and cleaned up frequencies.

This repository is for headphone and earbud enthusiasts who like to chase better sound—especially for less common or older models that are hard to find good presets for.

## What this project is

- A community-friendly library of **Equalizer APO-compatible** parametric EQ presets.
- Tuned by ear using sine sweep checks and frequency cleanup.
- Focused on subjective listening, though the idea would be to approach Harman Targets.

If you are an audiophile looking for obscure presets, this is built for you. If you are new to EQ and just want your gear to sound better, this is also for you.

## Preset library

Current presets included:

| Brand | Model | Preset File |
|---|---|---|
| Audio Technica | EM7x | `Audio Technica/Audio Technica EM7x.txt` |
| JBL | TUNE310C | `JBL/JBL TUNE310C.txt` |
| Motorola | Moto Buds | `Motorola/moto buds.txt` |

## Quick start (Equalizer APO)

1. Install [Equalizer APO](https://sourceforge.net/projects/equalizerapo/).
2. Install Peace EQ
 (GUI for Equalizer APO) from [Peace project](https://sourceforge.net/projects/peace-equalizer-apo-extension/).
3. Download a preset file from this repository.
4. Open Peace, import the `.txt` file, and apply it to your device.
5. Test with your favorite music and adjust if needed.

### Important notes

- **Preamp matters**: keep the included preamp value to avoid clipping.
- Start at moderate volume when testing any new preset.
- Small unit-to-unit and ear-fit differences are normal, especially with IEMs and buds.

## How to use and tweak

- Treat each preset as a strong baseline.
- If treble feels hot, reduce upper filters by small steps (for example, 0.5–1.0 dB).
- If bass is too light or heavy, adjust low-shelf gain first before changing many peak filters.
- Make one change at a time and A/B test with familiar tracks.

Or simply tweak Bass/Treble instead of overly complicated Parametric EQ, we've done it too, it's fine.

## Contributing

Contributions are welcome, especially for uncommon models.

Suggested contribution format:

- One preset file per device model.
- Keep standard Equalizer APO syntax (`Preamp`, `Filter n:` lines).
- Use clear naming: `Brand/Model.txt`.
- In your PR, include:
	- Device name and revision (if known)
	- Brief tuning goal (for example: reduce shout, smooth 7–10 kHz)
	- Any fit/tip/source assumptions

If you'd like you could contact us to send us a pair of cheap earbuds or whatever obscure headphones you have and we tune them, free of charge.

## Project philosophy

- Ear-tuned, practical, and transparent.
- Favor cleaner tonal balance and fatigue reduction.
- Tendency towards Harman Target
- Share presets openly so others can refine and build on them.

## License

Licensed under **GNU GPL v2.0**. See [LICENSE](LICENSE).
